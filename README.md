# Travel Agency Management System

## Introduction
The Travel Agency Management System is a C++ application designed to manage the operations of a travel agency. This system allows for efficient handling of travel trips, user management, and trip management. It interacts with a MySQL database to store and retrieve data.

## Features
- **User Management**: Add, show, find, edit, and delete user information.
- **Trip Management**: Add, edit, and delete travel trips.
- **Database Integration**: Uses MySQL for storing and managing data.
- **Interactive Interface**: Simple text-based interface for easy interaction.

## Installation

### Prerequisites
- MySQL Server
- C++ Compiler (e.g., GCC, Clang)
- MySQL Connector for C++

### Setup
1. **Clone the Repository**:
   ```bash
   git clone [repository-url]
   ```
2. **Set up the MySQL Database**:
   - Create a new database named `cpp_travelagency_db`.
   - Import the provided SQL file to set up tables.

3. **Compile the Source Code**:
   Navigate to the project directory and compile the code:
   ```bash
   g++ -o travelAgency main.cpp -lmysqlcppconn
   ```

## Usage

Run the compiled executable:

```bash
./travelAgency
```

Follow the on-screen prompts to interact with the system.

## Contributing

Contributions to the Travel Agency Management System are welcome. If you have an idea or suggestion, please follow these steps:

1. **Fork the Repository**: Create your own fork of the code.
2. **Create a Feature Branch**: Make your changes in a new git branch.
3. **Submit a Pull Request**: Describe what your code does and why it should be included.

## License

This project is licensed under [LICENSE-NAME]. See the LICENSE file for more details.

## Contact

For any queries or support, please contact [Your Contact Information].
