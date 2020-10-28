# uvdesk-docker
UVDesk Docker manifests 3 containers deployed: Nginx:1.19.3-alpine, Mysql-server:8.0.22-1.1.18 and PHP:7.4-fpm-alpine.

STEP 1: Git me!: git clone https://github.com/schlepper-code/uvdesk-docker.git

STEP 2: Go to folder: cd uvdesk-docker and download UVdesk Open Source: wget https://cdn.uvdesk.com/uvdesk/downloads/opensource/uvdesk-community-current-stable.zip

STEP 3: unzip uvdesk-community-current-stable.zip

STEP 4: For installation, set full permissions on folder uvdesk-community-v1.0.12: chmod 777 -R uvdesk-community-v1.0.12

STEP 5: Now watch this Docker magic: docker-compose --file docker-compose.yml up -d
