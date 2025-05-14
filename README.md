# GoHighLevel Form Tracking GTM DataLayer

## How to use 
1. In Google Tag Manager, create a new tag as a custom HTML tag.
2. Inside the tag, paste the entire code from the `gohighlevel-gtm.html` file provided in this repository.
3. Set the trigger to fire on all page views.

Once you've configured this setup, you'll begin receiving Google Tag Manager dataLayer events as `ghl_form_submit` and `ghl_booking_complete` with form input values (name, email, etc)
