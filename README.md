# kuber-installer-ubuntu
> This repo containes a bash file for installing  and configuring container runtime Docker and Kubernetes on ubuntu 20.04 or higher

I created this script because I got bored of installing <br> Kuberntes & Docker repetedly on different servers <br> I want to automate this task so have fun go ahead & enjoy 😎

## Prerequisite
```bash
sudo apt install curl
```
## How to use
 > Just run this single command

### For installing Kuberneres on server
```bash
sudo curl "https://raw.githubusercontent.com/nkroker/kuber-installer-ubuntu-20.04/master/installer.sh" | bash
```

### For installing minikube on local machine
```bash
sudo curl "https://raw.githubusercontent.com/nkroker/kuber-installer-ubuntu-20.04/master/minikube-installer.sh" | bash
```

## PSA
> Please run at your own risk
