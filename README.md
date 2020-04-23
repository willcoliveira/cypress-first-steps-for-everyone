# First Steps with Cypress

In this current repo you will be able to learn a bit more about [Cypress](https://www.cypress.io/). The API documentation is available [here](https://docs.cypress.io/api/api/table-of-contents.html). 

### Dependencies
You will need to install the Node.js to execute the project. Download the latest Node available version [here](https://nodejs.org/pt-br/download/). Also, you can install via cli (MAC or Linux) using the Node Version Manager with the following commands:
> ```bash
> curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.1/install.sh | bash
>
> nvm install node
>
> nvm use node
> # Checking the version
> npm -v
> ```

After the completed node's installation, you will need to clone this current repo.

> ```bash
> # Git Links
> https://github.com/willcoliveira/cypressfirststeps.git
> git@github.com:willcoliveira/cypressfirststeps.git
> ```

### Installing the dependencies 
Open the repo folder and install all dev dependencies using:
> ```bash
> yarn 
> ```

You will see the following messages: 
> ```bash
> yarn install v1.15.2
> info No lockfile found.
> [1/4] 🔍  Resolving packages...
> [2/4] 🚚  Fetching packages...
> [3/4] 🔗  Linking dependencies...
> [4/4] 🔨  Building fresh packages...
> success Saved lockfile.
> ```

### How to Run functional tests with Cypress Interface

To run the specs with headed GUI and have a way to debug the tests start Cypress using: 

> ```bash
> yarn cy:open
> ```

With the last command above, Cypress interface will be open and you can select the browser and the exactly file that you want to run. In addition, you are able to select to run all files directly clicking on "Run All Specs" Button.

Also, you can run and follow all tests using the command below:
> ```bash
> yarn cy:run
> ```


### How to Run functional tests with Cypress using CLI
The following command will run all the specs in headless mode.

> ```bash
> # Starting the tests via CLI
> yarn cy:run:headless
> ```

