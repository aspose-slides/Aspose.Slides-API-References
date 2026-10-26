---
title: XmlNodeType
second_title: Aspose.Slides för C++ API-referens
description: Anger nodens typ.
type: docs
weight: 833
url: /sv/system.xml/xmlnodetype/
---
## XmlNodeType enum

Anger nodens typ.

```cpp
enum class XmlNodeType
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | 0 | Detta returneras av [XmlReader](../xmlreader/) om en **Read**-metod inte har anropats. |
| Element | 1 | Ett element (till exempel **<item>**). |
| Attribute | 2 | Ett attribut (till exempel **id='123'**). |
| Text | 3 | Textinnehållet i en nod. En [XmlNodeType::Text](./) nod kan inte ha några barnnoder. Den kan visas som barnnod till [XmlNodeType::Attribute](./), [XmlNodeType::DocumentFragment](./), [XmlNodeType::Element](./) och [XmlNodeType::EntityReference](./) noderna. |
| CDATA | 4 | En CDATA-sektion (till exempel **my escaped text**). |
| EntityReference | 5 | En referens till en entitet (till exempel **&num;**). |
| Entity | 6 | En entitetsdeklaration (till exempel **<!ENTITY...>**). |
| ProcessingInstruction | 7 | En bearbetningsinstruktion (till exempel **<?pi test?>**). |
| Comment | 8 | En kommentar (till exempel ****). |
| Document | 9 | Ett dokumentobjekt som, som roten i dokumentträdet, ger åtkomst till hela XML-dokumentet. |
| DocumentType | 10 | Deklarationen av dokumenttypen, som indikeras av följande tagg (till exempel **<!DOCTYPE...>**). |
| DocumentFragment | 11 | Ett dokumentfragment. |
| Notation | 12 | En notation i dokumenttypdeklarationen (till exempel **<!NOTATION...>**). |
| Whitespace | 13 | Mellanslag mellan markup. |
| SignificantWhitespace | 14 | Mellanslag mellan markup i en blandad innehållsmodell eller mellanslag inom **xml:space="preserve"**-området. |
| EndElement | 15 | En avslutningselement-tag (till exempel ****). |
| EndEntity | 16 | Returneras när [XmlReader](../xmlreader/) når slutet av entitetsersättningen som ett resultat av ett anrop till [XmlReader::ResolveEntity](../xmlreader/resolveentity/). |
| XmlDeclaration | 17 | XML-deklarationen (till exempel **<?xml version='1.0'?>**). [XmlNodeType::XmlDeclaration](./)-noden måste vara den första noden i dokumentet. Den kan inte ha barn. Den är ett barn till [XmlNodeType::Document](./)-noden. Den kan ha attribut som tillhandahåller version- och kodningsinformation. |

## Se även

* Namnrymd [System::Xml](../)
* Bibliotek [Aspose.Slides](../../)