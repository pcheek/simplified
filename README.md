# Simplified

This is an example application to help get you started accepting payments with Simplify Commerce by MasterCard.

It was created with open-source tools, and provides a barebones implementation of the Simplify Commerce PHP SDK and SimplifyJS for tokenization. Using built in development tools, and reference matierial you can begin accepting payments using Simplify Commerce by following the three step setup guide.

## Documentation

1. Copy your API keys from Simplify.com (Make sure you use your sandbox keys!)
2. Open index.php in any text editor.
3. Paste the keys between the quotes:

```php
<?php
$simplified = array(
     'publicKey' => 'YOUR_PUBLIC_KEY',
     'privateKey' => 'YOUR_PRIVATE_KEY'
);
// That's it, Simplify, simplified.
```
## License
This software is Open Source Software, released under the BSD 3-Clause license. See [LICENSE.md](LICENSE.md) for more info.