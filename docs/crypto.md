# crypto: Secure hashes

Secure hash and message digest functions.

Provides following functions:

-   `md5(data)`,
-   `sha1(data)`,
-   `sha256(data)`,
-   `sha384(data)`,
-   `sha512(data)`.

Each function expects `data` to be `TEXT` or `BLOB`. Returns a `BLOB` hash. Use the `hex()` function to convert it to hex string.

[Download](https://github.com/nalgeon/sqlean/releases/latest)

## Usage

```
sqlite> select hex(md5('abc'));
900150983CD24FB0D6963F7D28E17F72
```
