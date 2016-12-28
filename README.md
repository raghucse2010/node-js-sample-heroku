# node-js-sample-heroku
A sample barebone for running node js on heroku server.

# Running locally
 Make sure you have installed Node js globally and clone the git repo 
 
 git clone git@github.com: raghucse2010/node-js-sample-heroku.git  # clone the repository
 cd node-js-sample-heroku                                          # make directory active
 Run : npm install                         # This will download all the required dependencies provided in the package.json
 
 Test is locally by giving : node index.js
 and you should be able to see app running on localhost:5000.
 
 # Delpoying to Heroku
 
  1. Install Heroku Toolbelt from https://toolbelt.heroku.com/ 
  2. Use command line to login into heroku account : heroku login 
  3. Create app using : heroku create node-app-samplex
  4. clone the heroku app you just created to the local directory. 
  5. Run : git push heroku master 
 
You should be able to see app running on the https://node-app-samplex.herokuapp.com   
