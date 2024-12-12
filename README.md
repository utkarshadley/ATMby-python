ATM Machine Simulation in Python

This Python code simulates a basic ATM machine. It allows users to perform common ATM functions like checking balance, withdrawing cash, and depositing money. The code utilizes basic Python programming concepts like input/output operations, conditional statements, and loops.

Key Features:

User Authentication: The program prompts the user to enter their PIN to authenticate their identity.
Balance Inquiry: Users can check their current account balance.
Cash Withdrawal: Users can withdraw money from their account, with a limit on the withdrawal amount.
Cash Deposit: Users can deposit money into their account.
Exit: Users can exit the ATM application.
How it Works:

User Authentication:

The program asks the user to enter their PIN.
If the entered PIN is correct, the user is allowed to proceed.
If the PIN is incorrect, the user is prompted to try again or exit the application.
Main Menu:

Once authenticated, the user is presented with a main menu displaying the available options:
Check Balance
Withdraw Cash
Deposit Cash
Exit
Option Selection:

The user selects an option from the menu.
Based on the selected option, the program performs the corresponding action.
Transaction Processing:

Check Balance: The program displays the current account balance.
Withdraw Cash: The program prompts the user to enter the withdrawal amount. If the amount is valid and available, the balance is updated, and the withdrawal is processed.
Deposit Cash: The program prompts the user to enter the deposit amount. The balance is updated with the deposited amount.
Exit:

The program terminates, and the user exits the ATM simulation.
Note: This is a simplified ATM simulation. Real-world ATMs have additional features like transaction history, mini-statements, and security measures. This code can be further enhanced to incorporate more complex functionalities and security considerations.
