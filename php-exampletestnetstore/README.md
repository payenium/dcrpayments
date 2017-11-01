php-exampletestnetstore
====

This is a simple/basic mock up of a store running on testnet.  It is intended
to demonstrate an end-to-end example of integrating Decred payments.

Requires:

- [php-addressgen](https://github.com/dcrpayments/php-addressgen)
- pdo_sqlite module
- An extended public key generated by [epkgen](https://github.com/dcrpayments/epkgen)

# Running

- ```php -S localhost:8000```

# Status

- HD Coin Type change caveat from php-addressgen applies.
compensate for that.  See https://github.com/decred/dcrwallet/pull/976 for
more details.  **THIS MEANS ADDRESSES GENERATED BY THIS LIBRARY WILL BE
CONSIDERED LEGACY SOON AND SHOULD NOT BE USED IN PRODUCTION.**

- Need to address configuration options and security considerations.  ** NOT
  FOR PRODUCTION USE **