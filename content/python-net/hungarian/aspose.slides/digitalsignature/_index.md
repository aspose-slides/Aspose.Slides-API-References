---
title: DigitalSignature class
second_title: Aspose.Slides Pythonhoz a .NET-en keresztül API-referenciája
description: 
type: docs
url: /hu/aspose.slides/digitalsignature/
---
## DigitalSignature osztály

Digitális aláírás az aláírt fájlban.

A DigitalSignature típus a következő tagokat tartalmazza:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self, certificate)`](/slides/python-net/hu/aspose.slides/digitalsignature/__init__/#systemsecuritycryptographyx509certificatesx509certificate2) | Új DigitalSignature objektumot hoz létre a megadott tanúsítvánnyal. |
| [`__init__(self, file_path, password)`](/slides/python-net/hu/aspose.slides/digitalsignature/__init__/#str-str) | Új DigitalSignature objektumot hoz létre a megadott tanúsítványfájl-útvonal és jelszó alapján. |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`certificate`](/slides/python-net/hu/aspose.slides/digitalsignature/certificate/) | A dokumentum aláírásához használt tanúsítvány objektum.<br/>            Csak olvasható **System.Security.Cryptography.X509Certificates.X509Certificate2**. |
| [`is_valid`](/slides/python-net/hu/aspose.slides/digitalsignature/is_valid/) | Ha ez a digitális aláírás érvényes és a dokumentumot nem módosították, ez az érték true lesz.<br/>            Csak olvasható **bool**. |
| [`sign_time`](/slides/python-net/hu/aspose.slides/digitalsignature/sign_time/) | A dokumentum aláírásának időpontja.<br/>            Csak olvasható **System.DateTime**. |
| [`comments`](/slides/python-net/hu/aspose.slides/digitalsignature/comments/) | Az aláírás célja.<br/>            Olvasás/írás **str**. |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)