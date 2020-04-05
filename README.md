# helm-helloworld-go
- helm chart example w/helloworld go.
- For testing spinnaker blue/green deployment, using ReplicaSet instead of Deployment type.

## test command
- `helm install --dry-run --debug --generate-name .`

## install command
- `helm install --debug --generate-name .`
- `helm install --debug chart-helloworld-go .`

## check helm
- `helm ls`
- `helm serve`

## delete command
- `helm del chart-helloworld-g`
