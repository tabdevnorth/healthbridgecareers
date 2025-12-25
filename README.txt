Healthbridge Careers — Site package
Included files:
- home.html
- contact.html
- checkout.html
- css/styles.css
- assets/logo.svg

How to use:
1. Open the folder in Visual Studio Code.
2. Replace placeholder emails and PayPal business value in checkout.html and contact form endpoint in contact.html.
3. If you want Stripe Checkout:
   - You need a simple server endpoint that creates a Stripe Checkout Session with the price and returns the session id, then redirect to stripe.redirectToCheckout({ sessionId }).
   - See Stripe docs: https://stripe.com/docs/checkout

Deploying to Netfirms:
- Purchase a hosting plan if you don't have one.
- Upload the files (home.html as your root) via Netfirms File Manager or FTP.
- Point your domain to the hosting account (Netfirms offers an easy connect since your domain is already there).

Logo:
- assets/logo.svg is a simple vector logo. Replace if you want a different style.

Customization:
- Edit css/styles.css to change colors, spacing, fonts.
- For production, consider minifying CSS and enabling HTTPS on your hosting.

Contact form:
- The contact form currently calls Formspree. Replace the fetch URL with your own backend or your Formspree form ID.

If you want, I can:
- Create a ZIP with these files (already provided).
- Provide an optional simple Node/Express server example for Stripe Checkout integration.
