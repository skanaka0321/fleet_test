kind: GitRepo
apiVersion: fleet.cattle.io/v1alpha1
metadata:
  name: helm-verify-test
spec:
  repo: https://github.com/rancher/fleet-examples
  branch: test-helm-verify
  paths:
  - helm-verify
