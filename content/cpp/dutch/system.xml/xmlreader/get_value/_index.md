---
title: get_Value()
second_title: Aspose.Slides voor C++ API-referentie
description: Wanneer in een afgeleide klasse wordt overschreven, retourneert deze de tekstwaarde van het huidige knooppunt.
type: docs
weight: 92
url: /nl/system.xml/xmlreader/get_value/
---
## XmlReader::get_Value() method


Wanneer in een afgeleide klasse wordt overschreven, retourneert deze de tekstwaarde van het huidige knooppunt.

```cpp
virtual String System::Xml::XmlReader::get_Value()=0
```


### Retourwaarde

De geretourneerde waarde hangt af van de [XmlReader::get_NodeType](../get_nodetype/)-waarde van het knooppunt.

## Opmerkingen



De volgende tabel geeft knoop-typen weer die een waarde hebben om terug te geven. Alle andere knoop-typen geven [String::Empty](../../../system/string/empty/) terug. 

| Node type | Value |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| De waarde van het attribuut. |
| `CDATA`| De inhoud van de CDATA-sectie. |
| `Comment`| De inhoud van de opmerking. |
| `DocumentType`| De interne subset. |
| `ProcessingInstruction`| De volledige inhoud, exclusief het doel. |
| `SignificantWhitespace`| De witruimte tussen markup in een gemengd inhoudsmodel. |
| `[Text](../../../system.text/)`| De inhoud van het tekstknooppunt. |
| `Whitespace`| De witruimte tussen markup. |
| [XmlDeclaration](../../xmldeclaration/)| De inhoud van de declaratie. |


## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlReader](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)