


#### AWS
```
Deploy Spring Boot App to AWS Cloud using Elastic Beanstalk

On AWS Cloud spring boot app uses MySQL(MySQL server which is deployed in AWS Cloud)

AWS provides 90+ services, you should use based on your requirement.
```

#### SERVICES TO KNOW BY JAVA DEVELOPER
```
AMAZON EC2
AWS ELASTIC BEAN STALK SERVICE
RDS
S3
ROUTE 53
```

##### EC2
```
Once if we have EC2 Service we can install java, mysql, tomcat and any other software
```

##### Elastic Bean Stalk
```
You can simply upload your code and Elastic Beanstalk automatically handles the deployment, from capacity
provisioning, load balancing, auto-scaling to application health moni ring. At the same time, you retain full
control over the AWS resources powering your application and can access the underlying resources at any time.

if you dont use elastic bean stalk you want to do manually below works

we should install ec2 instance first, on top of it,

we should install java, web server like tomcat server and then upload our code and other stuff on s3 service.

we need to setup mysql server on RDS service and we need to connect our application to RDS.
```

##### RDS
```
Whenever you require relational databases you should go for RDS.

RDS engines -> MySQL, PostGREsql, Oracle, Amazon Arora, SQLServer, MariaDB
```

##### S3
```
Whenever you want to store and retrive large amount of data on AWS Cloud.

ex: upload jar file or war file or any other files on aws cloud we use S3 Service.
```

##### ROUTE 53
```
Whener you deploy your application on aws cloud then you need to configure a domain for your application.

you cannot provide your ip address of your machine to end users to access your applications.

```
