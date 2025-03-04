# UserProfileValidatorAndEmailSender

## Description
This Python script validates user inputs such as phone number, Instagram ID, and email, then compiles them into a formatted message and sends it via email using SMTP.

## Features
- Validates phone numbers (Indian format: `XXX-XXX-XXXX` where `X` starts with 6, 7, 8, or 9).
- Accepts and stores an Instagram ID.
- Validates Gmail addresses.
- Sends a formatted email containing the user's profile details.

## Requirements
Ensure you have the following installed before running the script:
- Python 3.x
- `re` (Regular Expression module, built-in)
- `smtplib` (SMTP library, built-in)
- `email` (Built-in email handling module)

## Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/UserProfileValidatorAndEmailSender.git
   ```
2. Navigate to the project folder:
   ```sh
   cd UserProfileValidatorAndEmailSender
   ```
3. Open the script and replace the sender email and password:
   ```python
   server.login("your-email@gmail.com", "your-app-password")
   ```
   **Note:** It is recommended to use an [App Password](https://myaccount.google.com/apppasswords) instead of your actual password.

## Usage
1. Run the script:
   ```sh
   python script.py
   ```
2. Follow the prompts to enter:
   - Mobile Number (Format: `678-123-4567`)
   - Instagram ID
   - Email (Only `@gmail.com` addresses are accepted)
3. The script will validate inputs and send an email containing your profile details.

## Notes
- Ensure "Less Secure Apps" is enabled in your Gmail settings or use an App Password.
- The script does not handle errors related to incorrect SMTP configurations, so ensure your email credentials are correct.

## License
This project is licensed under the MIT License.

## Author
K Shashi Kumar

