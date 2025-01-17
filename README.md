

```
kubectl apply -f deployment.yaml
```
```
kubectl get pods
```

```
kubectl get ingress
```

设置服务 才能访问 要不会503
```
kubectl apply -f service.yaml
```
```
kubectl get services
```

非虚拟域名访问
```
minikube service --url=true laravel-kubernetes-demo 
```

# Laravel Kubernetes Demo Application

A simple Laravel Demo Application for a Kubernetes Tutorial.

This application is a simple stateless Laravel installation for learning how to deploy a PHP application to Kubernetes.

As detailed in [this tutorial](https://learnk8s.io/blog/deploying-laravel-to-kubernetes/)


## Installation

This application is nothing more than a simple stateless Laravel installation. However if you wish to install it, simply follow these steps:

__Clone the repository__

`git clone git@github.com:learnk8s/laravel-kubernetes-demo.git`

__Install dependencies__

`composer install`

## Documentation

As detailed in [this tutorial](https://learnk8s.io/blog/deploying-laravel-to-kubernetes/)

## Support

Please email support@learnk8s.io

## License

The Laravel framework and this demo are open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
