# **Kube调度器**

## **概要**
Kubernetes调度器是一个函数，policy-rich，topology-aware和workload-specific（三个形容词，翻译待考虑），显著影响可用性、性能和容量。该调度器需要考虑个人和集体的资源需求，服务质量需求，硬件、软件、策略约束，亲和力和非亲和力规范，