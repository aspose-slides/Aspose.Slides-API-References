---
title: get_Value()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de tekstwaarde van de huidige node.
type: docs
weight: 79
url: /nl/system.xml/xmlnodereader/get_value/
---
## XmlNodeReader::get_Value() method


Retourneert de tekstwaarde van de huidige node.

```cpp
String System::Xml::XmlNodeReader::get_Value() override
```


### Return Value

De geretourneerde waarde is afhankelijk van de [XmlNodeReader::get_NodeType](../get_nodetype/) van de node.
## Remarks



De volgende tabel geeft de node-types weer die een waarde hebben om te retourneren. Alle andere node-types retourneren [String::Empty](../../../system/string/empty/). 

| Node-type | Waarde |
| --- | --- |
| [Attribute](../../../system/attribute/)| De waarde van het attribuut. |
| CDATA| De inhoud van de CDATA-sectie. |
| Comment| De inhoud van de commentaar. |
| DocumentType| De interne subset. |
| ProcessingInstruction| De volledige inhoud, exclusief het doel. |
| SignificantWhitespace| De witruimte tussen markup in een gemengd inhoudsmodel. |
| [Text](../../../system.text/)| De inhoud van het tekst-node. |
| Whitespace| De witruimte tussen markup. |
| [XmlDeclaration](../../xmldeclaration/)| De inhoud van de declaratie. |


## See Also

* Klasse [String](../../../system/string/)
* Klasse [XmlNodeReader](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)