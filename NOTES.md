# Notes

## Publishing

To publish the Theme with 2FA enabled it's necessary to create a [Personal Access Token](https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/) (make sure to grant all permissions). First run `apm publish patch` then enter the token generated on the page there, after this you'll be prompted for the GitHub username and then the password. Instead of the password the PAT generated before should be entered.
