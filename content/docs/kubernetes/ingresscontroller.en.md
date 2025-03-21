---
title: "Kubernetes Ingress Controller"
linkTitle: "Ingress"
summary: "Kubernetes Ingress Controller"
---

The following table provides an overview on popular Kubernetes ingress controllers.
A full list of Ingress Controllers can be found at https://kubernetes.io/docs/concepts/services-networking/ingress-controllers/.

| Controller      | Pricing                 | Key Use Case                                                   | Differentiators                                     |
|-----------------|-------------------------|----------------------------------------------------------------|-----------------------------------------------------|
| NGINX Ingress   | FOSS (Apache 2)         | Kubernetes maintained ingress                                  | Lua Scrip extensibility                             |
| Traefik         | FOSS (MIT) or paid      | dynamic environments                                           | auto-discovery, real-time updates                   |
| HAProxy Ingress | FOSS (Apache 2)         | high-performance evironments with extensive traffic management | L7 routing, robust observability                    |
| Envoy           | FOSS (Apache 2) or paid | cloud-native environments with complex traffic scenarios       | adanced L7, distributed tracing, custom filters     |
| Istio Ingress   | FOSS (Apache 2)         | Istio service mesh environments                                | service mesh integration, mTLS, intelligent routing |
| Contour         | FOSS (Apache 2)         | modern protocol support with high performance                  | http/2 and gRPC support                             |
