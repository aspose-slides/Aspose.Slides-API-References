---
title: DigitalSignature
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/digitalsignature/
---

## DigitalSignature class

 Digital signature in signed file.
 

## Constructors

| Name | Description |
| --- | --- |
| [DigitalSignature](digitalsignature)(byte[], String) | Creates a new DigitalSignature object with the specified certificate. |
| [DigitalSignature](digitalsignature)(String, String) | Creates a new DigitalSignature object with the specified certificate file path and password. |

## Methods

| Name | Description |
| --- | --- |
| [getCertificate](getcertificate)() | Certificate object that was used to sign the document. Read-only byte[]. |
| [getComments](getcomments)() | The purpose of signature. Read/write String. |
| [getSignTime](getsigntime)() | The time when the document was signed. Read-only java.util.Date. |
| [isValid](isvalid)() | If this digital signature is valid and the document has not been tampered with, this value will be true. Read-only boolean. |
| [setComments](setcomments)(String) | The purpose of signature. Read/write String. |
