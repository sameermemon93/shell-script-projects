1. Update Package Lists:
      sudo apt update

2. Install the AWS CLI Using Package Manager
       sudo apt install awscli
   This command installs the AWS CLI along with its dependencies.

3. Configure AWS
      aws configure

Now it will ask to enter the Access Key ID, Secret Access Key, default region, and output format as prompted. These credentials will be used by AWS CLI for authentication.

4. Let's create Access Key
      Click on Security Credentials
      Scroll down and click on create access key
      Once you have generated the secret access key, make sure to store it on your local machine, you cannot retrieve the secret access key again.

5. Now jump back to step 4

Enter your access key id and secret access key also select the default region which you want and default output format as json.

Congratulations! You've successfully installed and configured AWS CLI on your Ubuntu machine. With this powerful tool at your disposal, you're now equipped to manage your AWS resources efficiently, automate tasks, and streamline your cloud operations.
