## This is a Openshift Blue - Green DEPLOYMENT demonstration with a simple PHP Application

![](bgdeploy.PNG)



#### Blue-Green Deployment
#### Blue-green deployments involve running two versions of an application at the same time and moving production traffic from the old version to the new version.

#### When to Use a Blue-Green Deployment
#### Use a blue-green deployment when you want to test a new version of your application in a production environment before moving traffic to it. Blue-green deployments make switching between two different versions of your application easy. However, since many applications depend on persistent data, you will need to have an application that supports N-1 compatibility if you share a database, or implement a live data migration between your database, store, or disk if you choose to create two copies of your data layer.

