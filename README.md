# Jenkins-job-caller-action

The Jenkins Job Caller Action enables the triggering of Jenkins jobs, utilizing Jenkins APIs to initiate the respective job.

If the job requires String parameters during the build process, those values should be passed as key1=value1&key2=value2
Note: API Token should be created by the user from the Jenkins

First, you need to generate an API token in Jenkins that will be used for authentication when making API requests. You can do this by navigating to your Jenkins instance, going to your user profile, and selecting "Configure" or "Manage User." Then, under the "API Token" section, you can generate a token.

Store Jenkins Credentials in GitHub Secrets:
To securely use the API token in your GitHub Action workflow, you should store it as a secret in your GitHub repository. Go to your repository settings, then "Secrets," and add a new secret with the Jenkins API token.
