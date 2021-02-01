# Rapid Multi-hybrid Cloud Management of Kubernetes and Cloud-Native Facilities

Relentless global competition forces every organization to reinvent, improve, and deliver their capabilities better than their competitors every day. Applications and initiatives defined by the business, implemented by developers, and delivered by operators requires combining and coordinating each of their focused efforts efficiently to run and manage the business. Many significant challenges are encountered because the convergence of efforts also represents the potentially conflicting responsibilities of rapid innovation for developers, performance and stability by operators, and fiscal and secure governance by the business.

The global leaders in web-scale business have established and proven the modern manner to produce and scale their capabilities is cloud-native architectures and facilities. Most have settled on micro-service architectures, built and delivered as containers, running on Kubernetes with supporting facilities and operations. Because many of these technologies are open source and de-facto standards, the barriers to adoption are low. However, to achieve these goals, the organization must resolve the contention between teams, meet the challenges of gaining cloud-native skill sets and experience, while securing and managing the entire enterprise.

Nutanix Karbon Platform Services (KPS), a Platform as a Service (PaaS) offering which creates Kubernetes clusters anywhere, provides supporting cloud-native facilities to accelerate developer efforts, and manages them on multiple public and private clouds. KPS allows all of the organization's teams to align their efforts, vendors, and management from a single web console.

The remainder of this blog will serve as a tutorial showing you how to start with KPS by setting up governance, operations, and management!

---

## Karbon Platform Services: Log-in

At the top of the [Karbon Platform Services](https://www.nutanix.com/products/karbon/platform-services) product page, there is a log-in button and a free trial sign-up via Test Drive buttons. KPS is a PaaS that can be accessed directly via https://karbon.nutanix.com/ or you can log-in to your Nutanix account at https://my.nutanix.com: under the Cloud Services section, choose Karbon Platform Services.

Because KPS can create new and manage existing K8s clusters from different providers, it is important to establish basic governance first with roles for your teams and access to your infrastructure and Kubernetes providers.

Here are some KPS resources you should keep handy:

- [Articles](https://www.nutanix.dev/?s=kps) and [Labs](https://www.nutanix.dev/labs/#lab_kps)@Nutanix.dev Developer Portal with application, IoT, and database examples.
  - I recommend reviewing [From there to here, from here to there, Containers are everywhere!](https://www.nutanix.dev/2020/12/16/from-there-to-here-from-here-to-there-containers-are-everywhere/) and [Introducing Karbon Platform Services](https://www.nutanix.dev/2020/09/09/introducing-karbon-platform-services/) for KPS overviews directly from the Nutanix Product and Engineering teams.
- [Documentation](https://portal.nutanix.com/page/documents/list?type=software&filterKey=software&filterVal=Karbon%20Platform%20Services)@Nutanix Support Portal https://portal.nutanix.com/page/documents/details?targetId=Karbon-Platform-Services-Admin-Guide:ks-ks-onboarding-admin-c.html
- https://github.com/nutanix/karbon-platform-services Public Git Repository

## Set-up

## Service Domains
- Terraform
- Direct provisioning of:
  - https://github.com/nutanixdev/karbon-platform-services/tree/master/how_to/service_domain_deployment/baremetal
  - https://github.com/nutanixdev/karbon-platform-services/tree/master/how_to/service_domain_deployment/aws
  - Hands on Workshop: [KPS Service Domain deployment on AHV](https://nutanix.handsonworkshops.com/workshops/66418164-5f85-4c74-9803-72bac2d0c196/view/)
