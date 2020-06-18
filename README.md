# SpringSecurityJDBCAuthentication
This is a simple spring JDBC authentication example using JDBC API and H2 DB. Here we extends "WebSecurityConfigurerAdapter" and overrride "configure" method 
and added JDBC authentication using datasource. Also we added custom query to fetch from H2.
Added predefined schema for users and authorities table. Also added data.sql to add the custom data.
Diffrent schemas are available here "https://docs.spring.io/spring-security/site/docs/current/reference/html5/#user-schema" 
