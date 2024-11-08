
# eCommerce Website

This eCommerce website is built with **Ruby on Rails 7** and provides essential features for online shopping, such as product management, user authentication, and a responsive UI. The project leverages Rails' powerful capabilities alongside modern tools like Turbo and Tailwind CSS for a seamless, single-page application (SPA) experience.

**Screenshots of website**
![Screenshot from 2024-10-27 19-40-31](https://github.com/user-attachments/assets/f54e5e80-ee56-44c8-81cf-aa4b336964eb)
![Screenshot from 2024-10-27 19-40-22](https://github.com/user-attachments/assets/916ef034-f0f5-4edc-9373-a815bab58edc)
![Screenshot from 2024-10-27 19-40-08](https://github.com/user-attachments/assets/b799d3ac-1e4e-4cc1-a909-e4c9cf6918ce)

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Features
- **User Authentication**: Secure user login, registration, and management via Devise.
- **Product Listings**: Browse and manage product catalog with dynamic, user-friendly listings.
- **Responsive Design**: Tailwind CSS for consistent, responsive layouts across devices.
- **Single-Page Experience**: Turbo Rails for fast, single-page-like interactions.
- **Database Management**: SQLite database for lightweight data storage (development only).

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/princekumarg12/ecommerce-website.git
   cd ecommerce-website
   ```

2. **Install Dependencies**:
   ```bash
   bundle install
   ```

3. **Database Setup**:
   Create and migrate the database:
   ```bash
   rails db:create
   rails db:migrate
   ```

4. **Start the Server**:
   ```bash
   rails server
   ```

5. **Access the Application**:
   Open your browser and navigate to `http://localhost:3000`.

## Usage
This application can be used as a base for building an eCommerce platform. Add and manage products, handle user authentication, and customize it for your specific needs.

## Dependencies
The following are the major dependencies used in this project:

- **Rails 8.0**: Core framework for building the application.
- **SQLite3**: Development database.
- **Puma**: Web server for handling requests.
- **Turbo-Rails & Stimulus**: Hotwire tools for SPA-like interactions.
- **Tailwind CSS**: CSS framework for a modern, responsive UI.
- **Jbuilder**: JSON builder for API responses.
- **Devise**: User authentication system.
- **Font Awesome**: Icons for enhancing the UI.

### Development & Testing
- **Brakeman**: Security scanner for Rails applications.
- **RuboCop Rails Omokase**: Linter for Rails styling.
- **Better Errors & Web Console**: Enhanced error handling in development.
- **Capybara & Selenium**: For system testing.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## License
This project is licensed under the MIT License.
