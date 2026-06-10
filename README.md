# Ingress
Kubernetes Ingress.

### Issues or Failures at four layers of Ingress

- DNS/Routing
- the Ingress Controller
- the Kubernetes Service
- the underlying Application Pods

#### The issues i faced while setting up an ingress controller with resource and accessing different services under the ingress

- I could not be able to access the service like app1.srikanth-suthari.me
- All the required resources got created but there may an issue with the Role access with the OIDC provider between the loadbalancer and the domain name
- Created different 2 different folders and  manifests within them for 2 different Applications
  - as app1 and app2