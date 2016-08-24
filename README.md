# Likedin Connect Example

- Create an app at https://www.linkedin.com/developer/apps/
- Check `r_basicprofile` and `r_emailaddress` in the app settings
- Set redirection URL to `http://localhost:3000/users/auth/linkedin/callback`
- You must have a `config/application.yml` with the linkedin ID and SECRET
- You need some fields on your User model: uid, provider, first_name, last_name, picture_url, token, token_expiry
- rince and repeat for production