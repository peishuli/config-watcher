# config-watcher
A lightweight kubernetes controller that monitors configmaps and/or secrets specified in the CR (kind = ConfigWatch). Whenever a listed configmap or secret change is detected, the reconcile process will automatically restart all pods that depend on the configmap or secret.
