# clo835-assignment3
GitHub Repo for Assignment 3.

Implementation Flow.

1. Meet all prequites and deploy eks cluster using eks_config.yaml
2. Verify the cluster is running and two nodes are ready
3. Create storageClass using standard-storageclass.yaml
4. Create PersistentVolumeClaim using pvc-mongo-pvc.yaml
5. Deploy mongodb-backend using backend-deployment.yaml and create CluserIP Servcice using backend-svc.yaml
6. Deploy guestbook-frontend using frontend-deployment.yaml and create LoadBalacner Service using frontend-svc.yaml
7. Check the application using elb dns.
8. Deploy hostpath-pv.yaml to create persistentVolume.
9. Deploy hostpath-pvc.yaml to create persistentVolumeClaim.
10. Deploy hostpath.sc.yaml to create storageclass
11. Redploy backend application using hostpath-backend.yaml
