# acs-gitops
Repository for install ACS as GitOps

## Bootstrap Openshift GitOps / ArgoCD

```
until oc apply -k bootstrap/base/; do sleep 2; done
```

## Install ACS through GitOps

```
oc apply -k acs-deploy/base/
```

## Video of the Demo

* [Demo](https://youtu.be/33XuvCPLZ58)

Enjoy!
