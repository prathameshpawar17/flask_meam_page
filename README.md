<div id="top"></div>

# MEME_PAGE

<details>
<summary>Table_of_contents</summary>

-   [Overview](#overview)
-   [Technology Stack](#technology-stack)
-   [Getting Started](#getting-started)
-   [Features](#features)
-   [Screenshots](#screenshots)

</details>

## Overview
This is a meme page created with Flask. It utilizes the Reddit API to interact with Reddit and retrieve meme images. Additionally, it features user authentication using a MySQL database, allowing users to register, log in, and log out. The page refreshes to display a new meme every 25 seconds.

## Technology Stack

- Flask
- MySQL
- HTML
- CSS
- JS

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/prathameshpawar17/flask_meam_page.git
   cd meme_page
   ```

2. Install Flask in that directory
   ```bash
   pip install flask
   ```

3. Install flask_mysqldb in that directory
   ```bash
   pip install flask_mysqldb
   ```

4. Install requests in that directory
   ```bash
   pip install requests
   ```

5. Update the config in app.py (you can find your details in MySQL workbench)

    ```python
    app.config['MYSQL_HOST'] = 'YOUR-HOST-NAME'
    app.config['MYSQL_USER'] = 'YOUR-USER-NAME'
    app.config['MYSQL_PASSWORD'] = 'YOUR-PASSWORD'
    app.config['MYSQL_DB'] = 'YOUR-DB-NAME'
    ```

6. Run XAMPP server
    - open XAMPP
    - Click on Apache - start

7. Run the flask file
    ```bash
    python app.py
    ```

## Features

- A new meme generates for every 25 seconds
- Users can register and login to their account

## Screenshots

<table>
    <tr>
        <th>Desktop View</th>
    </tr>
    <tr>
      <td style="text-align: left;font-weight: bold;">
      Home Page
      </td>
    </tr>
    <tr>
        <td>
            <img src="" width="95%" title="Desktop view - Home"/>
        </td>
    </tr>
    <tr>
      <td style="text-align: left;font-weight: bold;">
      Login Page
      </td>
    </tr>
    <tr>
        <td>
            <img src="" width="100%" title="Desktop view - login"/>
        </td>
    </tr>
    <tr>
      <td style="text-align: left;font-weight: bold;">
      Registration Page
      </td>
    </tr>
    <tr>
        <td>
            <img src="" width="100%" title="Desktop view - register"/>
        </td>
    </tr>
    <tr>
      <td style="text-align: left;font-weight: bold;">
      After Logged in
      </td>
    </tr>
    <tr>
        <td>
            <img src="" width="100%" title="Desktop view - after logged in"/>
        </td>
    </tr>
</table>

<p align="right"><a href="#top">⬆️ Back to Top</a></p>