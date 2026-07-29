---
title: get_Value()
second_title: Aspose.Slides för C++ API-referens
description: När den åsidosätts i en avledd klass, hämtar den textvärdet för den aktuella noden.
type: docs
weight: 92
url: /sv/system.xml/xmlreader/get_value/
---
## XmlReader::get_Value() metod


När den åsidosätts i en avledd klass, hämtar den textvärdet för den aktuella noden.

```cpp
virtual String System::Xml::XmlReader::get_Value()=0
```


### Returvärde

Det returnerade värdet beror på [XmlReader::get_NodeType](../get_nodetype/)-värdet för noden.

## Anmärkningar



Följande tabell listar nodtyper som har ett värde att returnera. Alla andra nodtyper returnerar [String::Empty](../../../system/string/empty/). 

| Nodtyp | Värde |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| Attributets värde. |
| `CDATA`| Innehållet i CDATA-sektionen. |
| `Comment`| Innehållet i kommentaren. |
| `DocumentType`| Den interna delmängden. |
| `ProcessingInstruction`| Det fullständiga innehållet, exklusive målet. |
| `SignificantWhitespace`| Blanksteg mellan markup i en blandad innehållsmodell. |
| `[Text](../../../system.text/)`| Innehållet i textnoden. |
| `Whitespace`| Blanksteg mellan markup. |
| [XmlDeclaration](../../xmldeclaration/)| Innehållet i deklarationen. |


## Se också

* Klass [String](../../../system/string/)
* Klass [XmlReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)