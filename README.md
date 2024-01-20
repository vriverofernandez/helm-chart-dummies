# Kubectl

## Instalar
https://kubernetes.io/docs/tasks/tools/

# Minikube

## Instalar
https://minikube.sigs.k8s.io/docs/start/

## Crear cluster 
minikube start --cni='calico' --container-runtime='containerd' --cpus='2' --memory='2g' --nodes=2

# Helm Chart
https://helm.sh/docs/intro/install/

## Crear chart nuevo
helm create {nombre}

## Instalar chart
helm install {nombre_queramos_ponerle} ./{directorio_del_chart}

## Verificar manifiestos que me creara
helm install {nombre_queramos_ponerle} ./{directorio_del_chart} --dry-run --debug