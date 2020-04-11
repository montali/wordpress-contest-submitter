# wordpress-contest-submitter

WordPress plugin you can use to host website creation contests! Kicks participants out of their website when submitting.

## How to use

The plugin creates a backdoor in the website. When the participant submits the website, you just have to GET `[your-website]/?contestend=thatsit`.
This will:

- Create you a new user: `username: contestJudge password: judgeMeBro`
- Delete every other user, reassigning its posts to you.
- Disabling CloudAccess' auto login plugin.
