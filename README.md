# aws-bootcamp-cruddur-2023
tasks:
    - name: aws-cli
      env:
      AWS_CLI_AUTO_PROMPT: on-partial
      init: 
       cd/workspace
       curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip -o "awscliv2.zip"
       unzip awscliv2.zip
       sudo ./aws/install
       cd $THEIA WORKSPACE ROOT
      command: yarn build