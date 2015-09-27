OAuthGoogle
========

A demo and helper class for providing Google OAuthGoogle authentication in java.

Assumptions

- familiarity with OOP, java, maven, and JEE
- java application server listening on localhost:8081

Prerequisites

- Google API access credentials (Client ID, Client Secret). Set it up here https://code.google.com/apis/console/
- Set up allowed Redirect URIs at Google API -> API Access. Input: http://localhost:8081/OAuthGoogle/index.jsp
- a positive outlook on life

Usage

1. Add Client ID, and Client Secret parameters to GoogleAuthHelper.java
2. Compile the project ($ mvn clean install)
3. Deploy war to application server
4. Browse to: http://localhost:8081/OAuthGoogle/
5. Click "log in with google" on top of this page
