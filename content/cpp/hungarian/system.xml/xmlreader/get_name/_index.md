---
title: get_Name()
second_title: Aspose.Slides C++ API referencia
description: Amikor felül van definiálva egy származtatott osztályban, visszaadja az aktuális csomópont kvalifikált nevét.
type: docs
weight: 27
url: /hu/system.xml/xmlreader/get_name/
---
## XmlReader::get_Name() metódus

When overridden in a derived class, gets the qualified name of the current node.

```cpp
virtual String System::Xml::XmlReader::get_Name()
```

### Visszatérési érték

The qualified name of the current node. For example, **Name** is **bk:book** for the element **<bk:book>**.

## Megjegyzés

The name returned is dependent on the [XmlReader::get_NodeType](../get_nodetype/) value of the node. The following node types return the listed values. All other node types return an empty string. 

| Csomópont típusa | Név |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| Az attribútum neve. |
| `DocumentType`| A dokumentumtípus neve. |
| `Element`| A címke neve. |
| `EntityReference`| A hivatkozott entitás neve. |
| `ProcessingInstruction`| A feldolgozási utasítás célja. |
| [XmlDeclaration](../../xmldeclaration/)| A `xml` szó szerinti karakterlánc. |

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)