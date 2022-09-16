# Kubernetes Interview Challenge
1. Start from a single file Python mini HTTP server.<br>The source code is located here: https://gist.github.com/eredo/1547873c189ed5ced7353d6217cfeb42
2. Run it locally.
3. Dockerize it.
4. Run it locally through Docker.
5. Deploy it to k8s with a regular k8s Deployment.
6. Expose to the outside world.
7. Modify the application code so it waits 30 seconds before starting to serve the webpage.
8. Add a k8s check using so that no traffic goes to the application until it is ready to serve.
9. Make the message that the application is serving configurable through a config map.
