### Create a project
kubebuilder init --domain emqx.com --repo github.com/yao560909/emqx-operator --project-name emqx-operator

### Create api
kubebuilder create api --group apps --version v2beta1 --kind EMQX