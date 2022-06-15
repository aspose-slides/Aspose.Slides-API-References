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
| [DigitalSignature](/php-java/digitalsignature/digitalsignature/)(byte[], String) | Creates a new DigitalSignature object with the specified certificate. |
| [DigitalSignature](/php-java/digitalsignature/digitalsignature/)(String, String) | Creates a new DigitalSignature object with the specified certificate file path and password. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getCertificate](/php-java/digitalsignature/getcertificate/)() | byte | Certificate object that was used to sign the document. Read-only byte[]. |
| [getComments](/php-java/digitalsignature/getcomments/)() | String | The purpose of signature. Read/write String. |
| [getSignTime](/php-java/digitalsignature/getsigntime/)() | Date | The time when the document was signed. Read-only java.util.Date. |
| [isValid](/php-java/digitalsignature/isvalid/)() | boolean | If this digital signature is valid and the document has not been tampered with, this value will be true. Read-only boolean. |
| [setComments](/php-java/digitalsignature/setcomments/)(String) | void | The purpose of signature. Read/write String. |
