# earlybird-api
Purpose: The web application earlybird allows users to be notified when new issues are opened on their favorite open source projects

## Environment Variables
To authenticate requests, provide a GitHub OAuth token. Here are the [instructions](https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/).
The environment variable required is `OAUTH_TOKEN`. Unauthenticated requests have a rate limit of 60 per hour. Authenticated requests
have a limit of 5000 per hour. The application will run without a token, but the rate limit will be hit rather quickly.

## Code Style
In IntelliJ, `CMD + ,` to open preferences. Under Code Style, modify the scheme to use the `intellij-java-google-style.xml` 
listed in the project root. 







































































































































































































































































