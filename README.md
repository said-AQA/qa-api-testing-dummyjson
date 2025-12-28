# QA API Automation – DummyJSON (Postman & Newman)

 ![API Tests](https://github.com/said-AQA/qa-api-testing-dummyjson/actions/workflows/api-tests.yml/badge.svg)
 
##  Overview
This repository contains an **API automation testing project** built using **Postman** and **Newman**, designed to validate authentication and product endpoints on the **DummyJSON public API**.

The project demonstrates **real-world QA API automation practices**, including functional, negative, schema, header, and performance testing, fully executable via CLI and CI-ready.

API under test:  
https://dummyjson.com

---

##  Test Coverage

###  Authentication
-  Login – valid credentials
-  Login – invalid credentials
-  Access token validation

###  Products
-  Get product by ID
-  Search products
-  Pagination (limit & skip)

---

## Test Types Implemented
- Functional testing
- Negative testing
- Header validation
- JSON schema validation
- Performance testing (response time)
- CLI execution (Newman)

---

## Tech Stack
- **Postman**
- **Newman**
- **Node.js**
- **npm**
- **Git & GitHub**
- **GitHub Actions (CI)**

---

## Project Structure

```text
qa-api-testing-dummyjson/
├─ collections/
│  └─ dummyjson_api_tests.postman_collection.json
├─ environments/
│  └─ dummyjson_env.postman_environment.json
├─ package.json
├─ package-lock.json
├─ .gitignore
└─ README.md

## How to Run the Tests
## Install dependencies
npm install

## Run API tests with Newman
npm run api:test

 Test Assertions Examples

Status code validation (200 / 400)

Required response fields

JSON schema validation

Response headers

Response time thresholds

## CI / GitHub Actions

This project includes a GitHub Actions pipeline that automatically runs API tests using Newman on every push.

Test results are available in the Actions tab of the repository.

## Author

Said
QA Engineer – Manual & Automation

This project is part of a personal QA automation portfolio.
