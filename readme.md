Project template
======

This is a basic template for a web based project. It utilizes [Parcel.js](https://parceljs.org/) for a more 
simplified path towards automatic bundling of assets and other items. 

Installing
====
* Make sure you have a fairly recent version of Node.js. [nvm](https://github.com/creationix/nvm) is a great tool for keeping up to date with Node on Unix like platforms. 
* if on Windows - for the best ease of use with Node, it's recommended installing a Linux subsystem which can be obtained from the Windows store but it is available as a installer instead as well. 
* once Node is installed, you should have access to the `npm` command. Run `npm install` to install all the necessary dependencies.

Scss
====
* Regular css bundling ought to work by default but if you want scss handling, you'll need to make sure you install ruby and sass. See [https://sass-lang.com/install](https://sass-lang.com/install)
* that page also has a number of alternatives if you don't want to install ruby

Project structure
======
The way that parcel works, unfortunately means that customizing the project structure is somewhat limited but this is probably the easiest to understand. 

app 
  -- src
     <any other folders and javascript files>
  -- css
     <any other folders and css/scss files>
  -- index.html 
  
  
How to use
======
* Run `npm start` to start things up in development mode. You can access the development server at `localhost:1234`
* When you're ready to deploy, run `npm run build` - the output will get written to the `dist` folder by default.


Side note - What if more custom features are needed
=====
Though it does fill a large number of app types, Parcel is still rather limited in the way things can be customized out of the box; should more features be required, there are a number of alternatives 
* [Webpack](https://webpack.js.org/)
* [grunt](https://gruntjs.com/)
* [gulp](https://gulpjs.com/)