<h1 align='center'>TOC of All DigitalOcean Modules</h1><p align='center' style='font-size: 1.2rem;''> This repo is a useful way to discover all Digitalocean modules <a href='https://clouddrove.com'>CloudDrove</a> developed and maintained repositories. It is mainly designed for clients of CloudDrove. </p>	<p align='center'>	<a href='https://facebook.com/sharer/sharer.php?u=https://github.com/terraform-do-modules/toc'>	  <img title='Share on Facebook' src='https://user-images.githubusercontent.com/50652676/62817743-4f64cb80-bb59-11e9-90c7-b057252ded50.png' />	</a>	<a href='https://www.linkedin.com/shareArticle?mini=true&title=TOC+of+All+CloudDrove+Packages+and+Tools&url=https://github.com/terraform-do-modules/toc'>	  <img title='Share on LinkedIn' src='https://user-images.githubusercontent.com/50652676/62817742-4e339e80-bb59-11e9-87b9-a1f68cae1049.png' />	</a>	<a href='https://twitter.com/intent/tweet/?text=TOC+of+All+CloudDrove+Packages+and+Tools&url=https://github.com/terraform-do-modules/toc'>	  <img title='Share on Twitter' src='https://user-images.githubusercontent.com/50652676/62817740-4c69db00-bb59-11e9-8a79-3580fbbf6d5c.png' />	</a>	</p>	<hr>

## Terraform DigitalOcean modules

CloudDrove offers the below terraform DigitalOcean modules:

