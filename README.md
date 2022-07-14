# Learning Kubernetes on VMware Cloud on AWS

Welcome to to a set of labs purposefully built for VMware Cloud on AWS customers. These labs are meant to help teach the concepts around containers, Kubernetes, and Tanzu Kubernetes Grid in a VMware Cloud on AWS environment.

## Lectures

Each of the labs contained in this repository are designed to augment training videos found on the [VMware Cloud TechZone site](https://vmc.techzone.vmware.com/kubernetes-vmware-cloud-course). It is highly recommended to go through the training lectures before taking any of the labs found in this repository.



## Labs

| Lab | Name | Description |
|-----|-----|-----|
| 1 |[Run Your First Container](Chapter1/Run%20Your%20First%20Container/Instructions.md)| Install Docker on your Workstation and practice starting and stopping containers. |
| 2 |[Build Your First Image](/Chapter1/Build%20Your%20First%20Image/Instructions.md)| Build a new image from a Dockerfile and run the new container from that image. |
| 3 |[Activate the TKG Service](/Chapter3/Activate%20the%20TKG%20Service/Instructions.md)| Activate the Tanzu Kubernetes Grid Service |
| 4 |[Create a vSphere Namespace](/Chapter3/Create%20a%20vSphere%20Namespace/Instructions.md)| Create a vSphere Namespace |
| 5 |[Create Firewall Rules](/Chapter3/Create%20Firewall%20Rules/Instructions.md)| Create SDDC Firewall Rules |
| 6 |[Install CLI Tools](/Chapter3/Install%20CLI%20Tools/Instructions.md)| Install CLI Tools |
| 7 |[Authenticate to TKG](/Chapter3/Authenticate%20to%20TKG/Instructions.md)| Authenticate to the TKG Service |
| 8 |[Create a TKC](/Chapter3/Create%20a%20TKC/Instructions.md)| Create a Tanzu Kubernete Cluster |
| 9 |[Interacting with Pods](/Chapter4/Interacting%20with%20Pods/Instructions.md)| Interacting with Pods from the command line |
| 10 |[Interacting with Deployments](/Chapter4/Interacting%20with%20Deployments/Instructions.md)| Interacting with Deployments from the command line |
| 11 |[Working with Services](/Chapter5/Working%20with%20Services/Instructions.md)| Working with Kubernetes Services |
| 12 |[Load Balancers](/Chapter5/Load%20Balancers/Instructions.md)| Creating Load Balancers |
| 13 |[Namespaces and DNS](/Chapter5/namespaces/Instructions.md)| Working with Namespaces |

## Using Lab Example Files

As you are working thorugh the labs, you should know that example files are located within the lab you're taking. This may include, Dockerfiles, html files, help files, and Kuberntes YAML files. You are free to download these however you would like but most commonly, you'd use the git cli to pull down these labs from the public git repository.

```bash
git clone https://github.com/vmware-tanzu-labs/learn-kubernetes-on-vmware-cloud.git
```

Once you've pulled down this repository to your local workstation, you can change your working directory to the lab you're taking.

> Note: If you're taking labs over a long period of time, be sure to refresh your local git repository to retrieve any new labs that have been published since you originally pulled from the remote repository.
