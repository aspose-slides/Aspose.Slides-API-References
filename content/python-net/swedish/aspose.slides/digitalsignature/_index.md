---
title: DigitalSignature class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/digitalsignature/
---
## DigitalSignature klass

Digital signatur i signerad fil.

DigitalSignature-typen exponerar följande medlemmar:

## Konstruktorer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self, certificate)`](/slides/python-net/sv/aspose.slides/digitalsignature/__init__/#systemsecuritycryptographyx509certificatesx509certificate2) | Skapar ett nytt DigitalSignature-objekt med det angivna certifikatet. |
| [`__init__(self, file_path, password)`](/slides/python-net/sv/aspose.slides/digitalsignature/__init__/#str-str) | Skapar ett nytt DigitalSignature-objekt med den angivna sökvägen till certifikatfilen och lösenordet. |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`certificate`](/slides/python-net/sv/aspose.slides/digitalsignature/certificate/) | Certifikatobjekt som användes för att signera dokumentet.<br/>            Read-only **System.Security.Cryptography.X509Certificates.X509Certificate2**. |
| [`is_valid`](/slides/python-net/sv/aspose.slides/digitalsignature/is_valid/) | Om denna digitala signatur är giltig och dokumentet inte har manipulerats, kommer detta värde att vara sant.<br/>            Read-only **bool**. |
| [`sign_time`](/slides/python-net/sv/aspose.slides/digitalsignature/sign_time/) | Tidpunkten då dokumentet signerades.<br/>            Read-only **System.DateTime**. |
| [`comments`](/slides/python-net/sv/aspose.slides/digitalsignature/comments/) | Syftet med signaturen.<br/>            Read/write **str**. |

### Se också
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)