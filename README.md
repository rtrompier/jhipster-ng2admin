# bis

This application was generated using JHipster 3.9.1 for the backend only.
We use the template ng2-admin for the front end.


## Development

Before you can build this project, you must install and configure the following dependencies on your machine:
1. [Node.js][]: We use Node to run a development web server and build the project.
   Depending on your system, you can install Node either from source or as a pre-packaged bundle.

After installing Node, you should be able to run the following command to install development tools. 
You will only need to run this command when dependencies change in package.json.

    npm install

Run the following commands in two separate terminals to create a blissful development experience where your browser
auto-refreshes when files change on your hard drive.

    npm start

NPM is used to manage CSS and JavaScript dependencies used in this application. You can upgrade dependencies by
specifying a newer version in `package.json`.

## Building for production

To optimize the bis application for production, run:

    mvn -Pprod clean package

This will concatenate and minify the client CSS and compile TypeScript files. It will also modify `index.html` so it references these new files.
To ensure everything worked, run:

    java -jar target/*.war

Then navigate to [http://localhost:8080](http://localhost:8080) in your browser.

Refer to [Using JHipster in production][] for more details.
