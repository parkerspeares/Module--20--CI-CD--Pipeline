Challenge-20: CI CD PIPELINE
Overview
This project showcases the integration of the cypress-ctrf-json-reporter package and the github-actions-ctrf package. While not a typical application, it demonstrates automated testing and deployment workflows using GitHub Actions.


Table of Contents
Required Technologies
Installation
Usage
Features
License
Technologies Used
Credits
Contact

Required Technologies
To install and use this project locally, ensure the following are available:
Node.js
MongoDB

Installation
Clone or download the project files.
Open the project folder and run the terminal from the root directory.
Install dependencies using:
bash
Copy code
npm i
npm run install
Navigate to the server folder and rename .env.EXAMPLE to .env.
Seed the database with sample data by running:
bash
Copy code
npm run seed
Build and start the application:
bash
Copy code
npm run build
npm run start:dev
Additional commands can be found in the package.json file.

Usage
This assignment demonstrates Cypress testing integration within GitHub Actions.

Navigate to the GitHub Actions tab in the repository.
Open the development testing workflow and view the summary of tests under the "Deploy" job.
A CTRF-formatted test report displays the results of all conducted tests.

Features
Cypress testing integration.
CTRF test result visualization.
Branch protection rules.
Automatic deployment via GitHub Actions.

License
Licensed under the MIT License.

Technologies Used
VS Code
Node.js 
MongoDB 
Cypress 
GitHub Actions

Credits
Author: Parker Speares

Contact
For questions, please reach out