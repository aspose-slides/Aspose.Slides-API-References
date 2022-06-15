---
title: DigitalSignature
type: docs
weight: 0
url: /php-java/digitalsignature/
---

# DigitalSignature class

 Digital signature in signed file.
 

## Constructors

| name | description |
| --- | --- |
| [DigitalSignature](/slides/php-java/digitalsignature/digitalsignature/)(byte[], String) | Creates a new DigitalSignature object with the specified certificate. |
| [DigitalSignature](/slides/php-java/digitalsignature/digitalsignature/)(String, String) | Creates a new DigitalSignature object with the specified certificate file path and password. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getCertificate](/slides/php-java/digitalsignature/getcertificate/)() | byte | Certificate object that was used to sign the document. Read-only byte[]. |
| [getComments](/slides/php-java/digitalsignature/getcomments/)() | String | The purpose of signature. Read/write String. |
| [getSignTime](/slides/php-java/digitalsignature/getsigntime/)() | Date | The time when the document was signed. Read-only java.util.Date. |
| [isValid](/slides/php-java/digitalsignature/isvalid/)() | boolean | If this digital signature is valid and the document has not been tampered with, this value will be true. Read-only boolean. |
| [setComments](/slides/php-java/digitalsignature/setcomments/)(String) | void | The purpose of signature. Read/write String. |
