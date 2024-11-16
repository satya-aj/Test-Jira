# Test-Jira

## Setup github pages

Navigate to Repo settings -> Pages
Under Build and Deployment
Select main Branch and /root and save

## TODO in Middleware.py file

Replace GITHUB_TOKEN with your github token in line 9
Replace Github url in line 27

Steps to run

# Run Ngrok

ngrok http 5000

# Create WebHook in Jira

Path -- Settings -> System -> Webhooks
-- Create New WebHook
Add Name
Add Url which is coming from Ngrok command
Select required items to trigger Github Action
Save

# Run Middleware.py

python Middleware.py

Create an issue in Jira and Github workflow will triggre and in new tab index.html file will open.
