---
title: get_Value()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de tekstwaarde van het huidige knooppunt.
type: docs
weight: 79
url: /nl/system.xml/xmlvalidatingreader/get_value/
---
## XmlValidatingReader::get_Value() methode

Retourneert de tekstwaarde van het huidige knooppunt.

```cpp
String System::Xml::XmlValidatingReader::get_Value() override
```

### Retourwaarde

De geretourneerde waarde hangt af van de XmlValidatingReader::NodeType van het knooppunt.

## Opmerkingen

De onderstaande tabel lijst knooptypen op die een waarde hebben om te retourneren. Alle andere knooptypen retourneren [String::Empty](../../../system/string/empty/). 

| Knooptype | Waarde |
| --- | --- |
| [Attribute](../../../system/attribute/)| De waarde van het attribuut. |
| CDATA| De inhoud van de CDATA-sectie. |
| Comment| De inhoud van de opmerking. |
| DocumentType| De interne subset. |
| ProcessingInstruction| De volledige inhoud, exclusief het doel. |
| SignificantWhitespace| De witruimte tussen markup in een gemengd inhoudsmodel. |
| [Text](../../../system.text/)| De inhoud van de tekstknoop. |
| Whitespace| De witruimte tussen markup. |
| [XmlDeclaration](../../xmldeclaration/)| De inhoud van de declaratie. |

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)