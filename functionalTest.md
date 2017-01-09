# Functional Test Training Curriculum
All work can be conducted easier inside a development environment on linux (preferred). linux
mint 18 is a very well supported OS for development and testing work.

We will use Oracle JDK 8 for all purposes.

We will use Fake Online REST API for all tests which can be reached here:
https://jsonplaceholder.typicode.com

## Week 1
Main goal of this week is to learn how to use tools involved in functional testing such as 
cucumber, gradle, rest-assued, selenium and saucelabs. As well as their integration with 
bitbucket integration.

### Day 1
* Install Intellij Community edition
* Install OracleJDK 8 
* Create first Gradle & JUnit driven cucumber test

### Day 2
* Create cucumber scenarios for the following features
    * Posts must be accessible 
        * Get a single post by id
        * Obtain a list of posts
        * Obtain posts by a single user
    * Photos must be accessible
        * Get a single photo by id
        * Obtain a list of all Photos
        * Obtain associated albums of a single Photo

### Day 3
* Implement cucumber features using REST-Assured.

### Day 4
* Continue on Implementation using REST-Assured.

### Day 5
* Demo your work 

## Week 2
### Day 1
* Create cucumber scenarios for following features and broken down scenarios
    * Intro Paragraph Must Exist
        * Intro paragraph title must exist with bold font
        * Two paragraphs must exist within Intro section
    * Code Example Section Must Exist
        * There must be a code example section with a greyed out background
        * Run button must exist
        * Underneathe run button there must be an output section
    * Resources section must exist
        * There must be links to Posts, Comments, Albums and Photos
        * There must be a text describing '100 items' in line with link to posts
        * There must be a text describing '500 items' in line with link to Comments

### Day 2
* Implement cucumber tests using selenium

### Day 3
* Continue to Implement cucumber tests using selenium

### Day 4
* Develop a Bitbucket project and push test code
* Create a basic pipeline in the project running test code

### Day 5
* Demo what you learned