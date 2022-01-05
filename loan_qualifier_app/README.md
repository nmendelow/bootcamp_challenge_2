# Loan Analyzer 

This project is add features to a loan analyzer program which allows a customer to check their eligibility for a loan against a .csv file of imported bank offerings. The program filters the list of loan options automatically. The updated features will allow the user to export the refined list to a .csv file to a path of their choosing.

---

## Technologies

This program should be run with python verson 3.9 or greater, and the following libraries should be installed:
Fire,
Questionary,
Pathlib,
sys,
csv

---

## Installation Guide

n/a

---

## Usage

To begin, when running the program, you will be prompted for a path to load in the bank data.
(/screencaps/step_1.png?raw=true "Enter the file path here.")

Once the file has been sucessfully uploaded, the user will be prompted to enter in relavant data pertaining to their loan application
(/screencaps/step_2.png?raw=true "Answer the questions asked.")

The program will calculate a few financial ratios, and then display the details of the mortgage products which are available to the user given the information provided
(/screencaps/step_3.png?raw=true "Here are the loans the analyzer found.)

If no loans are found that the user qualifies for, the system will notify the user and terminate the program
(/screencaps/step_4.png?raw=true "Better luck next time.")

If there are loans found, the program will give the user the option to save the loans as a .csv file
(/screencaps/step_5_yes.png?raw=true "'Yes' option")
(/screencaps/step_5_no.png?raw=true "'No' option")

---

## Contributors

Neil Mendelow - https://www.linkedin.com/in/neil-mendelow/

---

## License

This code is covered by the MIT license.
