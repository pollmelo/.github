# POLLmelo
POLLmelo is beeing developed as a student project to enable foodsharing.de to use this poll tool to create feature requests. These can then be voted on by the community to test which feature requests are deserving of the devs time. The goal is to create a simple prototype.


## How to start POLLmelo
1. Pull Backberry repository (backend) and Fruitend repository (frontend) into separate local directories.
2. Install [Docker](https://docs.docker.com/engine/install/), [DDEV](https://ddev.readthedocs.io/en/latest/users/install/ddev-installation/) and [NPM](https://nodejs.org/en/download).
3. Follow instructions in Backberry README.
4. Open terminal in Backberry directory and run backend with `ddev start`.
5. Open terminal in Fruitend directory and run frontend with `npm install` & `npm run dev`.
6. Follow shown link (localhost:3000/) to view POLLmelo.
7. Have fun!

## Troubleshooting
If you experience the following issue, these steps should help you to access POLLmelo: When visiting POLLmelo via localhost with the backend server successfully running and you cannot create polls or access polls already created, open developer tools in your browser and navigate to "console". There you should find an error saying that the backend cannot be access. You will be given a link to backberry ddev. Open this link and allow access by navigating through the advanced settings. Go back to POLLmelo and relaod the page.
