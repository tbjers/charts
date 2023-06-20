# Helm charts

[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/tbjers/charts/main.svg)](https://results.pre-commit.ci/latest/github/tbjers/charts/main)

## Add repository

``` sh
helm repo add tbjers https://charts.bjers.org
```

## Install chart

``` sh
helm install my-vanity tbjers/go-vanity
```

## Install chart (Helm 2)

``` sh
helm install --name my-vanity tbjers/go-vanity
```
