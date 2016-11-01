# sheetgen

![https://badge.fury.io/py/sheetgen](http://badge.fury.io/py/sheetgen.png)

Do you own a retail store or a warehose? Do you need an easy way of printing sheets with barcodes? This tool will help you with that!

## What do we use sheetgen for?

Most of the products in our shop (FooBar) already have EAN barcodes on them, but there are some products, i.e. tee, coffe or spoons, that do not. We simply generate sheets for them, cut them in smaller pieces and laminate them, then place close to the cash register.

![The codes in our kiosk](https://files.kjagiello.com/3d39696c_codes.png)

## Quickstart guide

Install using pip:

```bash
pip install sheetgen
```

Create a text file containing product names and their respective EAN codes.

```
7310865000545	Milk
6410600109210	Cup of coffee
7392678922016	Cutlery
```

Run sheetgen and generate a PDF codesheet:

```bash
sheetgen codesheet.pdf < products.txt
```
