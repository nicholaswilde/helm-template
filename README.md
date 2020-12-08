# Helm Template
A template repository for my [Helm charts repository](https://github.com/nicholaswilde/helm-charts).

## Requirements
- [helm](https://helm.sh/docs/intro/install/)

## Usage
Copy the template dir of this repo to the charts dir of the helm-charts repository.

Rename the template dir to the name of your chart.

Edit the `Chart.yaml` with the details of the chart.

Edit the `values.yaml` with the details of the chart setup.

Run `helm dependencies update` in the chart directory to download common dependencies.

Run `helm install release . --dry-run --debug` in the chart directory to test the deployment.
