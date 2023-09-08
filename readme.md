# React Product Cart


## 🌟Features:
-A simulated product list fetched from a local database.
-Add products to a shopping cart.
-View the content of the cart, including the possibility to remove items.
-A checkout system that calculates the total amount for the cart items.
-Restocking feature to add more items from the database.


## 🔧 Installation:

```bash
npm install react react-dom react-bootstrap axios

```


## 🚀 Usage:
To run this React component, ensure that you have set up a React environment, and simply render the Products component in your desired location.


## 🔎 Code Details:

-The Cart component displays items added to the cart.
-The useDataApi hook provides a reusable method for fetching data from an API endpoint.
-The Products component is the main component that renders the product list, cart, and checkout system.
-Axios is used for HTTP requests.

## ⚠️ Known Issues:

The provided URL http://localhost:1337/api/products assumes the server is running on port 1337. Ensure the server is running and accessible.

## 🤝 Contributions:

Feel free to raise issues or submit pull requests if you find any problems or have suggestions to improve the component.

## 📜 License:

This component is open-sourced under the [MIT License](https://opensource.org/licenses/MIT).
