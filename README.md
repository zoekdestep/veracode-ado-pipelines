# Veracode for Azure DevOps Pipelines

In [this Veracode blogpost](https://community.veracode.com/s/blog/user-story-how-we-set-up-veracode-in-a-large-azure-project-MCT4HNONEE55CIFA6O3ULXNUW2BI), I describe how we implemented Veracode and Azure DevOps in a large Azure project. To get started quickly with your own Veracode pipelines in Azure DevOps, you can find yaml pipelines of our setup in this repo.

You can find the following pipelines in this repo:

- *pipelines/veracode-pipeline-scan* -- To scan while developing new features.
- *pipelines/veracode-sandbox-myteam* -- To scan team code per team in an isolated environment.
- *pipelines/veracode-policy-scan* -- To scan while production code is being introduced into the main branch.
- *pipelines/template/veracode-sandbox* -- Templated pipeline to enable multiple teams to quickly build their own sandbox scan.
- *pipelines/template/azure-key-vault-secrets* -- Template to download Azure Key Vault secrets into other pipelines.

Feel free to reach out when you have any questions!