# <table id="wrapper">
  <tr>
    <td><img src="./.bluemix/istio-logo.png" alt="" /></td> Canary testing in Kubernetes using Istio
  </tr> Canary testing in Kubernetes using Istio
</table>

# ![Icon](./.bluemix/istio-logo.png) Canary testing in Kubernetes using Istio


### Develop and canary test your Kubernetes application using Istio
The sample application uses Docker with Node.js and includes a DevOps toolchain that is preconfigured for canary testing, continuous delivery with Vulnerability Advisor, source control, issue tracking, and online editing, and deployment to the IBM Cloud Kubernetes Service.

Application code is stored in source control, along with its Dockerfile and its Kubernetes deployment script.
The target cluster is configured during toolchain setup (using an IBM Cloud API key and cluster name). You can later change these by altering the Delivery Pipeline configuration.
Any code change to the Git repo will automatically be built, validated and deployed into the Kubernetes cluster.

![Icon](./.bluemix/toolchain.png)



### To get started, click this button:
[![Create Toolchain](https://console.bluemix.net/devops/graphics/create_toolchain_button.png)](https://console.bluemix.net/devops/setup/deploy/?repository=https%3A//github.com/open-toolchain/canary-testing-istio-toolchain)

---
### Learn more 

* Blog [Continuously deliver your app to Kubernetes with Bluemix](https://www.ibm.com/blogs/bluemix/2017/07/continuously-deliver-your-app-to-kubernetes-with-bluemix/)
* Step by step [tutorial](https://www.ibm.com/devops/method/tutorials/tc_secure_kube)
* [Getting started with Bluemix clusters](https://console.bluemix.net/docs/containers/container_index.html?pos=2)
* [Getting started with toolchains](https://bluemix.net/devops/getting-started)
* [Documentation](https://console.bluemix.net/docs/services/ContinuousDelivery/index.html?pos=2)
