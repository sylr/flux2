## flux reconcile alert

Reconcile an Alert

### Synopsis

The reconcile alert command triggers a reconciliation of an Alert resource and waits for it to finish.

```
flux reconcile alert [name] [flags]
```

### Examples

```
  # Trigger a reconciliation for an existing alert
  flux reconcile alert main

```

### Options

```
  -h, --help   help for alert
```

### Options inherited from parent commands

```
      --kubeconfig string   path to the kubeconfig file (default "~/.kube/config")
  -n, --namespace string    the namespace scope for this operation (default "flux-system")
      --timeout duration    timeout for this operation (default 5m0s)
      --verbose             print generated objects
```

### SEE ALSO

* [flux reconcile](flux_reconcile.md)	 - Reconcile sources and resources

