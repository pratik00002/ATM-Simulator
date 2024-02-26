# ATM-Simulator
The ATM Machine Simulator is a Python program that mimics the functionality of an Automated Teller Machine (ATM). It allows users to interact with simulated banking operations such as checking balance, withdrawing money, depositing money, and exiting the ATM session. The simulator is designed to be user-friendly and easy to understand.
Features

    PIN Verification: Users are required to enter a PIN to access the ATM functionalities.
    Check Balance: Users can check their account balance.
    Withdraw Money: Users can withdraw money from their account, provided they have sufficient funds.
    Deposit Money: Users can deposit money into their account.
    Error Handling: The simulator provides appropriate error messages for invalid PINs, insufficient balance, and invalid input.

Class ATM

    Attributes:
        balance: Represents the current balance in the user's account. By default, it is initialized to Rs. 10,000.

    Methods:
        check_balance(): Returns a string indicating the current balance.
        withdraw(amount): Allows the user to withdraw a specified amount from their account. If the withdrawal amount is valid and there are sufficient funds, the withdrawal is processed, and a success message with the remaining balance is returned. Otherwise, an error message is returned.
        deposit(amount): Allows the user to deposit a specified amount into their account. If the deposit amount is valid, the deposit is processed, and a success message with the new balance is returned. Otherwise, an error message is returned.

main() Function

    The main() function serves as the entry point of the program.
    It prompts the user to enter their PIN and verifies it against the predefined sample PIN.
    If the PIN is valid, it presents the user with options to perform various transactions.
    Based on the user's selection, it calls the corresponding method of the ATM class and displays the result.
    The session continues until the user chooses to exit.

Usage

To run the ATM Machine Simulator, execute the Python script (atm_simulator.py). Follow the on-screen instructions to navigate through the ATM functionalities.
