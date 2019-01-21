# psk8sinstall

```
apt-mark hold docker.io kubelet kubeadm kubectl
systemctl enable kubelet.service
mkdir -p $HOME/.kube
cp -i /etc/kubernetes/admin.conf $HOME/.kube/config
```
```
chown $(id -u):$(id -g) $HOME/.kube/config
```
