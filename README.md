# RestaurantsWithSQLAlchemy

## Table of Contents
* [Description]
* [Installation]
* [Usage]
* [License]
* [Authors]

## Description
Welcome to the "RestaurantsWithSQLAlchemy" project! This project involves working with three classes: `Restaurant`, `Customer`, and `Review`. These classes represent entities in the context of restaurant reviews and customer interactions. The relationships between these models are defined as follows:
- A `Restaurant` can have multiple `Reviews`.
- A `Customer` can write multiple `Reviews`.
- A `Review` is associated with both a `Restaurant` and a `Customer`.

### Project Overview
Here's a brief overview of the key entities within the project:

- `Restaurant Class`: Represents restaurants and their interactions with customers. You can perform various operations related to restaurant management using this class.

- `Customer Class`: Represents customers who write reviews for restaurants. It includes attributes for the customer's name and family name.

- `Review Class`: Represents reviews written by customers for restaurants. This class helps manage and store review-related data.

## Installation
To get started with this project, follow these installation steps:

1. Clone the repository to your local machine using the following command:
   ```bash
   git clone https://github.com/winny52/RestaurantsWithSQLAlchemy

2.Navigate to the project directory:

cd RestaurantsWithSQLAlchemy

3.Install the necessary dependencies using pipenv. If you don't have pipenv installed, you can install it via pip:


pip install pipenv

4.Install project dependencies with pipenv:

pipenv install

### Usage
You can now use the project to manage restaurant reviews and customer interactions. Refer to the documentation within each class (Restaurant, Customer, and Review) for detailed information on how to use them effectively.

### License
This project is licensed under the MIT License - see the LICENSE file for details.

### Authors
Winny Chelangat