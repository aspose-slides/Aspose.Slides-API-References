---
title: get_Value()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar textvärdet för den aktuella noden.
type: docs
weight: 79
url: /sv/system.xml/xmlnodereader/get_value/
---
## XmlNodeReader::get_Value() metod


Returnerar textvärdet för den aktuella noden.

```cpp
String System::Xml::XmlNodeReader::get_Value() override
```


### Returvärde

Det returnerade värdet beror på [XmlNodeReader::get_NodeType](../get_nodetype/) för noden.

## Anmärkningar



Följande tabell listar nodtyper som har ett värde att returnera. Alla andra nodtyper returnerar [String::Empty](../../../system/string/empty/). 

| Nodtyp | Värde |
| --- | --- |
| [Attribute](../../../system/attribute/)| Värdet på attributet. |
| CDATA| Innehållet i CDATA-sektionen. |
| Comment| Innehållet i kommentaren. |
| DocumentType| Den interna delmängden. |
| ProcessingInstruction| Hela innehållet, exklusive målet. |
| SignificantWhitespace| Mellanrummet mellan markup i en blandad innehållsmodell. |
| [Text](../../../system.text/)| Innehållet i textnoden. |
| Whitespace| Mellanrummet mellan markup. |
| [XmlDeclaration](../../xmldeclaration/)| Innehållet i deklarationen. |


## Se även

* Klass [String](../../../system/string/)
* Klass [XmlNodeReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)