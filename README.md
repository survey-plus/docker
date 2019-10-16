# docker

https://github.com/survey-plus/docker
https://hub.docker.com/u/surveyplus

```bash
docker pull surveyplus/coredns:1.6.2
docker pull surveyplus/etcd:3.3.15-0
docker pull surveyplus/k8s-dns-dnsmasq-nanny-amd64:1.14.13
docker pull surveyplus/k8s-dns-kube-dns-amd64:1.14.13
docker pull surveyplus/k8s-dns-sidecar-amd64:1.14.13
docker pull surveyplus/kube-addon-manager:v9.0.2
docker pull surveyplus/kube-apiserver:v1.16.0
docker pull surveyplus/kube-controller-manager:v1.16.0
docker pull surveyplus/kube-proxy:v1.16.0
docker pull surveyplus/kube-scheduler:v1.16.0
docker pull surveyplus/pause:3.1
docker pull surveyplus/storage-provisioner:v1.8.1
docker pull surveyplus/nginx-ingress-controller:0.26.1

docker tag surveyplus/coredns:1.6.2 k8s.gcr.io/coredns:1.6.2
docker tag surveyplus/etcd:3.3.15-0 k8s.gcr.io/etcd:3.3.15-0
docker tag surveyplus/k8s-dns-dnsmasq-nanny-amd64:1.14.13 k8s.gcr.io/k8s-dns-dnsmasq-nanny-amd64:1.14.13
docker tag surveyplus/k8s-dns-kube-dns-amd64:1.14.13 k8s.gcr.io/k8s-dns-kube-dns-amd64:1.14.13
docker tag surveyplus/k8s-dns-sidecar-amd64:1.14.13 k8s.gcr.io/k8s-dns-sidecar-amd64:1.14.13
docker tag surveyplus/kube-addon-manager:v9.0.2 k8s.gcr.io/kube-addon-manager:v9.0.2
docker tag surveyplus/kube-apiserver:v1.16.0 k8s.gcr.io/kube-apiserver:v1.16.0
docker tag surveyplus/kube-controller-manager:v1.16.0 k8s.gcr.io/kube-controller-manager:v1.16.0
docker tag surveyplus/kube-proxy:v1.16.0 k8s.gcr.io/kube-proxy:v1.16.0
docker tag surveyplus/kube-scheduler:v1.16.0 k8s.gcr.io/kube-scheduler:v1.16.0
docker tag surveyplus/pause:3.1 k8s.gcr.io/pause:3.1
docker tag surveyplus/storage-provisioner:v1.8.1 gcr.io/k8s-minikube/storage-provisioner:v1.8.1
docker tag surveyplus/nginx-ingress-controller:0.26.1 quay.io/kubernetes-ingress-controller/nginx-ingress-controller:0.26.1
```