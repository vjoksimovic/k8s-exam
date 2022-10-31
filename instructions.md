Description

In this final task, we’ll migrate a project from docker-compose to Kubernetes. With provided docker-compose.yaml you have to create all necessary specifications for Kubernetes deployment.

Requirements

1. Every single application in this project has to have at least one Service.

2. Elasticsearch is a single clustered application.

3. Elasticsearch should be deployed as a StatefulSet, Persistent Volumes would be a plus.

4. All communications have to be implemented through Services.

5. Kibana and web-server have to be accessible from outside of the cluster.

6. All shared configs should be managed from one place.

7. In Kubernetes specifications you should use as many different kinds of Kubernetes objects as possible.

Notes:

On local kubernetes installations you might need to extend available memory, due to Elasticsearch requirements.
This docker-compose.yaml require some indentation fixes due to GridU UI specifics.