# IoT Edge on Kubernetes with KubeVirt

This repo provides a guidance and an accelerator to deploy Azure IoT Edge runtime in a VM, on Kubernetes(K8s) cluster.

There are two primary reasons why we may want to run IoT Edge on K8s cluster, they are horizontal scale and resilience. Horizontal scale allow running compute on multiple physical or virtualized machines and thus allow a degree of parallelism on the edge, resilience on the other hand allow services to recover from the underlying hardware failure without a manual intervention. This solution covers the resilience aspect of IoT Edge runtime and its modules, it does not specifically address horizontal scale aspect of it which may need changes in the runtime design. Please note this repo provides a solution for running IoT Edge version 1.2 onwards on K8s, if you are running IoT Edge v1.1 LTS, you can follow the instructions [here](https://docs.microsoft.com/en-us/azure/iot-edge/how-to-install-iot-edge-kubernetes?view=iotedge-2018-06) but be aware that v1.1 will only be [supported until Dec 2022](https://azure.microsoft.com/nb-no/updates/iot-edge1-1-0/).

## Solution

This is now moved to Azure-Samples, you can find the link for it below:
https://github.com/Azure-Samples/IoT-Edge-K8s-KubeVirt-Deployment
