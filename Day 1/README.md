              DAY 1 : BASIC REACT  INFORMATION 
Why we install node js while using react 
   A. build tools :> node.js comes with npm (Node Package Manager) which is a powerful tool for managing dependencies and packages. React applications often use npm to install and manage libraries and tools needed for development, such as webpack, Babel, and ESLint. 

 B.Development server :> node.js can be used to run a development server that server uour react application locally during development. like creating a first react app.

 C.Server-side rendering :> check before send to render , While React is typically used for client-side rendering, Node.js can be used for server-side rendering with   libraries like Next.js. This allows React applications to render on the server before sending them to the client, which can improve performance and SEO

 D.Tooling and scripts :>  Many React projects use Node.js scripts for tasks such as compiling code, running tests, and deploying applications. Node.js provides a runtime environment for these scripts to execute.

 E. npm Scripts:> Node.js allows you to define custom npm scripts in your project's package.json file. These scripts can automate various development tasks, such as building, testing, and deploying your React application.
              TO INSTALL REACT
           1. Traditional approach:> npx creat-react-app@latest
           2. Modern and efficent,high performance way :>vite create@latest   

 The folder structure of npx                
your-app/
  ├── node_modules/
  ├── public/
  │   ├── index.html
  │   ├── favicon.ico
  │   └── ...
  ├── src/
  │   ├── index.js
  │   ├── App.js
  │   ├── App.css
  │   ├── logo.svg
  │   └── ...
  ├── package.json
  ├── README.md
  └── ...
  information about how its works
  
node_modules/: This folder contains all the dependencies and devDependencies of your project. It's generated when you run npm install or yarn install and isn't typically committed to version control due to its size.

public/: This folder contains static assets like HTML files, images, and icons. The index.html file in this folder is the entry point for your React application.

index.html: The main HTML file of your application, which includes the root div where your React components will be rendered. It also includes links to CSS files and scripts.
src/: This folder contains the source code of your React application.

index.js: The entry point of your React application. This file typically renders the root component (App) into the DOM.

App.js: The main component of your application. This is where you define the structure of your UI and include other components.

App.css: The CSS file associated with the App component. This is where you define styles specific to this component.

logo.svg: A sample SVG image file included by default.

package.json: This file contains metadata about your project and its dependencies. It also includes scripts for running various tasks like starting the development server or building the production version of your app.

README.md: A Markdown file containing information about your project, including instructions for setting it up and running it.

          The folder structure of vite 
          your-app/
  ├── node_modules/
  ├── public/
  │   ├── index.html
  │   └── ...
  ├── src/
  │   ├── main.js   // or index.ts for TypeScript projects
  │   ├── App.vue   // or App.jsx for JSX projects
  │   └── ...
  ├── vite.config.js
  ├── package.json
  └── ...
 
           Devpendencies VS DevDependencies
 Dependencies: These are the packages that are necessary for your application to run in a production environment. These could include libraries like React, React DOM, Redux, Axios, etc. Dependencies are typically installed using npm install --save or npm install shorthand, which adds them to your package.json file under the "dependencies" key. When you deploy your application, these packages will be included.

DevDependencies: These are packages that are only needed for development and testing purposes. Examples include testing frameworks like Jest, development servers like webpack or Babel, linting tools, and so on. DevDependencies are installed using npm install --save-dev or npm install -D, which adds them to your package.json file under the "devDependencies" key. DevDependencies are not included when your application is deployed because they are not needed for the application to run in a production environment.
NOTES:> 
 To Install one package ;> npm install (package-name )
 To install package:> npm install
 To find any npm package :> npmjs.com
 TO run package.json script :npm run key ( like dev)
  folder files information
  1.pacakge.json;> hold project information or metadata like, name, version, description, author, license and more

command line tool = npx and vite 

