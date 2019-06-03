# WebSearch

This is a project for my CS 172 class at UCR (Information Retrieval). This project is a simple search engine that searches through previously scraped .gov web pages and allows the user to search through them. 
- Each web page is scored and indexed through Lucene
- The pages are sent along with their score to a back end located at http://localhost:8080/ through Spring Boot in a JSON format
- The front end is created through Angular and then reads from http://localhost:8080/
- The front end is located at http://localhost:4200/

## Usage
In one shell run the following commands to run the back end:

```
cd ~/WebSearch/testing/src/app/demo
mvn spring-boot:run
```
In another shell run the following commands to run the front end:
```
cd ~/WebSearch/testing/search
ng serve --open
```

