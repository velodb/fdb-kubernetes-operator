# Samples

This folder contains some samples on how to use the FoundationDB operator.
All YAML files directly in this folder except for `pod_disruption_budget.yaml` are automatically generated from the [config/tests](../tests) folder.
If you want to change the base files, do the changes in the `config/tests` folder and then run `make samples`.
You can find some additional examples under `config/tests`.

## VeloDB installation profiles

For Operator v2.35.0 with VeloDB images, namespace-scoped Monitor RBAC and
explicit single/double resource profiles, see [the installation guide](velodb/README.md).
These examples are maintained separately from the generated samples above.
