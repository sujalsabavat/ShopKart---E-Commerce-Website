# ShopKart---E-Commerce-Website
This project is an eCommerce website built using Django, a powerful and flexible web framework for Python. The website provides a comprehensive online shopping experience, featuring product listings, user authentication, shopping carts, and order management.

![Screenshot 2024-09-09 004244](https://github.com/user-attachments/assets/94fbd9f9-9103-49b6-ac7f-d819aa2f880f)

## Key Features

### Ecommerce Website with User Authentication

- **User Accounts**: Users can register for an account, log in, and manage their personal profiles.
- **Secure Authentication**: Built-in Django authentication system ensures secure user login and session management.
- **Profile Management**: Users can update their personal information and view their order history.
  ![Screenshot 2024-09-09 004400](https://github.com/user-attachments/assets/85f79162-e71a-4fc5-a361-43c4c3351364)


### Guest User Management via Cookies

- **Browse as Guest**: Users can explore the product catalog and add items to their cart without creating an account.
- **Session Management**: Cookies are used to manage guest sessions and persist cart data across page refreshes.
- **Conversion to Registered User**: Option for guests to convert their cart into a registered user’s cart upon registration.

### Payment Integration

- **Seamless Checkout**: Integrated payment gateway allows users to securely pay for their orders.
- **Supported Payment Methods**: Includes major credit/debit cards and other payment options (e.g., Stripe, PayPal).
- **Secure Transactions**: Uses industry-standard encryption to protect payment information.
  ![Screenshot 2024-09-09 004505](https://github.com/user-attachments/assets/cbc8fd20-5952-49b9-9a1c-22e1741b1ccb)


### Order Summary Before Payment

- **Review Order**: Users can review a detailed summary of their order before proceeding to payment.
- **Order Details**: Includes product names, quantities, individual prices, and total cost.
- **Edit Cart**: Option to modify cart contents or cancel the order before finalizing payment.
  ![Screenshot 2024-09-09 004311](https://github.com/user-attachments/assets/cf6e7197-4def-408e-b455-4c22129e9e5b)


## Technologies Used

- **Django**: The primary web framework used to build the application, providing a robust backend.
- **SQLite**: Default database for development; can be replaced with PostgreSQL or MySQL for production environments.
- **Stripe/PayPal**: Integrated payment gateways (or specify the one used) for handling transactions.
- **Bootstrap**: Frontend framework used for designing a responsive and modern user interface.
- **JavaScript**: Enhances user interactions and performs client-side validations.

## Installation and Setup

Follow these steps to set up the project on your local machine:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/ecommerce-django.git
   cd ecommerce-django

