# Airflow DevContainer Setup

This repository provides a seamless development environment for [Apache Airflow](https://airflow.apache.org/) using Visual Studio Code's DevContainers.

## Features
- Isolated development environment using Docker.
- Quick startup with pre-configured settings.
- Suitable for local Airflow experimentation or DAG development.

## Prerequisites
1. [Docker](https://docs.docker.com/get-docker/)
2. [Visual Studio Code](https://code.visualstudio.com/)
3. [Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extension for VS Code.

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/elarib/airflow-devcontainer.git
   cd airflow-devcontainer
   ```
2. Open the project in VS Code. When prompted, open the project in the DevContainer.

3. Access the Airflow web interface at http://localhost:8080/ using the credentials (Username: admin, Password: admin)
4. To develop your DAGs, place them in the dags directory. The Airflow server will automatically pick them up.
