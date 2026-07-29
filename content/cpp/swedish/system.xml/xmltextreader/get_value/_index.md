---
title: get_Value()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar textvärdet för den aktuella noden.
type: docs
weight: 79
url: /sv/system.xml/xmltextreader/get_value/
---
## XmlTextReader::get_Value() metod

Returns the text value of the current node.

```cpp
String System::Xml::XmlTextReader::get_Value() override
```

### Returvärde

Det returnerade värdet beror på [XmlTextReader::get_NodeType](../get_nodetype/)-värdet för noden.

## Anmärkningar

Följande tabell listar nodtyper som har ett värde att returnera. Alla andra nodtyper returnerar [String::Empty](../../../system/string/empty/). 

| Node Type | Value |
| --- | --- |
| [Attribute](../../../system/attribute/)| Attributets värde. |
| CDATA| Innehållet i CDATA-sektionen. |
| Comment| Innehållet i kommentaren. |
| DocumentType| Den interna delmängden. |
| ProcessingInstruction| Det fullständiga innehållet, exklusive målet. |
| SignificantWhitespace| Mellanslaget inom ett `xml:space='preserve'`-omfång. |
| [Text](../../../system.text/)| Innehållet i textnod. |
| Whitespace| Mellanslaget mellan markup. |
| [XmlDeclaration](../../xmldeclaration/)| Innehållet i deklarationen. |

## Se även

* Klass [String](../../../system/string/)
* Klass [XmlTextReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)