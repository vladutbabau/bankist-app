# Bankist App
Bankist is a simple and modern banking application built with JavaScript, HTML, and CSS. The app showcases key functionalities such as account management, fund transfers, loan requests, and more, all designed to demonstrate essential concepts of web development and JavaScript.

# 🚀 Features
User Authentication: Secure login with unique credentials for each user.
Transaction Display: View detailed records of deposits and withdrawals, including the transaction date.
Fund Transfer: Transfer money to other users seamlessly.
Loan Requests: Request loans based on a percentage of account balance.
Account Summary: Get a clear summary of total deposits, withdrawals, and interest earned.
Currency Formatting: Displays amounts formatted according to the user’s locale and currency.
Automatic Logout: Inactivity triggers an auto-logout after 2 minutes for enhanced security.
Sorting Transactions: Sort transaction history by amount in ascending or descending order.
👤 Test User Credentials
You can log in and test the app using the following credentials:

# Account 1
Username: js
PIN: 1111
@@@@@@@@@@@@
# Account 2
Username: jd
PIN: 2222
# 🛠️ How to Run Locally
# 1. Clone the repository:

git clone https://github.com/yourusername/bankist-app.git
# 2. Navigate to the project directory:
cd bankist-app

Open the index.html file in your browser to run the app.

# 📝 Functionalities in Detail
# Login System:

Enter the username and PIN to log in.
If credentials are correct, the dashboard is displayed with the user's data.

# View Transactions:

Displays a list of all transactions (deposits and withdrawals) with their respective dates.
Dates are formatted dynamically based on how recent they are (e.g., "Today," "Yesterday," or exact date).

# Account Summary:

Shows the total balance, total money deposited, withdrawn, and interest earned.

# Fund Transfers:

Transfer money to another registered user by entering their username and transfer amount.

# Request a Loan:

Request a loan if any deposit is greater than 10% of the requested loan amount.
Loan amounts are rounded down to the nearest integer.

# Close Account:

Users can close their account by providing the correct username and PIN.

# Transaction Sorting:

Sort transaction history in ascending or descending order by amount.

# Automatic Logout Timer:

Users are automatically logged out after 2 minutes of inactivity.
