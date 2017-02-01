#### Learning Node Js With Heroku
This repository contains a sample code that will be helpful if you want to deploy NodeJs Application with **Heroku**
We will have to start with :

1. Create a **Heroku** account @ [Heroku](https://www.heroku.com/)
2. Download Heroku cli from choosing a specific application type
3. For nodeJs make sure you have **node** and **npm** working
  In case of Ubuntu type
  `sudo apt install nodejs`
  `sudo apt install npm`

4. Check if they are properly installed or not via

  `node -v && npm -v`

5. Once completed you are ready to make any nodeJs Application
6. Clone any git node js application repository e.g [Sample NodeJs App](https://github.com/r0hi7/learningNodeJs)
7. `heroku login` Enter Credentials
8. Creating an application to start heroku with

  `heroku create` or `heroku apps:create <appname>`

9. `git push heroku master` will triger continug integration with heroku and build your app TADA.
