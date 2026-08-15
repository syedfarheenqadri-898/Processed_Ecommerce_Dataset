# Processed E-commerce Dataset

## Objective

The objective of this project is to process and combine e-commerce data using Python and Pandas. The Orders, Customers, and Products datasets were combined to create a clean and meaningful processed dataset.

## Datasets Used

* **Orders** — Contains order details such as Order ID, Order Date, Customer ID, Product ID, Quantity, Payment Method, and Order Status.
* **Customers** — Contains customer details such as Customer ID, Customer Name, City, Region, and Membership Type.
* **Products** — Contains product details such as Product ID, Product Name, Category, Unit Price, and Brand.

## Pandas Operations Used

The following Pandas operations were used:

* `read_csv()` — To load the CSV datasets.
* `merge()` — To combine Orders with Customers and Products using common ID columns.
* `concat()` — To demonstrate combining DataFrames.
* `apply()` — To create the `Total_Amount` column.
* `to_datetime()` — To convert the Order Date into DateTime format.
* DateTime operations — To extract the month, day, and day of the week.
* Column selection and organization — To create a clean final DataFrame.
* `to_csv()` — To export the processed dataset.

## Output File

The final processed dataset is:

`Day9_Processed_Ecommerce_Dataset.csv`

## Conclusion

The three e-commerce datasets were successfully processed and combined using Pandas. The final dataset contains order, customer, and product information along with calculated total amounts and useful date-related columns. The processed dataset was exported as a CSV file for further analysis and uploaded to GitHub.

