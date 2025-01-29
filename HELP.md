### Online food order booking system

### **Features to Build**
1. **Restaurant Management**:
    - Add, update, and delete restaurants.
    - Each restaurant can have multiple products (menu items).

2. **Menu Management**:
    - Add, update, and delete menu items for each restaurant.
    - Allow fetching menu for a specific restaurant.

3. **Order Management**:
    - Customers can place orders for one or more items from a specific restaurant.
    - Support `order tracking` (e.g., Pending, Confirmed, Delivered, Cancelled).
    - Calculate the total order amount.

4. **Pagination, Searching, and Sorting**:
    - Fetch restaurants, menu items, and orders with pagination.
    - Enable searching by restaurant name or menu item name.
    - Enable sorting by price, rating, or order status.

5. **CRON Jobs**:
    - Automatically cancel **abandoned orders** (e.g., not confirmed within X minutes).

6. **Calling 3rd Party APIs**:
    - Simulate **payment gateway integration** for order payments.
    - Allow restaurants to be notified externally (via webhooks) for new orders.

7. **Admin/Restaurant-Specific Features**:
    - Each restaurant can manage its own menu and view its orders.
    - Orders can have callbacks to update inventory automatically.
