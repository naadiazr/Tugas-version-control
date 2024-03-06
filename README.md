# Collaborator Names Project

This project is created as a part of an assignment to demonstrate a workflow using GitHub Actions. The objective of this project is to create a workflow that generates a list of collaborator names and saves it as an artifact when a pull request is created targeting the `main` branch.

## Workflow Overview

The workflow consists of the following steps:

1. **Checkout Repository:** This step checks out the repository's code to the runner environment.
2. **Set up Python:** Sets up the Python environment with the specified version (3.x).
3. **Run Python script:** Executes the Python script `Project-Kel-Jatim.py`, which prints out a list of collaborator names to an `output.txt` file.
4. **Upload Artifact:** Uploads the `output.txt` file as an artifact named `collaborator_names`.

## Running the Workflow

The workflow will be triggered automatically when someone creates a pull request targeting the `main` branch. 

Once the workflow has completed successfully, you can view the list of collaborator names by downloading the artifact named `collaborator_names` from the GitHub Actions tab in the repository.

For any issues or questions regarding this project, please feel free to reach out.
