------------------------------------------------------
Push PHP code Image:-
------------------------------------------------------

# step1 : Create a docker images
- sudo docker build -t phpcode .

# step2 : Create a docker images tags (releases)
- sudo docker tag phpcode:latest wahid74/phpcode:v1.0.0
- sudo docker tag phpcode:latest wahid74/phpcode:v1.0.1
- sudo docker tag phpcode:latest wahid74/phpcode:v2.0.0

# step3 : login into docker
  - sudo docker login
     - username :
     - password :

# step4: push tag to docker hub.
  - sudo docker push wahid74/phpcode:v1.0.0

------------------------------------------------------
Push Sprinng boot Image:-
------------------------------------------------------
# step1 : create a docker images
 - sudo docker build -t ecom-webservice .

# step2 : create a docker images tags (release)
 - sudo docker tag ecom-webservice:latest wahid74/ecom-webservice
 - sudo docker tag ecom-webservice:latest wahid74/ecom-webservice:v1.0.0
 - sudo docker tag ecom-webservice:latest wahid74/ecom-webservice:v1.0.1
 - sudo docker tag ecom-webservice:latest wahid74/ecom-webservice:v2.0.0

# step3 : login into docker
  - sudo docker login
     - username :
     - password :

# step4: push tag to docker hub.
  - sudo docker push wahid74/ecom-webservice:v1.0.0