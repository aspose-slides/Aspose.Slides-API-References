---
title: get_Value()
second_title: Aspose.Slides C++-hoz API hivatkozás
description: Amikor egy származtatott osztályban felül van definiálva, visszaadja a jelenlegi csomópont szöveges értékét.
type: docs
weight: 92
url: /hu/system.xml/xmlreader/get_value/
---
## XmlReader::get_Value() metódus

When overridden in a derived class, gets the text value of the current node.

```cpp
virtual String System::Xml::XmlReader::get_Value()=0
```

### Visszatérési érték

The value returned depends on the [XmlReader::get_NodeType](../get_nodetype/) value of the node.

## Megjegyzések

The following table lists node types that have a value to return. All other node types return [String::Empty](../../../system/string/empty/). 

| Csomópont típus | Érték |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| Az attribútum értéke. |
| `CDATA`| A CDATA szakasz tartalma. |
| `Comment`| A megjegyzés tartalma. |
| `DocumentType`| A belső részhalmaz. |
| `ProcessingInstruction`| A teljes tartalom, a cél nélkül. |
| `SignificantWhitespace`| A jelentős szóköz a vegyes tartalom modellben a jelölés között. |
| `[Text](../../../system.text/)`| A szöveges csomópont tartalma. |
| `Whitespace`| A szóköz a jelölés között. |
| [XmlDeclaration](../../xmldeclaration/)| A deklaráció tartalma. |

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)