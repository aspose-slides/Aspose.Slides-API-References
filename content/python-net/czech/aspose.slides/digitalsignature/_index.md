---
title: DigitalSignature class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/digitalsignature/
---
## Třída DigitalSignature

Digitální podpis v podepsaném souboru.

Typ DigitalSignature vystavuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self, certificate)`](/slides/python-net/cs/aspose.slides/digitalsignature/__init__/#systemsecuritycryptographyx509certificatesx509certificate2) | Vytvoří nový objekt DigitalSignature se zvoleným certifikátem. |
| [`__init__(self, file_path, password)`](/slides/python-net/cs/aspose.slides/digitalsignature/__init__/#str-str) | Vytvoří nový objekt DigitalSignature se zadanou cestou k souboru certifikátu a heslem. |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`certificate`](/slides/python-net/cs/aspose.slides/digitalsignature/certificate/) | Objekt certifikátu, který byl použit k podepsání dokumentu.<br/>            Read-only **System.Security.Cryptography.X509Certificates.X509Certificate2**. |
| [`is_valid`](/slides/python-net/cs/aspose.slides/digitalsignature/is_valid/) | Pokud je tento digitální podpis platný a dokument nebyl pozměněn, tato hodnota bude true.<br/>            Read-only **bool**. |
| [`sign_time`](/slides/python-net/cs/aspose.slides/digitalsignature/sign_time/) | Čas, kdy byl dokument podepsán.<br/>            Read-only **System.DateTime**. |
| [`comments`](/slides/python-net/cs/aspose.slides/digitalsignature/comments/) | Účel podpisu.<br/>            Read/write **str**. |


### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)