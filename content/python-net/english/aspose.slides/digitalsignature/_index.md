---
title: DigitalSignature class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/digitalsignature/
---


## DigitalSignature class

Digital signature in signed file.

The DigitalSignature type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__`](/slides/python-net/aspose.slides/digitalsignature/__init__/#systemsecuritycryptographyx509certificatesx509certificate2) | Creates a new DigitalSignature object with the specified certificate. |
| [`__init__`](/slides/python-net/aspose.slides/digitalsignature/__init__/#string-string) | Creates a new DigitalSignature object with the specified certificate file path and password. |

## Properties

| Property | Description |
| :- | :- |
| [`certificate`](/slides/python-net/aspose.slides/digitalsignature/certificate/) | Certificate object that was used to sign the document.<br/>            Read-only **System.Security.Cryptography.X509Certificates.X509Certificate2**. |
| [`is_valid`](/slides/python-net/aspose.slides/digitalsignature/is_valid/) | If this digital signature is valid and the document has not been tampered with, this value will be true.<br/>            Read-only **bool**. |
| [`sign_time`](/slides/python-net/aspose.slides/digitalsignature/sign_time/) | The time when the document was signed.<br/>            Read-only **System.DateTime**. |
| [`comments`](/slides/python-net/aspose.slides/digitalsignature/comments/) | The purpose of signature.<br/>            Read/write **string**. |

### See Also
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
