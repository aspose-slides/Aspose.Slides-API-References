---
title: get_Name()
second_title: Aspose.Slides C++ API hivatkozás
description: Visszaadja az aktuális csomópont minősített nevét.
type: docs
weight: 14
url: /hu/system.xml/xmlvalidatingreader/get_name/
---
## XmlValidatingReader::get_Name() metódus

Visszaadja az aktuális csomópont minősített nevét.

```cpp
String System::Xml::XmlValidatingReader::get_Name() override
```

### Visszatérési érték

Az aktuális csomópont minősített neve. Például a **Name** **bk:book**, ha a **<bk:book>** elemet nézzük.

## Megjegyzések

A visszaadott név az XmlValidatingReader::NodeType értékétől függ. A következő csomóponttípusok a felsorolt értékeket adják vissza. Minden más csomóponttípus egy üres stringet ad vissza.

| Csomópont típusa | Név |
| --- | --- |
| [Attribute](../../../system/attribute/)| Az attribútum neve. |
| DocumentType| A dokumentumtípus neve. |
| Element| A tag neve. |
| EntityReference| A hivatkozott entitás neve. |
| ProcessingInstruction| A feldolgozási utasítás célja. |
| [XmlDeclaration](../../xmldeclaration/)| A `xml` szó szerinti karakterlánc. |

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlValidatingReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)