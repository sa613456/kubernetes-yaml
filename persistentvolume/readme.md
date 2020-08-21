# Persisted Volumes Demo

## Container Storage

By default containers store their data on the file system like any other process.
Container file system is temporary and not persisted during container restarts
When container is recreated, so is the file system




Same can be demonstrated using Kubernetes

```
cd .\kubernetes\persistedvolumes\



# Persist data Docker
# Persist data Kubernetes


```
kubectl apply -f persistedvolume.yaml

```
