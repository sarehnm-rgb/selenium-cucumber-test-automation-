# Selenium Cucumber Test Automation Framework

A BDD test automation framework for a web application, built as a group project during a software testing bootcamp.

## Tech stack
Java · Selenium WebDriver · Cucumber (BDD) · TestNG · Maven · Page Object Model

## Architecture
- **Page Object Model** with generic, reusable element-handling methods
- **Base/parent class** with common actions (click, sendKeys, explicit waits, verifications)
- **ThreadLocal driver management** for parallel execution (Chrome/Firefox via WebDriverManager)

## My contribution
I was responsible for the core of the test framework: the parent class with reusable
base methods, the Page Object Model element-handling layer, and the ThreadLocal-based
driver setup for parallel execution.
(6 commits / ~630 lines — visible in the project's Git history under username "srhnm".)

> Note: This was a group bootcamp project, shared here with the team's consent for portfolio purposes.
