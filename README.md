# Installing Kuberentes On Ubuntu Servers
---
The purpose of this guide is to automate the installation of a Kubernetes cluster on Ubuntu Servers.
---
Before we start, let us point out couple of points.
1. The scripts available in this mainfest is tested on Ubuntu 18.04
2. The scripts available here supports only one Master Node and one or more Workers Node.
3. Two scripts to be used
..* One to install Kubernetes on the Master Node.
..* One to Install Kubernetes on the Worker Node.

## Installing Kubernetes on Master Node
---
```
curl https://raw.githubusercontent.com/tahershaker/Kubernetes-BareMetal-Install/main/MasterNodeInstall.sh | bash
```

## Installing Kubernetes on Worker Node
---
```
curl https://raw.githubusercontent.com/tahershaker/Kubernetes-BareMetal-Install/main/WorkerNodeInstall.sh | bash
```

