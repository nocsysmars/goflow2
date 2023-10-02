# Flow-pipeline Helm Charts

- An example to install flow-pipeline with goflow2 on k8s.

## Usage:

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

```console
helm install {release} -n {namespace} .
```

_See [helm install](https://helm.sh/docs/helm/helm_install/) for command documentation._

---

## Configuration

| Parameter | Description | Default |
|:----------|:------------|:--------|
| `grafana.adminUser`     | default username for grafana | admin   |
| `grafana.adminPassword` | default password for grafana | grafana |
