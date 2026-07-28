---
title: get_Name()
second_title: Aspose.Slides C++ API referenciája
description: Visszaadja a csomópont minősített nevét, ha egy leszármazott osztály felülírja.
type: docs
weight: 1
url: /hu/system.xml/xmlnode/get_name/
---
## XmlNode::get_Name() metódus


Visszaadja a csomópont minősített nevét, ha egy leszármazott osztály felülírja.

```cpp
virtual String System::Xml::XmlNode::get_Name()=0
```


### Visszatérési érték

A csomópont minősített neve.
## Megjegyzés



A visszaadott név a [XmlNode::get_NodeType](../get_nodetype/)-tól függ a csomópont esetében: 

| Típus | Név |
| --- | --- |
| [Attribute](../../../system/attribute/)| Az attribútum minősített neve. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | A dokumentumtípus neve. |
| Element | Az elem minősített neve. |
| Entity | Az entitás neve. |
| EntityReference | A hivatkozott entitás neve. |
| Notation | A jelölés neve. |
| ProcessingInstruction | A feldolgozási utasítás célja. |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |


## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlNode](../)
* Névtere [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)