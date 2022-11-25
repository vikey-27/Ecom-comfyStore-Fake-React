## Notes


## Work
-Created a Sample Ecom sites (Comfy Store).
-Consist of Home page ,About Page,Products Page which contained the products and checkout Page if the user is logged in.
-The Homepage also contain a featured products list.
-The products list is fetched from API 'https://course-api.com/react-store-products'.
-The Single product list api 'https://course-api.com/react-store-single-product?id='
-The respective product id should be added in the url .
-The products page contain a filter option to filter out the product using price,color,company,free shipping.
-The Single Product page contain add to cart button. The product is added to cart if the product stock is available and respective color is choosen.
-In cart page we can increase or decrease the product or we can remove the product from the list or we can remove the entire product list.
-Also Newsletter form is available, if the user submit the form the data is send to Formspree and the user data is collected.
-For Login Auth0 api is used .
-For payment gateway Stripe api is used(Since indian location has some restriction ,the payment gateway is handled manually,if the user click the pay button ,Payment done message is poped up and redirected to the Homepage).



#### Older React Version

```
"react": "^16.13.1",
"react-dom": "^16.13.1",
"react-scripts": "3.4.3",
```

#### Current React Version

```
"react": "^17.0.1",
"react-dom": "^17.0.1",
"react-scripts": "4.0.0",
```

#### Alternative fix

.env file in the root
FAST_REFRESH=FALSE

