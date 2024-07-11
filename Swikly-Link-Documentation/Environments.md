# Sandbox and production environments

Swikly's Transaction Link redirects the end-user to Swikly's checkout. Swikly's checkout will then process all the GET request parameters set in the link and display the necessary transaction information to the end-user as well as the credit card form for him to complete the transaction.

- ## Sandbox

The sandbox environment enables you to test your links and application integration. All transactions made and accepted in sandbox mode are for testing purpose only. To complete a  transaction from end to end in sandbox mode, you have to use a **[test credit card](/Swikly-Link-Documentation/Test-Credit-Cards)**.

| Environment  | URL  | Usage |
|---|---| --- |
| Sandbox | [https://app.sandbox.swikly.com](https://app.sandbox.swikly.com) | Test |
| Sandbox Checkout Root | [https://app.sandbox.swikly.com/fr/checkout](https://app.sandbox.swikly.com/fr/checkout)  | Test |

- ## Production 

The production environment enables you to go live with your links and application integration. All transactions made and accepted in production are real transactions. To complete a transaction in production mode, you have to use a **real credit card**. 

| Environment  | URL | Usage |
|---|---| --- |
| Production | [https://app.v2.swikly.com](https://app.v2.swikly.com) | Live |
| Production Checkout Root | [https://app.v2.swikly.com/fr/checkout](https://app.v2.swikly.com/fr/checkout) | Live |
