# EX01 Developing a Simple Webserver
## Date: 13-11-2024

## AIM:
To develop a simple webserver to serve html pages and display the configuration details of laptop.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Serving the HTML pages.

### Step 5:
Testing the webserver.

## PROGRAM:
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Laptop Configuration</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color:gainsboro;
            margin: 0;
            padding: 0;
        }

        h1 {
            text-align: center;
            margin-top: 20px;
        }

        table {
            width: 70%;
            margin: 50px auto;
            border-collapse: collapse;
            background-color: #fff;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }

        th, td {
            padding: 15px;
            text-align: left;
            border-bottom: 1px solid #ddd;
        }

        th {
            background-color:gray;
            color: white;
        }

        tr:hover {
            background-color: #f1f1f1;
        }

        td {
            color: #333;
        }

        .highlight {
            background-color: #e0f7fa;
        }
    </style>
</head>
<body>

<h1>VARSHA K</h1>
<h1>212223220122</h1>
<h1>Laptop Configuration</h1>

<table>
    <tr>
        <th>Component</th>
        <th>Details</th>
    </tr>
    <tr>
        <td>Model</td>
        <td>Lenovo Thinkpad</td>
    </tr>
    <tr>
        <td>Processor</td>
        <td>12th Gen Intel(R) Core(TM) i5-1235U   1.30 GHz</td>
    </tr>
    <tr>
        <td>RAM</td>
        <td>16 GB DDR4</td>
    </tr>
    <tr>
        <td>Storage</td>
        <td>512 GB SSD</td>
    </tr>
    <tr>
        <td>Graphics</td>
        <td>Intel Iris XE</td>
    </tr>
    <tr>
        <td>Display</td>
        <td>15.6" 2K</td>
    </tr>
    <tr>
        <td>Battery</td>
        <td>86 Whr</td>
    </tr>
</table>

</body>
</html>
"""

```

## OUTPUT:
![Screenshot (70)](https://github.com/user-attachments/assets/18c21e5e-0949-4b7e-a2ac-e53e2c354622)
![Screenshot (71)](https://github.com/user-attachments/assets/e3ef47a2-c467-4b8d-b604-96f71f0828c1)


## RESULT:
The program for implementing simple webserver is executed successfully.
