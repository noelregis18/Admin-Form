# Admin_Form

A dynamic form generation system built with PHP that allows clients to create customized forms on-the-fly.

## Overview

This project provides a simple yet powerful way to generate custom forms without coding knowledge. The client can specify the number of questions, question types, and options, and the system will immediately generate a functional form.

## Files

### index.php

This file provides the interface for clients to design their custom form:
- Specify the number of questions
- Set form title and description
- Define each question with options for:
  - Text input questions
  - Radio button questions
  - Checkbox questions
- For radio and checkbox questions, clients can specify the number and text of options

### admin.php

This file generates the actual form based on the client's specifications:
- Renders the form with the specified title and description
- Creates the appropriate input fields for each question type
- Handles text inputs, radio buttons, and checkboxes according to the client's design

## Features

- Dynamic form generation
- Support for multiple question types
- Customizable options for radio buttons and checkboxes
- Clean, responsive design using Bootstrap
- User-friendly interface

## Prerequisites

- Apache2 web server
- PHP installed on your system
- Web browser with JavaScript enabled

## Usage

1. Access the index.php file in your web browser
2. Specify the number of questions you want in your form
3. Enter the form title and description
4. Define each question and select its type
5. For radio and checkbox questions, specify the options
6. Submit to generate your custom form

## Styling

The project uses Bootstrap 4 for styling and responsive design, along with Google Fonts for typography.

