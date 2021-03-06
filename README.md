# Woocommerce New Order Notification Plugin

Woocommerce custom order page for showing a popup notification with sound when a new order received. 

Usage: 

- Download the current version from release folder and upload it to wp-content/plugins using FTP or using Admin Panel -> Plugins -> Add New -> Upload Plugin, then extract there.

or

- Download: https://wordpress.org/plugins/new-order-notification-for-woocommerce/

or

- Wordpress Admin Panel -> Plugins -> Add New -> Search -> "New Order Notification for Woocommerce" -> Install -> Activate

---

Version 1.0.0:

- New Order Notification Popup with Sound effect in a custom order page at admin panel.
- Settings for New Order Notification Popup strings, refresh time of order controller and music file url.

Version 1.0.1:

- Small bug fixes.
- CSS additions.
- README is more detailed now.

Version 1.0.2:

- Settings field for selection of order statuses that the plugin will notify.
- CSS fixes.
- Small bug fixes.

Version 1.0.3:

- "Alert only for orders that contain specific products" option is added.
- You may enter the product ids one by one from the related settings field.
- Small bug and CSS fixes.

Version 1.1.0:

- Reported bug fixed for WooCommerce Shops that have not received any (0) or enough (<10) orders yet.
- An information message is added for WooCommerce Shops that have not received any orders.
- Auto refresh with every 5 seconds to detect the first order of a very new WooCommerce shop.

Version 1.1.1:

- Separate tab (submenu) for settings page.
- Access control changes: Shop manager and Administrator can access the New Order Notification page.
- Access control changes: Only Administrator can access the Settings page.
- Warning message if WooCommerce plugin is not installed or activated.

Version 1.1.2:

- Better CSS for Settings page.
- Small bug fixes, speed optimizations.

Version 1.2.0:

- Sound playing problem when another tab is focused on the browser is solved.
- Audio loop feature is added.
- Better product ID selection with dropdown options.
- Improvement of order status selection in Settings to show all order statuses including custom statuses.
- Time zone problem of order date is solved.
- Better format for order date.
- Better CSS for Settings page.

Version 1.2.1:

- Bug fixes for reported PHP errors.
- New Order Notifciation page is now accessable for roles: Super Admin, Admin, Editor, Author and Shop Manager.

---

Next release:

- Sound playing problem when another tab is focused on the browser (Wordpress Support)
- Loop feature for the audio play (Wordpress Support)
- Improvement of order status selection in settings to show all order statuses including custom ones (Mail Support)
- Settings for formatting the view of order date and time zone selection (Wordpress Support)
- Better product ID selection with dropdown options.

To-Do: 
- Usage instructions like browser and device type, browser settings for autoplay (Wordpress Support)
- A video tutorial for example usage.
- Order notification popup title with order status (New Order -> Pending/On-Hold/Processing..)
- Order notification popup second acknowledge button to provide order status change functionality
- Better UI/UX for custom order page and new order popup
- Audio file upload button instead of link field.
- Remove refresh feature, use hook to detect new order.
- Notify admin on every page of admin panel.
- Detect all new orders and show as a list with multiple confirm buttons.
- Show order statuses with selected Woocommerce language and provide translation feature.
