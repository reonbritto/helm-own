helm create app-deploy


helm template test -f .\app-deploy\values-dev.yaml .\app-deploy\ --debug