# API Testing Framework

## What is this project?
This project is used to test APIs using Postman and run tests using Newman.

## Tools used
- Postman
- Newman
- GitHub Actions

## What it does
- Runs API tests
- Checks response status
- Validates response data
- Generates report

## How to run
Run this command:

newman run API-Testing-Framework.json -e QA_Environment.json

## CI/CD
Tests run automatically using GitHub Actions when code is pushed.