---
title: DigitalSignature class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/digitalsignature/
---
## DigitalSignature klasse

Digitale handtekening in ondertekend bestand.

Het DigitalSignature-type exposeert de volgende leden:

## Constructoren

| Constructor | Beschrijving |
| :- | :- |
| [`__init__(self, certificate)`](/slides/python-net/nl/aspose.slides/digitalsignature/__init__/#systemsecuritycryptographyx509certificatesx509certificate2) | Maakt een nieuw DigitalSignature-object met het opgegeven certificaat. |
| [`__init__(self, file_path, password)`](/slides/python-net/nl/aspose.slides/digitalsignature/__init__/#str-str) | Maakt een nieuw DigitalSignature-object met het opgegeven certificaatbestandspad en wachtwoord. |

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`certificate`](/slides/python-net/nl/aspose.slides/digitalsignature/certificate/) | Certificaatobject dat werd gebruikt om het document te ondertekenen.<br/>            Alleen-lezen **System.Security.Cryptography.X509Certificates.X509Certificate2**. |
| [`is_valid`](/slides/python-net/nl/aspose.slides/digitalsignature/is_valid/) | Als deze digitale handtekening geldig is en het document niet is gemanipuleerd, zal deze waarde true zijn.<br/>            Alleen-lezen **bool**. |
| [`sign_time`](/slides/python-net/nl/aspose.slides/digitalsignature/sign_time/) | Het tijdstip waarop het document werd ondertekend.<br/>            Alleen-lezen **System.DateTime**. |
| [`comments`](/slides/python-net/nl/aspose.slides/digitalsignature/comments/) | Het doel van de handtekening.<br/>            Lezen/schrijven **str**. |

### Zie Ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)