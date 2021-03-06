安装环境：

虚拟机两台

CPU：4核

内存：8G

内核：3.10.0-514.26.2.el7.x86\_64

操作系统：CentOS Linux release 7.3.1611

注意安装版本：

[http://rancher.com/docs/rancher/v1.6/en/hosts/\#supported-docker-versions](http://rancher.com/docs/rancher/v1.6/en/hosts/#supported-docker-versions)

### SUPPORTED DOCKER VERSIONS {#supported-docker-versions}

|  | Version | Supported? | Kubernetes Supported? | Windows Supported? | Install Script |
| :--- | :--- | :--- | :--- | :--- | :--- |
|  | `1.9.x`and lower | No |  |  |  |
|  | `1.10.0`-`1.10.2` | No |  |  |  |
| `1.10.3`\(and higher\) | No\(Yes in v1.6.5 and lower\) | No | No | \`curl [https://releases.rancher.com/install-docker/1.10.sh](https://releases.rancher.com/install-docker/1.10.sh) | sh\` |
| `1.11.x` | No |  |  | \`curl [https://releases.rancher.com/install-docker/1.11.sh](https://releases.rancher.com/install-docker/1.11.sh) | sh\` |
|  | `1.12.0`-`1.12.2` | No |  |  |  |
| `1.12.3`\(and higher\) | **Yes** | **Yes** | No | \`curl [https://releases.rancher.com/install-docker/1.12.sh](https://releases.rancher.com/install-docker/1.12.sh) | sh\` |
| `1.13.x` | **Yes** | **Yes**\(Kubernetes version 1.8\) | No | \`curl [https://releases.rancher.com/install-docker/1.13.sh](https://releases.rancher.com/install-docker/1.13.sh) | sh\` |
| `17.03.x-ce` | _**Yes**_ | _**Yes**\(Kubernetes version 1.8\)_ | _No_ | _\`curl _[_https://releases.rancher.com/install-docker/17.03.sh_](https://releases.rancher.com/install-docker/17.03.sh) | _sh\`_ |
|  | `17.03.x-ee` | **Yes** | **Yes**\(Kubernetes version 1.8\) | No | n/a |
| `17.04.x-ce` | No | No | No | \`curl [https://releases.rancher.com/install-docker/17.04.sh](https://releases.rancher.com/install-docker/17.04.sh) | sh\` |
| `17.05.x-ce` | No | No | No | \`curl [https://releases.rancher.com/install-docker/17.05.sh](https://releases.rancher.com/install-docker/17.05.sh) | sh\` |
| `17.06.x-ce` | **Yes**\(v1.6.3 and higher\) | No | No | \`curl [https://releases.rancher.com/install-docker/17.06.sh](https://releases.rancher.com/install-docker/17.06.sh) | sh\` |
|  | `17.06.x-ee` | **Yes**\(v1.6.3 and higher\) | No | **Yes**\(v1.6.13 and higher\) | n/a |
| `17.09.x-ce` | **Yes**\(v1.6.11 and higher\) | No | No | \`curl [https://releases.rancher.com/install-docker/17.09.sh](https://releases.rancher.com/install-docker/17.09.sh) | sh\` |
|  | `17.09.x-ee` | **Yes**\(v1.6.11 and higher\) | No | No | n/a |
| `17.10.x-ce` | No | No |  | \`curl [https://releases.rancher.com/install-docker/17.10.sh](https://releases.rancher.com/install-docker/17.10.sh) | sh\` |



