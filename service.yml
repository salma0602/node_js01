apiVersion: v1
kind: Service
metadata:
  name: node-js-app
spec:
  type: LoadBalancer
  selector:
    app: node-js-app
  ports:
    - protocol: TCP
      port: 3000
      targetPort: 3000
