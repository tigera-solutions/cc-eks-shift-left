# Module 10 - Clean up

1. Delete the example application stacks and namespaces.

   ```bash
   kubectl delete -f manifests/20-dev-app.yaml
   kubectl delete -f manifests/00-namespaces.yaml
   ```

2. Delete the EKS cluster.

   ```bash
   eksctl delete cluster $CLUSTERNAME
   ```

3. Delete environment variables backup file.

   ```bash
   rm envLabVars.env
   ```

---

[:arrow_left: Module 9 - Traffic visualization inside your Kubernetes Cluster](module-9-visibility.md) <br>

[:leftwards_arrow_with_hook: Back to Main](../README.md)
