---
title: get_LocalName()
second_title: Aspose.Slides a C++ API hivatkozás
description: Visszaadja a csomópont helyi nevét, ha egy származtatott osztályban felül van definiálva.
type: docs
weight: 209
url: /hu/system.xml/xmlnode/get_localname/
---
## XmlNode::get_LocalName() metódus


Returns the local name of the node, when overridden in a derived class.

```cpp
virtual String System::Xml::XmlNode::get_LocalName()=0
```


### Visszatérési érték

A csomópont neve a prefix eltávolítása után. Például a **LocalName** **book** a **<bk:book>** elemhez.

## Megjegyzések



A visszaadott név a [XmlNode::get_NodeType](../get_nodetype/) a csomóponttól függ: 

| Típus | Név |
| --- | --- |
| [Attribute](../../../system/attribute/)| Az attribútum helyi neve. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | A dokumentumtípus neve. |
| Element | Az elem helyi neve. |
| Entity | Az entitás neve. |
| EntityReference | A hivatkozott entitás neve. |
| Notation | A notáció neve. |
| ProcessingInstruction | A feldolgozási utasítás célja. |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |


## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlNode](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)