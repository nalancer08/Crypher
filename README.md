# Crypher
Crypher it's a library to manage encryption parameters with JavaScript, Java, PHP and Swift


This library it's so simle to use:

## PHP

```
include "../crypher.inc.php";
$crypher = new Crypher();
$crypher->setPassphrase("pass_salt");
```

### Encrypt

```
$pass = $crypher->encrypt($value_to_be_encrypt);
```

### Decrypt

```
$pass = $crypher->decrypt($value_to_be_decrypt);
```