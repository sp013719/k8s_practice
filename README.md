# k8s_practice

## Instructions to Create Kubernetes Services and Deployments

### Step 1: Apply PostgreSQL Deployment and Service

1. Apply the PostgreSQL deployment and service:

    ```sh
    kubectl apply -f postgres-deployment.yaml
    ```

### Step 2: Apply Redis Deployment and Service

1. Apply the Redis deployment and service:

    ```sh
    kubectl apply -f redis-deployment.yaml
    ```

### Step 3: Apply the Application Deployment and Service

1. Apply the application deployment and service:

    ```sh
    kubectl apply -f deployment.yaml
    ```

### Step 4: Verify the Deployments and Services

1. Check the status of the deployments:

    ```sh
    kubectl get deployments
    ```

2. Check the status of the services:

    ```sh
    kubectl get services
    ```

### Instructions to Delete Kubernetes Services and Deployments

### Step 1: Delete the Application Deployment and Service

1. Delete the application deployment and service:

    ```sh
    kubectl delete -f deployment.yaml
    ```

### Step 2: Delete Redis Deployment and Service

1. Delete the Redis deployment and service:

    ```sh
    kubectl delete -f redis-deployment.yaml
    ```

### Step 3: Delete PostgreSQL Deployment and Service

1. Delete the PostgreSQL deployment and service:

    ```sh
    kubectl delete -f postgres-deployment.yaml
    ```

This will set up and tear down the PostgreSQL and Redis databases and update your application to connect to them.