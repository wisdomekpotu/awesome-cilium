# Awesome Cilium [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> 🐝 Cilium is an open-source networking, observability, and security platform for cloud-native environments. Powered by eBPF, Cilium provides high-performance, identity-aware networking for Kubernetes and beyond.

---

## 🔗 Core Projects

> Explore the main components that power the Cilium ecosystem:

- [**Cilium**](https://github.com/cilium/cilium) - The core project delivering scalable networking, security, and observability using eBPF.
- [**eBPF**](https://github.com/cilium/ebpf) - eBPF library for Go that powers many Cilium features.
- [**Hubble**](https://github.com/cilium/hubble) - Network observability and monitoring.
- [**Tetragon**](https://github.com/cilium/tetragon) - Real-time security observability and runtime enforcement.
- [**Cilium Proxy**](https://github.com/cilium/proxy) - Envoy fork optimized for use in Kubernetes.
- [**Cilium Mesh**](https://isovalent.com/blog/post/introducing-cilium-mesh/) - Service mesh built into Cilium using eBPF and XDP.
- [**Network Policy Editor**](https://editor.networkpolicy.io/) - Visual Kubernetes network policy designer.

---

## 🛠️ Tools & Utilities

> Enhance your workflow with these tools:

- [cilium-cli](https://github.com/cilium/cilium-cli) - Official CLI to install, manage, and troubleshoot Cilium.
- [kubectl-cilium](https://github.com/kakao/kubectl-cilium) - `kubectl` plugin to inspect SNAT usage in Cilium.
- [cilium-certgen](https://github.com/cilium/certgen) - Tool to generate mTLS certificates for Hubble Relay.
- [Netfetch](https://github.com/deggja/netfetch) - Scan Kubernetes clusters for network policy coverage.

---

## 📖 Articles & Blog Posts

### 🧰 Getting Started

- [A Beginner’s Guide to Cilium](https://www.itprc.com/cilium-beginners-guide/)
- [Introduction to eBPF and Cilium](https://www.everythingdevops.dev/blog/introduction-to-ebpf-and-cilium)
- [Cilium: Advanced Network Policies and Observability in Kubernetes](https://medium.com/@simardeep.oberoi/cilium-advanced-network-policies-and-observability-in-kubernetes-fbb4fdd747ba)

### 🔍 Observability & Hubble

- [How to use Cilium Hubble for Network Observability](https://www.techtarget.com/searchnetworking/tip/How-to-use-Cilium-Hubble-for-network-observability)
- [Supercharge Kubernetes Networking Observability using Hubble and Cilium](https://docs.rafay.co/blog/2025/03/03/supercharge-kubernetes-networking-observability-using-hubble-and-cilium/)

### 🌐 Multi-Cluster & ClusterMesh

- [Multi-Cluster with Cilium on Civo Cloud](https://www.everythingdevops.dev/blog/multi-cluster-with-cilium-on-civo-cloud)
- [Introduction to Multi-Cluster Deployment in Kubernetes](https://www.everythingdevops.dev/blog/introduction-to-multi-clusters)
- [Deploying MySQL InnoDB ClusterSet Across Kubernetes Clusters Using Cilium](https://blogs.oracle.com/mysql/post/deploying-mysql-innodb-clusterset-across-kubernetes-clusters-using-cilium)

### ☁️ Cloud Integrations

- [Deploying Cilium on Amazon EKS Hybrid Nodes](https://repost.aws/articles/ARpKAVyUXgSBW1h9GBhh2JKA/deploying-cilium-networking-on-amazon-eks-hybrid-nodes)
- [Using Cilium as a Standalone NAT46x64 Gateway](https://netops2devops.net/posts/cilium-nat64/)
- [High-Scale Kubernetes Networking with Azure CNI + Cilium](https://techcommunity.microsoft.com/blog/azurenetworkingblog/high-scale-kubernetes-networking-with-azure-cni-powered-by-cilium/4407234)
- [Cilium & Enhanced Networking with Intel 82599 VF in EKS](https://medium.com/@amitmavgupta/cilium-enhanced-networking-with-intel-82599-vi-bf7688b9615e)
- [Deploy a Hybrid EKS Cluster Using On-Prem Nodes with Cilium](https://albycrescini.medium.com/setting-up-a-hybrid-eks-cluster-using-on-premises-nodes-to-your-amazon-eks-kubernetes-cluster-030b4e963d53)

### 🔐 Security

- [Unlocking Cloud-Native Security with Cilium and eBPF](https://www.cncf.io/blog/2025/01/02/unlocking-cloud-native-security-with-cilium-and-ebpf/)
- [Hardening Palantir’s Kubernetes Infrastructure with Cilium](https://blog.palantir.com/hardening-palantirs-kubernetes-infrastructure-with-cilium-1c40d4c7ef0)
- [Best Practices for Network Policies in Azure Kubernetes Service](https://learn.microsoft.com/en-us/azure/aks/network-policy-best-practices)

---

### 🛜 Networking & Performance

- [Breaking the Chains of Kube-Proxy With Cilium](https://thenewstack.io/breaking-the-chains-of-kube-proxy-with-cilium/)
- [Dual Stack K3s With Cilium and BGP](https://mmacleod.ca/2025/04/dual-stack-k3s-with-cilium-and-bgp/)
- [Exposing Apps in Kubernetes with Gateway API + Cilium](https://blog.teknews.cloud/aks/security/network/2025/03/30/Exposing_apps_in_kubernetes-_From_services_to_Gateway_API.html)

---

## 🎓 Cilium Training & Certification

### Online Courses:

- [LFS146: Introduction to Cilium](https://training.linuxfoundation.org/training/introduction-to-cilium-lfs146/) - Free beginner course from The Linux Foundation.

### Certifications:

- [Cilium Certified Associate (CCA) Exam](https://training.linuxfoundation.org/certification/cilium-certified-associate-cca/) - Entry-level certification by the Linux Foundation.

---

## 🧪 Hands-On Labs

> Get practical experience with Cilium:

- [**Isovalent Labs**](https://isovalent.com/resource-library/labs/) – Official, guided labs to learn Cilium fundamentals, ClusterMesh, observability, security policies, and more.

---

## 📚 Books & Publications

### Books

- [**Ultimate Cilium and eBPF for Cloud Native Development**](https://www.amazon.com/Ultimate-Cilium-eBPF-Cloud-Native-Development-Observability-Environments/dp/B0DY88M12X) - by Gaurav Shekhar.
- [**Kubernetes Networking and Cilium**](https://isovalent.com/books/kubernetes-networking-and-cilium) - by Nicolas Vibert.
- [**Kubernetes Network Policies Done the Right Way**](https://isovalent.com/books/kubernetes-network-policies-done-the-right-way-by-isovalent/) - by Dean Lewis & Raymond de Jong.
- [**Cilium Network Policy Deep Dive**](https://isovalent.com/books/cilium-network-policy-deep-dive/) - by Joe Stringer & Nicholas Lane.
- _Cilium Up and Running_ (TBD release by O’Reilly)

### Research & White Papers

- [**Kubernetes Traffic Engineering for Network Engineers: Cilium Best Practices**](https://isovalent.com/white-paper/kubernetes-traffic-engineering-cilium/)
- [**Cilium and VDM – Formal Analysis of Policies**](https://arxiv.org/abs/2410.12009) - Academic perspective.
- [**Cilium and Cisco ACI**](https://www.cisco.com/c/en/us/solutions/collateral/data-center-virtualization/application-centric-infrastructure/cilium-and-aci-modular-design-wp.html) - White paper on integration with Cisco.

---

## 📨 Newsletters

- [**eCHO News**](https://www.linkedin.com/newsletters/echo-news-6937495018668482560/) - Biweekly updates on Cilium & eBPF.

---

## 🌐 Community & Discussions

- [**Slack**](https://slack.cilium.io/) - Join the conversation.
- [**X / Twitter**](https://twitter.com/ciliumproject) - Stay updated with the latest news.
- [**YouTube Channel**](https://www.youtube.com/channel/UCJFUxkVQTBJh3LD1wYBWvuQ) - Watch webinars, tutorials, and more.
- [**Weekly Community Meeting**](https://docs.cilium.io/en/latest/community/community/#community-meetings) - Every Wednesday @ 8:00 AM PT ([Meeting Notes](https://docs.google.com/document/d/1Y_4chDk4rznD6UgXPlPvn3Dc7l-ZutGajUv1eF0VDwQ/edit#))
- [**APAC Community Meeting**](https://docs.google.com/document/d/1egv4qLydr0geP-GjQexYKm4tz3_tHy-LCBjVQcXcT5M/edit#) - Third Wednesday monthly @ 4:30 UTC.
- [**LinkedIn**](https://www.linkedin.com/company/cilium/) - Follow for insights and updates.

---

## 🤝 Contributing

Want to help grow this list? Contributions are welcome!

1. Fork this repository.
2. Add your resource(s).
3. Open a pull request with details.

See [CONTRIBUTING.md](contributing.md) for more info.
