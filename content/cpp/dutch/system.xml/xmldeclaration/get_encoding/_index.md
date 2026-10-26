---
title: get_Encoding()
second_title: Aspose.Slides voor C++ API Referentie
description: Retourneert het coderingsniveau van het XML-document.
type: docs
weight: 14
url: /nl/system.xml/xmldeclaration/get_encoding/
---
## XmlDeclaration::get_Encoding() methode

Retourneert het coderingsniveau van het XML-document.

```cpp
String System::Xml::XmlDeclaration::get_Encoding()
```

### Retourwaarde

De geldige naam van de tekenreekscodering.

## Opmerkingen

De meest algemeen ondersteunde namen voor tekenreekscoderingen voor XML zijn de volgende:

| Categorie | Coderingnamen |
| --- | --- |
| Unicode | UTF-8, UTF-16 |
| ISO 10646 | ISO-10646-UCS-2, ISO-10646-UCS-4 |
| ISO 8859 | ISO-8859-n (waar "n" een cijfer van 1 tot 9 is) |
| JIS X-0208-1997 | ISO-2022-JP, Shift_JIS, EUC-JP |

Deze waarde is optioneel. Als er geen waarde is ingesteld, retourneert deze methode [String::Empty](../../../system/string/empty/). Als een coderingsattribuut niet is opgenomen, wordt UTF-8-codering verondersteld wanneer het document wordt weggeschreven of opgeslagen.

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlDeclaration](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)