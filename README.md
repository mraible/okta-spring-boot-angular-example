# Spring Boot API with Angular UI
 
Example app that shows how to create a Spring Boot API and display its data with an Angular UI.

Set the following environment variables to talk to Okta:

```
export STORMPATH_CLIENT_BASEURL=https://dev-XXX.oktapreview.com
export OKTA_APPLICATION_ID=XXX
export OKTA_API_TOKEN=XXX
```

You should be able to get these values from reading [Getting Started with Okta](https://github.com/stormpath/stormpath-sdk-java/blob/okta/OktaGettingStarted.md).

To run the server, cd into the `server` folder and run `mvn spring-boot:run`.

To run the client, cd into the `client` folder and run `npm install && ng serve`.
