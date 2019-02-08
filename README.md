# Bamazon-CLI-App

First assignment using MySQL at the Penn Coding Bootcamp!

__Bamazon__ is a simple Amazon clone in the CLI, with a Customer App and a Manager App.


## Customer App

The Customer App will first display the current catalog of available products. Then it will prompt the customer to choose a product:

> + If the input is not a number, or it does not correspond to an existing product ID, an error message will be displayed
> + Once a correct input is typed in, the customer will be asked to select a quantity
> + If the selected quantity is higher than the availability in stock, a courtesy message will be displayed
> + Otherwise, the customer will get an order confirmation (and the stock in the database will be depleted accordingly)

## Manager App

The Manager App will offer four choices:

> 1. View Products for Sale
> 2. View Low Inventory
> 3. Add to Inventory
> 4. Add New Product

The third and fourth choices allow the Manager to update the database, whose updated content is then immediately available in the app for additional actions.

## Demo

[![Screenshot](https://raw.githubusercontent.com/stepicker/Bamazon-MySQL-App/master/screenshot.png)](https://youtu.be/XQNAK5zsTBA)

Here is a [YouTube video](https://youtu.be/S1SrbwpMeeI) I made with a complete demo.

## Under the hood

This CLI app uses the following NPM packages:

> + DotEnv
> + MySQL
> + Inquirer
