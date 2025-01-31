# Labs for Training and Serving TensorFlow Models with Kubernetes and Kubeflow on Azure Container Service (AKS)

<!-- ## [Learning Objectives](./learningObjectives.md)
## [Presentation Content](./presentationContent.md)
## [Room Organization](./roomOrganization.md) -->

## Prerequisites

1. Have a valid Microsoft Azure subscription allowing the creation of an AKS cluster
1. Docker client installed: [Installing Docker](https://www.docker.com/community-edition)
1. Azure-cli  (2.0) installed: [Installing the Azure CLI 2.0 | Microsoft Docs](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli?view=azure-cli-latest)
1. Git cli installed: [Installing Git CLI](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
1. Kubectl installed: [Installing Kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)
1. Helm installed: [Installing Helm CLI](https://docs.helm.sh/using_helm/#from-the-binary-releases) (**Note**: On Windows you can extract the `tar` file using a tool like 7Zip.)
1. ksonnet installed: [Installing ksonnet CLI](https://ksonnet.io/#get-started)

Clone this repository somewhere so you can easily access the different source files:
```console
git clone https://github.com/Azure/kubeflow-labs
```

## Content Summary

| | Module | Description |
| --- | --- | --- |
|0| **[Introduction](0-intro)** | Introduction to this workshop. Motivations and goals.|
|1| **[Kubeflow](4-kubeflow)** | Introduction to Kubeflow and how to deploy it in your cluster.|
|2| **[JupyterHub](5-jupyterhub)** | Learn how to run JupyterHub to create and manage Jupyter notebooks using Kubeflow |
|3| **[TFJob](6-tfjob)** | Introduction to `TFJob` and how to use it to deploy a simple TensorFlow training.|
|7| **[Distributed Tensorflow](7-distributed-tensorflow)** | Learn how to deploy and monitor distributed TensorFlow trainings with `TFJob`|
|8| **[Hyperparameters Sweep with Helm](8-hyperparam-sweep)** | Using Helm to deploy a large number of trainings testing different hypothesis, and TensorBoard to monitor and compare the results |
|9| **[Serving](9-serving)** | Using TensorFlow Serving to serve predictions |
|10| **[Going Further](10-going-further)** | Links and resources to go further: Autoscaling, Distributed Storage etc. |


# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

# Legal Notices

Microsoft and any contributors grant you a license to the Microsoft documentation and other content
in this repository under the [Creative Commons Attribution 4.0 International Public License](https://creativecommons.org/licenses/by/4.0/legalcode),
see the [LICENSE](LICENSE) file, and grant you a license to any code in the repository under the [MIT License](https://opensource.org/licenses/MIT), see the
[LICENSE-CODE](LICENSE-CODE) file.

Microsoft, Windows, Microsoft Azure and/or other Microsoft products and services referenced in the documentation
may be either trademarks or registered trademarks of Microsoft in the United States and/or other countries.
The licenses for this project do not grant you rights to use any Microsoft names, logos, or trademarks.
Microsoft's general trademark guidelines can be found at http://go.microsoft.com/fwlink/?LinkID=254653.

Privacy information can be found at https://privacy.microsoft.com/en-us/

Microsoft and any contributors reserve all others rights, whether under their respective copyrights, patents,
or trademarks, whether by implication, estoppel or otherwise.
