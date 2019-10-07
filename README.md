# Cloud platform gitops spike
This is the spike to us concourse as a gitops solution

Instructions on how to install and setup a concourse pipeline can be found in [cloud platform concourse repo](https://github.com/ministryofjustice/cloud-platform-concourse)

`gitops-apply, gitops-template.yaml`: Add this to [environments repository](https://github.com/ministryofjustice/cloud-platform-environments) to iterate the namespaces and to setup individual pipeline for user repo .

`gitops-deploy-template`: This is the sample template which should be placed in the user repo. This should have the command to deploy the user code into the cloud platform cluster.
