# Azure resource dashboard

This repo contains Azure and MS365 documentation and resources

## Infra as code wisdom:

As you mention a Windows environment, as well as moving to cloud, I think you can’t ignore PowerShell in general.

If your cloud environment is Azure, do a deep dive in Azure PowerShell in particular. Next, look at Azure DevOps to facilitate the CI CD pipelines.

If your cloud environment is AWS, or you think you will need to manage multiple cloud vendors, then HashiCorp’s Terraform is one of the more prevalent infrastructure-as-code frameworks.

I’m a reasonable proponent of Git (distributed version control system) with git-flow (how to approach branching, features and bug fixes) and GitOps (managing infrastructure through pull requests).


## Documentation
https://docs.microsoft.com/en-us/azure/architecture/
https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/



## Usefull Git Repositories  
- [MS patterns & practices](https://github.com/mspnp)
- [Azure](https://github.com/Azure)
- [Bicep](https://github.com/Azure/bicep)

## Infra as Code
Azure native
- [ARM templates](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/)
- [Bicep playground](https://bicepdemo.z22.web.core.windows.net/)

https://github.com/Azure/template-analyzer

https://github.com/azure/azops/wiki/introduction



Platform independant industry standard
- [Terraform](https://www.terraform.io/)

Higher level programming
- [Farmer](https://compositionalit.github.io/farmer/)
- [Pulumi](https://www.pulumi.com/)

Diagram to template
- [Cloudmaker](https://cloudmaker.ai/)

Blueprints
- https://docs.microsoft.com/en-us/azure/governance/blueprints/overview

## Kubernetes
https://github.com/Azure/aks-periscope  
https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks/secure-baseline-aks  
https://github.com/mspnp/aks-secure-baseline



## Learning Paths
- [Devops](https://docs.microsoft.com/en-us/learn/certifications/exams/az-400)


## Testing

- [Setup](https://docs.microsoft.com/en-us/azure/devtest-labs/devtest-lab-overview) lab in Azure (paid resources)
- [Setup](https://developer.microsoft.com/en-us/microsoft-365/profile) free MS 365 Azure AD tenant

## Roadmap
https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=


## Assesments
### MS 365 Compliance 


Compliance center - https://compliance.microsoft.com/

[compliance center] https://docs.microsoft.com/en-us/microsoft-365/compliance/compliance-manager-assessments?view=o365-worldwide  

[Assessment templates](https://docs.microsoft.com/en-us/microsoft-365/compliance/compliance-manager-templates?view=o365-worldwide)

[Microsoft Compliance Configuration Analyzer (MCCA)](https://docs.microsoft.com/en-us/microsoft-365/compliance/compliance-manager-mcca?view=o365-worldwide)

Input/Output: Excel / Powershell / MS 365 Compliance center dashboard

### Azure

**Architecture**

[Well architected framework - Azure Advisor](https://docs.microsoft.com/en-us/azure/architecture/framework/)

https://docs.microsoft.com/en-us/assessments/

https://docs.microsoft.com/en-us/assessments/?mode=pre-assessment&session=0f77b2ea-ef99-4ba7-8bff-9966ee995b5d


**Policies** 

https://docs.microsoft.com/en-us/azure/governance/policy/how-to/get-compliance-data
https://docs.microsoft.com/en-us/azure/governance/policy/assign-policy-bicep?tabs=azure-powershell

**Benchmarks**  
The Azure Security Benchmark (ASB) provides prescriptive best practices and recommendations to help improve the security of workloads, data, and services on Azure. 

Input/Output:
Azure policies (compliant/non-compliant)
Azure Security center regulatory compliance dashboard

https://techcommunity.microsoft.com/t5/azure-security-center/azure-security-benchmark-v2-is-now-available-with-expanded/ba-p/1689883
![](https://techcommunity.microsoft.com/t5/image/serverpage/image-id/220023iBCF810B31B1CD8A1/image-size/large?v=v2&px=999)
https://docs.microsoft.com/en-us/azure/security-center/security-center-compliance-dashboard

[Azure Security Benchmark (V2)](https://docs.microsoft.com/en-us/security/benchmark/azure/overview)

Output: Excel / Security Center compliance dashboard

### Governance
https://docs.microsoft.com/en-us/assessments/

## Security & Governance
[Microsoft (MS 365 & Azure) security best practices](https://docs.microsoft.com/en-us/security/compass/compass)

## AppSec

Waf & IaC code security
- https://www.signalsciences.com/

Dependency checker
- https://owasp.org/www-project-dependency-check/
- https://snyk.io/
- https://www.whitesourcesoftware.com/free-developer-tools/renovate

Code Analyses
- https://www.whitesourcesoftware.com/free-developer-tools/bolt
- https://devblogs.microsoft.com/premier-developer/azure-devops-pipelines-leveraging-owasp-zap-in-the-release-pipeline/

Dependabot


## General
Jupyter notebook
JupyterLab

## CI/CD concepts
- https://docs.gitlab.com/ee/ci/introduction/


Arm tenant deployments
- https://github.com/Azure/Enterprise-Scale/blob/main/docs/EnterpriseScale-Setup-azure.md


Quickstart ARM templates
- https://azure.microsoft.com/en-us/resources/templates/