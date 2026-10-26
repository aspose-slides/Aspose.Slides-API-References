---
title: get_Name()
second_title: Aspose.Slides for C++ API referencia
description: Visszaadja a jelenlegi csomópont minősített nevét.
type: docs
weight: 14
url: /hu/system.xml/xmltextreader/get_name/
---
## XmlTextReader::get_Name() metódus

Visszaadja a jelenlegi csomópont minősített nevét.

```cpp
String System::Xml::XmlTextReader::get_Name() override
```

### Visszatérési érték

A jelenlegi csomópont minősített neve. Például a **Name** értéke **bk:book** az **<bk:book>** elem esetén.

## Megjegyzés

A visszaadott név a [XmlTextReader::get_NodeType](../get_nodetype/) értékétől függ. A következő csomópont típusok a felsorolt értékeket adják vissza. Minden többi csomópont típus üres stringet ad vissza. 

| Csomópont típus | Név |
| --- | --- |
| [Attribute](../../../system/attribute/)| Az attribútum neve. |
| DocumentType| A dokumentumtípus neve. |
| Element| A címke neve. |
| EntityReference| A hivatkozott entitás neve. |
| ProcessingInstruction| A feldolgozási utasítás célja. |
| [XmlDeclaration](../../xmldeclaration/)| A szó szerinti karakterlánc `xml`. |

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlTextReader](../)
* Névterület [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)