# How to run this application in development environment
1. Install MongoDB Version 3.6.23 
2. Install Node.JS Version 12
3. Install Angular-CLI (for MacOS, sudo npm install -g --unsafe-perm angular-cli)
4. Change to directoy CustBE and run npm install
5. in CustBE directoy, run npm start
6. open the link http://localhost:8080/ and you will be able to see the homepage
7. For Frontend environment, change to CustFE directory and run npm install, it will install all packages required for Angular
8. run ng serve to test if frontend works. if you see this error "/customercontactdb/custFE/node_modules/@types/node/index.d.ts (20,1): Invalid 'reference' directive syntax." then go to folder "custFE/node_modules/@types/node/index.d.t" and remove one / from line 20 /// <reference lib="es2015" />
9. rerun ng serve and you will be able to see frontend pages in http://localhost:4200/

Now you should be able to work on the codes and develop it further. 