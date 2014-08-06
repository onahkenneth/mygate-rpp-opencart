mygate-rpp-opencart
===================

Extension adds support for "MyGate My Virtual" South African payment integration. 

Supported OpenCart Versions:
================
All 1.5.x versions


What does it do:
================
The checkout button will redirect the customer to the MyGate payment gateway site.
At this time, customer enters the payment details and payment is validated.
Once payment is completed, the page will redirect back to your site to complete the order.


Requirements:
==============
* You will of course need to have a "MyGate" account.
* You will be issued a MyGate Merchant & Application ID when you open an account


Main features:
==============
* Return click processing Supported with details
* Custom final order status

Note:  Compatible with OpenCart 1.4.x and 1.5.x

In order to get a MyGate Merchant Account please browse to "https://www.mygate.co.za"


Installation:

1. Upload the contents of this module to the root of your OpenCart installation. Make sure you adhere to the directory structure.
2. Go to http://www.yourdomain.com/{admin} - whatever admin is name
3. Log in with Admin credentials
4. Go to Extensions >> Payments.  
5. Click "Install" next to "MyGate" extension to install the extension
6. Click Edit.  
7. Enter your MyGate Merchant ID.
8. Also enter MyGate Application ID.
9. Set the Status to enabled.
10. Set the Completion Status to the status that you require the order to be set to if the payment succeeds.
11. Set the Denied Status to the status that you require the order to be set to if the payment is declined.
12. Set the Failed Status to the status that you require the order to be set to if the payment fails.
13. Once you have completed your testing simply enter MyGate Live Credentials instead of Test Credentials.
