#The Box Office
The Box Office allows you to check in patrons as they arrive and sell 
additional tickets and concessions.

## Credit Card Scanners

### Phone/Tablet Scanner
The Box Office works with the [Collect for Stripe](https://collectforstripe.com/) app 
and the [BBPOS Chipper card reader](https://dashboard.stripe.com/terminal/shop).

The Bluetooth reader supports newer chip cards and paying via card tap, and cellphone. It is
the recommended way to take credit cards.

* [iPhone App](https://itunes.apple.com/us/app/collect-for-stripe-instant/id1145604255?ls=1&mt=8)
* [Android App](https://play.google.com/store/apps/details?id=com.odd.collectforstripe)

You'll need to connect the Collect for Stripe app with your Stripe account before you can take tickets. 
 

### USB Scanner
The USB scanner works with pretty much any computer and a web browser. It is, however, a less secure way to take 
tickets. We'd recommend moving to the Chipper card reader.

## Getting Started

### Web and Mobile

Login to BuyPlayTix. Then click on Menu->Reservations. Choose the show date you want to take
tickets for and then click the Box Office icon.

![](img/boxoffice-icon.png "Icon")


## The Register Tab

The Register is the first tab and contains buttons with each item that
you have setup to sell. There will be one button for each ticket price. You should see
a button for concessions. There is a button for donations, and finally a custom button that can
catch any oddities that may come up in a Box Office. And for some reason they
always do.
 
### Selling Tickets

Selling tickets works the same way whether on mobile or the web.
 
First click the ticket price you want to sell.
 
![](img/bo2.png "Ticket Button")

Next enter your quantity. It works like a calculator. Press or click the numbers to 
 get the quantity you want to sell.
 
![](img/bo3.png "Quantity")

Then enter the payment type. If you want to sell more than one item in a single transaction
you can click 'Add to Cart'. Cash and Checks will both go through immediately. Credit
will prompt you for a credit card transaction. Pass will prompt you for a season
passcode.
 
![](img/bo4.png "Quantity")
 
#### Using the Mobile Scanner

To enable the mobile scanner you'll need to first enable Collect4Stripe, but you only need
 to do this once. First click on the menu in the upper left hand corner of the box office (next to the
 date):

![](img/collect4stripe-menu.png "Top Menu")

Then toggle the Collect4Stripe setting:

![](img/collect4stripe-menubody.png "Collec4Stripe Toggle")

Now when you click on the Credit option it will hand you off to the Collect for Stripe app. Once the charge
is complete you'll be returned to the Box Office.


#### Using the USB Scanner
When you click the 'Credit' button on the website you'll see the manual credit card
entry page. 

![](img/manualcredit.png "Manual Credit")

*Fear not!* You don't have to enter all that info. Just scan the card with the USB
scanner and it will automatically fill in the fields and click the Ok button for you.

And if the usb scanner doesn't work you can still enter the credit card information by hand.
 **grumble**, **grumble**

### Concessions

#### Adding Concessions

Concessions can be added by going to Menu->Concessions->Add Concession. From the mobile
app you can click the menu button.

![](img/menubutton.png "Menu Button")

Then click 'Add Concessions'

![](img/add-concession.png "Add Concessions")

Each concession will get their own button on the Box Office Screen. In this example
we've added Water and Popcorn Concessions.

![](img/bo6.png "Concessions")

#### Selling Concessions
Concessions are sold exactly the same way as tickets. Click on the Concession, then 
 enter the quantity. You can add the concessions to a shopping cart or process them
 right away.

### Donations
Donations work much the same way as tickets. Frequently if you want to sell an $18
ticket and the customer only has a $20 bill you can add one $18 ticket to the cart
and then add a $2 donation.

**Be Careful**: The donation button takes you to an amount screen, not a quantity screen.

Enter the amount of the donation in dollars. Donations also have an optional space for
a patron name (in case you want to send them a thank-you later).


### Custom Priced Tickets

There is also a custom price button. This gives you the ability to accept all the
oddities that come up with running a box office without changing your entire ticketing
structure.

**Be Careful**: The custom price button asks you for both a quantity and a price. 

So for example: at the first prompt you would enter 2 for the quantity and then
 at the second prompt enter $5. Which would add 2 $5 tickets to your shopping cart.
 
Custom Prices also require that you enter a Name/Comment. This will help you remember *why*
you granted that custom price when it comes time to reconcile
your reports.

## The Sales Tab
The sales tab has a list of all sales for the evening. If you make an erroneous cash 
or check sale you can delete it by clicking the delete button. 

![](img/bo7.png "Delete Button")
 
If you have sold an item using a credit card you'll have to process a refund. Credit
card transactions have a gear next ot them. Click on the gear.

![](img/bo8.png "Gear Button")

And click the red Refund button on the page you're taken to.
 

## The Reservations Tab

### Picking up Tickets

Picking up tickets is just a way of keeping track of which of your prepaid patrons
have arrived.

#### Scanning Tickets

Scanning tickets works best on mobile, but could work with a webcam.  For  users who have printed the tickets
or have them on their cell phone  have the customer bring up the ticket. Then click
the Scan button in the app. 

![](img/scan-top.png "Scan")

If you're holding your phone in portrait mode you might not see the Scan icon and might have to choose it from
the menu. First click on the menu in the top left corner:

![](img/collect4stripe-menu.png "Top Menu")

Then click on Scan Barcode in the menu:

![](img/scan-menu.png "Scan")

A dialog will come up with a view from your camera. Focus on the 2d barcode on the customers ticket and
it should automatically pickup the tickets and return you to the Register.

### Manual Pickup

If you're like me, scanning each individual ticket is time consuming and doesn't move
 fast enough. You can also manually enter people as the arrive on the Reservations tab.
Simply choose the number of tickets picked up. You don't have to pickup all
the tickets at once, as you'll inevitably have the parties that have arrived in more
than one car or pedicab.
  
![](img/partial-pickup.png "Partial Pickup")
  
Once all the tickets have been picked up, the free ticket button will go away and the
line will be crossed out.
   
![](img/full-pickup.png "Full Pickup")

### Freeing Tickets

So what happens if you need to free up all reservations 10 minutes before showtime, or
Bob decided he didn't want to see this show and so the party that arrived via pedicab
has an extra ticket? No sweat, you can free those tickets so they can be resold.

Click on the free icon (butterflies like to be free).

![](img/free.png "Free")

You'll be prompted to be sure you want to do that. 


## What if something goes wrong?
First try clicking the refresh button in your browser. If things don't get better try restarting your device, or
sending an email to <a href="mailto:support@buyplaytix.com">support@buyplaytix.com</a>





