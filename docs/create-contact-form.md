# Create contact form

## Shortcode

You can add the contact form component to any page using the ```[hypermarket-plus-contact]``` shortcode. Also, it is possible to pass the following attributes to the shortcode to create contact form elements.

```php
address_1
address_2
phone
mobile
email
hours
```

A full shortcode could look like:

```php
[hypermarket-plus-contact address_1="45 Park Avenue, Apt. 303" address_2="New York, NY 10016, USA" phone="001 (917) 555-4836" mobile="001 (800) 333-6578" email="info@example.com" hours="10am - 8pm, Mn - St"]
```

![Generate a contact form shortcode](img/generate-contact-form-shortcode.gif)

Alternatively, locate an additional button in TinyMCE’s toolbar – place the cursor where the contact form tooltip will appear, then click the **contact form button**.

After clicking the interface button, a modal dialog with a few options to config will appear, optionally fill the blanks and hit the **OK** button to generate a new contact form shortcode.