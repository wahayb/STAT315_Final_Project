# **STAT315 Group6 Final Project**
## Instructions:
### Step 1: Building a Docker Image
Ensure that Docker is downloaded on the local machine and running.

Download the project.zip file from github.

Unzip it and place it in a known directory.

Open the Terminal or PowerShell and navigate into the project folder.

Run the following command without the quotation marks in order to build the image and make it available “docker build -t project:0.0.1 .”
### Step 2: Accessing the Notebook
Start the container by running the following command in the Terminal or PowerShell without the quotation marks with ensuring that X is the correct file path on your machine “docker run -v X:/home/notebooks -p 8888:888 - -name pynb_devcontainer_new project:0.0.1”

After running the code, scroll to find an URL and copy paste it into a web browser window.

The .ipynb file should be be visible

Open the notebook file in a new tab and and run all cells
### Necessary Files:
The data file, notebook, Dockerfile are included as a zip file in the GitHib repository
