This template was forked from a repository created by Souvik Biswas

# Use this template to spin up docker Dev envrionment for flutter
# Alternatively download the flutter development envrionment docker image from docker.io/publicdockerimages/flutter_dev_env
# Steps to use this template

1. Clone this repo:
   ```bash
   git clone https://github.com/p-r-t/flutter_docker.git
   ```

2. Open this project directory using **VS Code**:
   ```bash
   code flutter_docker
   ```

3. Click on the **Remote Development icon** (present in the bottom-left corner of VS Code).

4. Select the option **Remote-Containers: Open Folder in Container** from the list.

5. Select the root directory which contains the **Dockerfile** (along with some other settings) and click on **Open** to start building the Docker container. This will take some time as it will download and setup all the tools in the container.

6. After the build finishes, you will be taken to the **bash terminal** of the **Docker container**.

7. Now, you can **build**, **test** and **run** Flutter apps in the container.

