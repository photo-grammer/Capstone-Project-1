# Inventory Management System

This Python project is an inventory management system that reads data from a text file and performs various operations on the data to prepare it for presentation to managers. It allows users to manage and track shoe inventory, including adding new shoes, viewing details, restocking, searching for specific shoes, calculating the total value per item, and identifying the product with the highest quantity.

## Getting Started

To use this project, follow the steps below:

1. Clone the repository to your local machine or download the source code files.
2. Ensure you have Python 3.x installed on your system.
3. Open the terminal or command prompt and navigate to the project directory.

## Project Structure

- `inventory.py`: This is the main Python script that contains the inventory management system.
- `inventory.txt`: This text file contains the shoe inventory data. Each line represents the data for one shoe.
- `README.md`: This readme file provides information about the project and instructions for using it.

## Usage

1. Open the `inventory.py` file in a text editor or Python IDE of your choice.
2. Run the `inventory.py` script.
3. The program will display a menu with options for different operations.
4. Follow the on-screen prompts and enter the corresponding numbers to perform various tasks.
5. Once you complete an operation, the program will return to the main menu, allowing you to choose another action or exit the program.

### Available Options

1. **Add New Shoe**: This option allows you to capture data about a new shoe and add it to the inventory.
2. **View All Shoes**: This option displays the details of all shoes in the inventory.
3. **Restock Shoes**: This option finds the shoe with the lowest quantity and prompts you to add more shoes to restock it.
4. **Search Shoe**: This option allows you to search for a shoe by its code and displays its details.
5. **Calculate Value per Item**: This option calculates the total value for each shoe in the inventory (value = cost * quantity) and prints the information.
6. **Product with Highest Quantity**: This option determines the product with the highest quantity in the inventory and displays it.
7. **Exit**: This option terminates the program and exits.

## Customization

You can modify the project according to your requirements. Here are some possible modifications:

- Update the `Shoe` class attributes and methods inside the `inventory.py` file to match your specific data structure and business needs.
- Modify the `inventory.txt` file to include your own shoe inventory data.
- Customize the menu options or add additional functionality based on your inventory management requirements.
- Use Python's tabulate module or any other libraries to format the output for better readability.

## Contributing

Contributions to this project are welcome. If you have any ideas, improvements, or bug fixes, please open an issue or submit a pull request on the GitHub repository.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
