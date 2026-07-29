---
title: get_Name()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar det kvalificerade namnet på noden när den åsidosätts i en underklass.
type: docs
weight: 1
url: /sv/system.xml/xmlnode/get_name/
---
## XmlNode::get_Name() metod


Returnerar det kvalificerade namnet på noden när den åsidosätts i en underklass.

```cpp
virtual String System::Xml::XmlNode::get_Name()=0
```


### Returvärde

Det kvalificerade namnet på noden.
## Anmärkningar



Det returnerade namnet beror på [XmlNode::get_NodeType](../get_nodetype/) för noden: 

| Typ | Namn |
| --- | --- |
| [Attribute](../../../system/attribute/)| Det kvalificerade namnet på attributet. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | Dokumenttypens namn. |
| Element | Det kvalificerade namnet på elementet. |
| Entity | Entitetens namn. |
| EntityReference | Namnet på den refererade entiteten. |
| Notation | Namnet på notationen. |
| ProcessingInstruction | Målet för bearbetningsinstruktionen. |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |


## Se också

* Klass [String](../../../system/string/)
* Klass [XmlNode](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)