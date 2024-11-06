
# GadgetHaven - E-commerce Platform

[Live Website Link](https://gadget-heaven-react.netlify.app/) 

[Requirement Document Link](/public/requirements.pdf)

GadgetHaven is a responsive e-commerce platform for gadget shopping. It includes intuitive navigation, categorized products, detailed product pages, a shopping cart, and a wishlist. Users can filter and sort items, with persistent data management via LocalStorage.

## Key Features

1. **Navigation**: Easy access to categories, cart, and wishlist via a structured navigation bar.
2. **Cart & Wishlist**: Add gadgets to a cart or wishlist (items added only once to the wishlist).
3. **Product Details**: Dedicated page with gadget info, “Add to Cart,” and wishlist options.
4. **Sort & Filter**: Filter by categories and sort cart items by descending price.
5. **Data Persistence**: Cart and wishlist are saved in LocalStorage for reload continuity.

## React Fundamentals Used

- **useState**: For managing state such as cart and wishlist items.
- **useEffect**: For updating the cart/wishlist when the data changes.
- **React Router**: For navigating between product pages, cart, and wishlist.
- **LocalStorage**: Used for data persistence, ensuring cart and wishlist items remain intact upon page refresh.
