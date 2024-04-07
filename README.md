# Password Generator API and Integrating an open-source third-party API

Welcome to the Password Generator API! This API allows you to generate secure passwords with customizable parameters.

## Description

This project provides a FastAPI-based web service for generating passwords. It includes an endpoint to generate passwords based on user-defined criteria, such as length and character types.

## Features

- Generate secure passwords with customizable parameters.
- Easy-to-use API endpoints for password generation.
- Comprehensive error handling and logging.

## Installation

There's no installation required for this project. Simply run the `main.py` file using Python.

## Usage

1. Run the `main.py` file.
2. Access the API endpoints to generate passwords and retrieve country-wise COVID-19 statistics.

### Generate Password

- **Endpoint:** `/generate-password/`
- **Method:** POST
- **Request Body:** JSON object containing parameters for password generation (e.g., length, character types).
- **Response:** JSON object containing the generated password.

### Get Countries Affected by COVID-19

- **Endpoint:** `/countries`
- **Method:** GET
- **Query Parameter:** `search` (optional)
- **Response:** JSON object containing the list of countries affected by COVID-19.

### Get COVID-19 Statistics

- **Endpoint:** `/statistics`
- **Method:** GET
- **Query Parameter:** `country` (optional)
- **Response:** JSON object containing the current statistics of COVID-19 spread in the specified country.

## API Documentation

Additional documentation for API endpoints can be found within the codebase.

## APIs Used

- **RapidAPI**
  - **Key:** `<RAPIDAPI_KEY>`
  - **Host:** `<RAPIDAPI_HOST>`
  - **Endpoints:** `/countries` and `/statistics`

## Authors

- [Baha Rehaan](https://github.com/rehaan17) - baha.rehaan17@gmail.com
