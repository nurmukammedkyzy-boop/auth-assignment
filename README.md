# Auth Assignment

This project contains a Sequence Diagram and OpenAPI documentation for a simple authentication system.

## Contents

- `sequence_diagram.pdf` — Sequence Diagram for the login process
- `openapi-auth.yaml` — OpenAPI documentation for authentication endpoints
- `explanation.md` — short explanation of how the login feature works

## Features

The API documentation includes the following endpoints:

- `/login`
- `/registration`
- `/reset-password`

## Login Flow

1. The user enters a username and password.
2. The request is sent to the Web Server.
3. The Web Server checks the user data in the Database.
4. The server validates the credentials.
5. The server returns either a success response with a token/session or an error message.

## Purpose

This assignment demonstrates:
- interaction between system components using a UML Sequence Diagram
- REST API documentation using OpenAPI/Swagger
- basic authentication flow in a web application