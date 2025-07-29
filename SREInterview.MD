# Interview Guide for SRE Engineers

## Interview Overview
This is a live debugging interview where you'll troubleshoot a cloud-native infrastructure issue. You'll be given access to a Kubernetes cluster with a broken nginx application that should be accessible via Twingate VPN and Envoy Gateway.

## What You Need to Know (Prerequisites)

### 1. Core Technologies
- **Kubernetes**: Pods, Services, Deployments, NetworkPolicies, Gateway API
- **Helm**: Chart deployment and value overrides
- **Envoy Gateway**: Gateway API implementation and HTTP routing
- **Network Policies**: Creating and troubleshooting Kubernetes NetworkPolicies to control traffic flow
- **Network Troubleshooting**: DNS resolution, port connectivity, service discovery
- **Twingate/ZTNA**[Optional]: VPN connectivity concepts and connector configuration

### 2. Required Tools & Commands
- Twingate connector pre install https://www.twingate.com/download 
- `kubectl` with cluster access
- `helm` for deployments
- `curl` or `wget` for HTTP testing
- Network debugging tools (`nslookup`, `telnet`, `nc`)
- Any other tool that you use to manage Kubernetes.
- email to allow vpn

## Additional Resources
- [Kubernetes Gateway API Documentation](https://gateway-api.sigs.k8s.io/)
- [Envoy Gateway Documentation](https://gateway.envoyproxy.io/)
- [Helm Documentation](https://helm.sh/docs/)
- [Kubernetes NetworkPolicies](https://kubernetes.io/docs/concepts/services-networking/network-policies/)
- [Twingate Documentation](https://docs.twingate.com/)
