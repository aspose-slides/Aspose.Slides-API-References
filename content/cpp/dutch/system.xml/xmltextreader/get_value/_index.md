---
title: get_Value()
second_title: Aspose.Slides voor C++ API-referentie
description: Geeft de tekstwaarde van de huidige knoop terug.
type: docs
weight: 79
url: /nl/system.xml/xmltextreader/get_value/
---
## XmlTextReader::get_Value() methode


Geeft de tekstwaarde van de huidige knoop terug.

```cpp
String System::Xml::XmlTextReader::get_Value() override
```


### Retourwaarde

De geretourneerde waarde is afhankelijk van de [XmlTextReader::get_NodeType](../get_nodetype/) waarde van de knoop.

## Opmerkingen



De volgende tabel toont knooptypen die een waarde hebben om terug te geven. Alle andere knooptypen geven [String::Empty](../../../system/string/empty/) terug. 

| Knooptype | Waarde |
| --- | --- |
| [Attribute](../../../system/attribute/)| De waarde van het attribuut. |
| CDATA| De inhoud van de CDATA sectie. |
| Comment| De inhoud van het commentaar. |
| DocumentType| De interne subset. |
| ProcessingInstruction| De volledige inhoud, exclusief het doel. |
| SignificantWhitespace| De witruimte binnen een `xml:space='preserve'` bereik. |
| [Text](../../../system.text/)| De inhoud van de tekstknoop. |
| Whitespace| De witruimte tussen markup. |
| [XmlDeclaration](../../xmldeclaration/)| De inhoud van de declaratie. |


## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlTextReader](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)