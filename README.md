# Web Scraping

This project is part of the software development course at Prodigy Infotech. It is a web scraping program that extracts product information, such as names, prices, and ratings, from an online e-commerce website and stores the data in a CSV file.

## Features

- Extracts product names, prices, and ratings from an e-commerce website
- Stores the extracted data in a structured CSV file

## Usage

1. Clone the repository.
2. Run the script to start scraping data from the specified website.

## Technologies

- Java
- Jsoup
- Apache Commons CSV

## How to Run

1. Ensure you have Java installed.
2. Add the required libraries (Jsoup and Apache Commons CSV) to your project.
3. Compile and run the script:
    ```bash
    javac -cp lib/jsoup-1.14.3.jar:lib/commons-csv-1.8.jar src/Main.java -d build
    cd build
    java -cp .:../lib/jsoup-1.14.3.jar:../lib/commons-csv-1.8.jar Main
    ```

## Example

The program extracts product information from an e-commerce website, parses the data to extract product names, prices, and ratings, and saves the results into a CSV file named `ebay_products.csv`.

## License

This project is licensed under the MIT License.
