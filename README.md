# Flask E-commerce

### Project Overview
This project is a simple e-commerce website built using the Flask framework. It includes user authentication, product browsing, and payment gateway integration with Instamojo. The application is hosted on Heroku for easy access and testing.

### Project Name
Flask E-commerce

### Description
The Flask E-commerce project is designed to create a functional online store where users can sign up, log in, browse products, and make purchases. The payment gateway integration allows for secure transactions. The application is deployed on Heroku to demonstrate its functionality.

### Features
- User Signup/Login
- Product Browsing
- Shopping Cart
- Payment Integration using Instamojo
- Secure Payment Transactions

### Pre-requisites
- Python 3.6.4
- pip 9.0.1
- Flask version: 0.12.2
- SQLite

### Setup and Installation

1. **Set Up a Virtual Environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

2. **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Configure Environment Variables:**
    Create a `.env` file in the root directory and add your Instamojo API credentials:
    ```plaintext
    INSTAMOJO_API_KEY=your_api_key
    INSTAMOJO_AUTH_TOKEN=your_auth_token
    ```

4. **Run the Application:**
    ```bash
    flask run
    ```
    The application will be available at [http://127.0.0.1:5000](http://127.0.0.1:5000).

### Technology Stack
- **Backend**: Flask (Python)
- **Database**: SQLite
- **Payment Gateway**: Instamojo
- **Deployment**: Heroku

### Project Structure
- `app/` - Contains the main application code.
- `templates/` - HTML templates for the application.
- `static/` - Static files such as CSS, JavaScript, and images.
- `config.py` - Configuration file for the application.
- `requirements.txt` - List of dependencies.
- `Procfile` - Configuration file for Heroku deployment.
- `runtime.txt` - Specifies the Python version for Heroku.

### License
This project is licensed under the MIT License.

### Live Demo
You can test the live application hosted on Heroku using the following URL: [Heroku App](https://your-heroku-app-url.herokuapp.com)

### Contributors
- Sahdev Saini
