---
title: get_Name()
second_title: Aspose.Slides pro C++ – reference API
description: Pokud je v odvozené třídě přepsána, získá kvalifikovaný název aktuálního uzlu.
type: docs
weight: 27
url: /cs/system.xml/xmlreader/get_name/
---
## XmlReader::get_Name() metoda

When overridden in a derived class, gets the qualified name of the current node.

```cpp
virtual String System::Xml::XmlReader::get_Name()
```

### Návratová hodnota

The qualified name of the current node. For example, **Name** is **bk:book** for the element **<bk:book>**.

## Poznámky

The name returned is dependent on the [XmlReader::get_NodeType](../get_nodetype/) value of the node. The following node types return the listed values. All other node types return an empty string. 

| Typ uzlu | Název |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| Název atributu. |
| `DocumentType`| Název typu dokumentu. |
| `Element`| Název značky. |
| `EntityReference`| Název odkazované entity. |
| `ProcessingInstruction`| Cíl instrukce zpracování. |
| [XmlDeclaration](../../xmldeclaration/)| Doslovný řetězec `xml`. |

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)