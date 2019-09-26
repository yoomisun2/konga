### Helm
download : https://github.com/pantsel/konga/tree/master/charts/konga
```
helm install -f ./values.yaml ../konga --namespace kong --wait
```

### Manual
```
kubectl -n kong apply -f konga.yaml
```
