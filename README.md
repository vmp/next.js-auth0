# DO NOT USE THIS IN PRODUCTION

## this repo is deprecated


I built this repo when I was just playing around with Auth0 and NextJS. Now that I'm working at Auth0 for almost 2 years, I can say that it is the wrong approach to use. Auth0 will be releasing guidance on this in the near future, but the short explanation is: 

## Regarding authentication, treat your SSR apps as server apps.

- Create a custom server handler
- Follow our [guidance](https://auth0.com/docs/quickstart/webapp/nodejs/01-login) on how to secure NodeJS server apps
- Profit :moneybag:

