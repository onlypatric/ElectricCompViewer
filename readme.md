# Electric Symbol Explorer

Electric Symbol Explorer is a PyQt6-based application designed for exploring and managing electric symbols along with their descriptions. The application supports various functionalities, including adding, removing, searching, exporting, and loading symbols.

## Features

- **Symbol Management:** Easily add and remove electric symbols.
- **Export and Import:** Save and load symbols in different formats, such as JSON, CSV, and Excel.
- **Multiple Windows:** Open multiple instances of the application with distinct symbol sets.

## Getting Started

Ensure you have the required dependencies installed before running the application. You can install these dependencies using the appropriate package manager.

Run the application by executing the main script file.

## Usage

Run the application with the following commands (CMD or Shell):

- install python 3 through [Python Official Website](httpshttps://www.python.org/downloads/release/python-3122/)
- download required packages:

  ```shell
  pip install PyQt6
  pip install openpyxl
  ```

- run the application (ensure your command prompt is in the project directory)

  ```shell
  python main.py
  ```

1. **Symbol Management:**
   - Add a symbol by clicking the "Add Symbol" button.
   - Remove a symbol by selecting it and clicking the "Remove Symbol" button.
   - Search for symbols using the search bar.

2. **Export and Import:**
   - Save symbols in JSON, CSV, or Excel format using the "Save as" button.
   - Load symbols from a file using the "Load" button.

3. **Multiple Windows:**
   - Create a new window from the "File" menu to manage separate sets of symbols.

## Application Structure

- **`main.py`:** Contains the main application logic and UI setup.
- **`ElectricSymbolViewer`:** QWidget for symbol exploration and management.
- **`AddSymbolDialog`:** QDialog for adding new symbols.
- **`MainWindow`:** QMainWindow for the main application window.

## Contribution

If you encounter any issues or have suggestions for improvement, feel free to open an issue or create a pull request.

## License

This project is licensed under the [MIT License](https://it.wikipedia.org/wiki/Licenza_MIT).

Thank you for using Electric Symbol Explorer!

## Future updates

In the following updates there might be a release of images in the symbol table, this way you will be able to visualize better symbols
