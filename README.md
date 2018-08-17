# Joomla template for Platform.sh

## How to install

1. Clone this repository
2. Create a new platform.sh project

```
platform project:create
```

3. Add specific environment variables

```
platform variable:add ADMIN_LOGIN yourlogin
platform variable:add ADMIN_PASSWORD yourpassword
```

4. Push to platform.sh

```
git remote add platform <project id>@git.<project region>.platform.sh:<project id>.git
git push platform master
```

5. Backend

You can access your backend at `/administrator` with the credentials that you defined as variables.
