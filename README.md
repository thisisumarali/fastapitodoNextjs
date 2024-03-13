# FastAPI App with Neon Serverless Postgres and AWS App Runner

_This repository is a companion to a [FastAPI and AWS App Runner with Neon](https://neon.tech/blog/deploy-a-serverless-fastapi-app-with-neon-postgres-and-aws-app-runner-at-any-scale) post on the Neon blog._

This repository hosts a FastAPI application leveraging Neon Serverless Postgres, deployed via AWS App Runner. This setup offers a solution for developing and deploying Python applications with demands for performance and reliability.

## Features

- **FastAPI**: A modern, fast (high-performance) web framework for building APIs with Python 3.11, featuring automatic Swagger UI generation, type checking, and asynchronous request handling.
- **Neon Serverless Postgres**: A scalable, fully managed serverless Postgres database, minimizing operational overhead.
- **AWS App Runner**: An AWS service that provides a simple, fully managed environment for deploying containerized-type applications, eliminating the need for infrastructure configuration and management.

## Prerequisites

- Python 3.11
- AWS Account
- A [Neon account for Serverless Postgres](https://neon.tech/)
- Git
- [Poetry](https://python-poetry.org/) for Python dependency management

## Getting Started

### 1. Clone the Repository

Clone the repository to your local machine and navigate into the project directory:

```bash
git clone https://github.com/neondatabase/fastapi-apprunner-neon
cd fastapi-apprunner-neon
```

### 2. Setup Your Python Environment with Poetry

Initialize a new environment using Poetry and install the project dependencies:

```sh
poetry install
```

### 3. Neon Serverless Postgres

- Sign up or log in to your Neon account
- You'll need this the database connection string for configuration.

### 4. Deploy to AWS App Runner

Follow along in the blog post to configure AWS SSM Parameter Store and deploy the FastAPI to AWS App Runner.
"# fastapitodoNextjs" 