Sr No. | Module name | Description | Latest version | Star | Fork | Issues
--- | --- | --- | --- |--- |--- |---
| 1. | **[terraform-digitalocean-vpc](https://github.com/terraform-do-modules/terraform-digitalocean-vpc)** | Terraform module to create VPC resources. VPCs are virtual networks containing resources that can communicate with each other in full isolation, using private IP addresses | [1.0.0](https://github.com/terraform-do-modules/terraform-digitalocean-vpc/releases) | 10 | 1 |  
| 2. | **[terraform-digitalocean-firewall](https://github.com/terraform-do-modules/terraform-digitalocean-firewall)** | Provides a DigitalOcean Cloud Firewall resource. DigitalOcean Cloud Firewalls are a network-based, stateful firewall service for Droplets provided at no additional cost. Cloud firewalls block all traffic that isn’t expressly permitted by a rule. | [1.0.0](https://github.com/terraform-do-modules/terraform-digitalocean-firewall/releases) | 8 | |  
| 3. | **[terraform-digitalocean-labels](https://github.com/terraform-do-modules/terraform-digitalocean-labels)** |   This terraform module is designed to generate consistent label names and tags for resources. You can use terraform-labels to implement a strict naming convention. | [1.0.0](https://github.com/terraform-do-modules/terraform-digitalocean-labels/releases) | 9 | |  
| 4. | **[terraform-digitalocean-droplet](https://github.com/terraform-do-modules/terraform-digitalocean-droplet)** | Provides a DigitalOcean Droplet resource. This can be used to create, modify, and delete Droplets. | [1.0.0](https://github.com/terraform-do-modules/terraform-digitalocean-droplet/releases) | 8 | |  
| 5. | **[terraform-digitalocean-ssh-key](https://github.com/terraform-do-modules/terraform-digitalocean-ssh-key)** | Terraform module to create  ssh-key. Provides a DigitalOcean SSH key resource to allow you to manage SSH keys for Droplet access. | | 7 | |  
| 6. | **[terraform-digitalocean-certificate](https://github.com/terraform-do-modules/terraform-digitalocean-certificate)** | Provides a DigitalOcean Certificate resource that allows you to manage certificates. | [1.0.0](https://github.com/terraform-do-modules/terraform-digitalocean-certificate/releases) | 8 | |  
| 7. | **[terraform-digitalocean-spaces](https://github.com/terraform-do-modules/terraform-digitalocean-spaces)** | Terraform module to create spaces resource on Digital Ocean. DigitalOcean Spaces provide S3-compatible object storage which lets you store and serve large amounts of data. | [1.0.0](https://github.com/terraform-do-modules/terraform-digitalocean-spaces/releases) | 8 | |  
| 8. | **[terraform-digitalocean-kubernetes](https://github.com/terraform-do-modules/terraform-digitalocean-kubernetes)** | Terraform module for creating a Kubernetes cluster on Digital Ocean.  DigitalOcean Kubernetes (DOKS) is a managed Kubernetes service that lets you deploy Kubernetes clusters without the complexities of handling the control plane and containerized infrastructure. | [1.0.0](https://github.com/terraform-do-modules/terraform-digitalocean-kubernetes/releases) | 9 | 1 |  
| 9. | **[terraform-digitalocean-database](https://github.com/terraform-do-modules/terraform-digitalocean-database)** | Terraform module to create DATABASE resources. DigitalOcean's Managed Databases are a fully managed, high performance database cluster service. Using managed databases is a powerful alternative to installing, configuring, maintaining, and securing databases by hand. | [1.0.1](https://github.com/terraform-do-modules/terraform-digitalocean-database/releases) | 9 | 1 |  
| 10. | **[terraform-digitalocean-monitoring](https://github.com/terraform-do-modules/terraform-digitalocean-monitoring)** | Terraform module to create monitor resource. DigitalOcean Monitoring is a free, opt-in service that gathers metrics about Droplet-level resource utilization. It provides additional Droplet graphs and supports configurable metrics alert policies with integrated email Slack notifications to help you track the operational health of your infrastructure | [1.0.0](https://github.com/terraform-do-modules/terraform-digitalocean-monitoring/releases) | 8 | |  
| 11. | **[terraform-digitalocean-container-registry](https://github.com/terraform-do-modules/terraform-digitalocean-container-registry)** | Terraform module to create container registry. The DigitalOcean Container Registry (DOCR) is a private Docker image registry with additional tooling support that enables integration with your Docker environment and DigitalOcean Kubernetes clusters. | [1.0.1](https://github.com/terraform-do-modules/terraform-digitalocean-container-registry/releases) | 7 | 1 |  
| 12. | **[terraform-digitalocean-load-balancer](https://github.com/terraform-do-modules/terraform-digitalocean-load-balancer)** | Terraform module to create Load-balancer resource .  DigitalOcean Load Balancers ensure that the requests your application receives are only distributed to Droplets that have passed health checks. | [1.0.0](https://github.com/terraform-do-modules/terraform-digitalocean-load-balancer/releases) | 8 | |  
| 13. | **[terraform-digitalocean-domain](https://github.com/terraform-do-modules/terraform-digitalocean-domain)** | Terraform module to create domain(DNS) resource on Digital Ocean. DigitalOcean is not a domain name registrar, but you can manage your DNS records from the DigitalOcean Control Panel. This can make record management easier because DigitalOcean DNS integrates with Droplets and Load Balancers. | [1.0.0](https://github.com/terraform-do-modules/terraform-digitalocean-domain/releases) | 8 | |  
| 14. | **[terraform-digitalocean-cdn](https://github.com/terraform-do-modules/terraform-digitalocean-cdn)** |  Terraform module to create CDN resources. DigitalOcean also includes a CDN with DigitalOcean Spaces, our object storage solution, and App Platform, our Platform as a Service solution. Sign up for a DigitalOcean account today to get started. | [1.0.0](https://github.com/terraform-do-modules/terraform-digitalocean-cdn/releases) | 6 | |  
| 15. | **[terraform-digitalocean-app](https://github.com/terraform-do-modules/terraform-digitalocean-app)** | Terraform module to create app resources. App Platform is a Platform-as-a-Service (PaaS) offering that allows developers to publish code directly to DigitalOcean servers without worrying about the underlying infrastructure. | [1.0.1](https://github.com/terraform-do-modules/terraform-digitalocean-app/releases) | 8 | 1 |  
| 16. | **[terraform-digitalocean-components](https://github.com/terraform-do-modules/terraform-digitalocean-components)** | Terraform module to create digital ocean component.  | | 11 | |  

## Feedback

If you come accross a bug or have any feedback, please log it in our [issue tracker](https://github.com/terraform-do-modules/toc/issues), or feel free to drop us an email at [hello@clouddrove.com](mailto:hello@clouddrove.com).

If you have found it worth your time, go ahead and give us a * on [our GitHub](https://github.com/terraform-do-modules/toc)!

## About us

At [CloudDrove](https://clouddrove.com), we offer expert guidance, implementation support and services to help organisations accelerate their journey to the cloud. Our services include docker and container orchestration, cloud migration and adoption, infrastructure automation, application modernisation and remediation, and performance engineering.

<p align='center'>We are <b> The Cloud Experts!</b></p><hr /><p align='center'>We ❤️  <a href='https://github.com/terraform-do-modules'>Open Source</a> and you can check out <a href='https://github.com/terraform-do-modulese'>our other modules</a> to get help with your new Cloud ideas.</p>

