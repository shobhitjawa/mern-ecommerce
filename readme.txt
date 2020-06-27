So the Project Starts with all the products displayed in the home screen  when react starts --> localhost:3000/
localhost:3000/->home screen

then comes the admin --> shobhitjawa60@gmail.com
only with this id new products can be added.

The project also gets a payment portal or gateway using paypal.

localhost:3000/signin is page where we can sign in and visit our home screen with login credentials.

we get the bearer token by backend using jwt(json-web-token)

used cookies for local storage .

Project also contains search and filter functionality which help user to get products as they want .

These component work on these routes --

      <Route path="/orders" component={OrdersScreen} /> 
            <Route path="/payment" component={PaymentScreen} />
            <Route path="/placeorder" component={PlaceOrderScreen} />
            <Route path="/signin" component={SigninScreen} />
            <Route path="/register" component={RegisterScreen} />
            <Route path="/product/:id" component={ProductScreen} />
            <Route path="/cart/:id?" component={CartScreen} />
            <Route path="/category/:id" component={HomeScreen} />
            <Route path="/" exact={true} component={HomeScreen} />
            <Route path="/profile" component={ProfileScreen} />
            <Route path="/order/:id" component={OrderScreen} />
            <Route path="/products" component={ProductsScreen} />
            <Route path="/shipping" component={ShippingScreen} /

whenever we visit or hit one specific route we get that component working for that route.

Backend is simple and plain working as same as given in node poc just slight changes on products fields.

all the css is in the index.css file because firstly i created a template and then i use html in 
jsx for home screen component.

Key technologies used..
1.React redux -->Major role was of redux as store in react gets complicated so usage of redux 
made project go on with ease.
2.React Hooks -->basics of this is used in page useEffect() as used and usestate no advance feature
of hooks were used.
3.Axios ->mainly used to integrate backend with frontend.  

To Run the project..
1.Open terminal in backend folder
2.run -->npm install  (will install all packages required) 
3.Open terminal in frontend folder
4.run -->npm install  (will install all packages required)
You are ready to go.

if there is an error please update the specified package to latest version.