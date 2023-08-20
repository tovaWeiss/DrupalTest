# DrupalTest
drupal test

steps to start site:
1. clone the progect from github: git clone https://github.com/tovaWeiss/DrupalTest.git
2. enter to project folder: cd DrupalTest
3. start docker containers: docker-compose up -d
4. import db:  cat ./drupal/backup.sql | docker exec -i mysql /usr/bin/mysql -u root --password=${pass} drupal
5. go to localhost:80 and enjoy drupal site with simple page & Aggregator module is already on!

good luck :)