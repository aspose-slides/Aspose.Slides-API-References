---
title: XmlNodeType
second_title: Aspose.Slides C++ API referencia
description: Megadja a csomópont típusát.
type: docs
weight: 833
url: /hu/system.xml/xmlnodetype/
---
## XmlNodeType enum

Megadja a csomópont típusát.

```cpp
enum class XmlNodeType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | Ezt adja vissza a [XmlReader](../xmlreader/), ha egy **Read** metódus nem lett meghívva. |
| Element | 1 | Egy elem (például **<item>**). |
| Attribute | 2 | Egy attribútum (például **id='123'**). |
| Text | 3 | A csomópont szövegtartalma. Egy [XmlNodeType::Text](./) csomópont nem rendelkezhet gyermek csomópontokkal. Megjelenhet a [XmlNodeType::Attribute](./), [XmlNodeType::DocumentFragment](./), [XmlNodeType::Element](./) és [XmlNodeType::EntityReference](./) csomópontok gyermekeként. |
| CDATA | 4 | Egy CDATA szakasz (például **my escaped text**). |
| EntityReference | 5 | Egy hivatkozás egy entitásra (például **&num;**). |
| Entity | 6 | Egy entitásdeklaráció (például **<!ENTITY...>**). |
| ProcessingInstruction | 7 | Egy feldolgozási utasítás (például **<?pi test?>**). |
| Comment | 8 | Egy megjegyzés (például ****). |
| Document | 9 | Egy dokumentumobjektum, amely a dokumentumfa gyökereként hozzáférést biztosít a teljes XML dokumentumhoz. |
| DocumentType | 10 | A dokumentumtípus deklarációja, amely a következő címkével jelölt (például **<!DOCTYPE...>**). |
| DocumentFragment | 11 | Egy dokumentum töredék. |
| Notation | 12 | Egy jelölés a dokumentumtípus deklarációban (például **<!NOTATION...>**). |
| Whitespace | 13 | Üres karakterek a jelölés között. |
| SignificantWhitespace | 14 | Üres karakterek a jelölés között kevert tartalommodellben vagy a **xml:space="preserve"** hatókörben. |
| EndElement | 15 | Egy záróelem címke (például ****). |
| EndEntity | 16 | Visszatér, amikor a [XmlReader](../xmlreader/) eléri az entitás helyettesítés végét a [XmlReader::ResolveEntity](../xmlreader/resolveentity/) hívása következtében. |
| XmlDeclaration | 17 | Az XML deklaráció (például **<?xml version='1.0'?>**). A [XmlNodeType::XmlDeclaration](./) csomópontnak kell, hogy legyen az első csomópont a dokumentumban. Nem lehet gyermekei. A [XmlNodeType::Document](./) csomópont gyermeke. Tartalmazhat attribútumokat, amelyek verzió- és kódolási információkat adnak meg. |

## Lásd még

* Namespace [System::Xml](../)
* Library [Aspose.Slides](../../)