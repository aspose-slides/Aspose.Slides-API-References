---
title: get_LocalName()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar det lokala namnet på noden när den åsidosätts i en underklass.
type: docs
weight: 209
url: /sv/system.xml/xmlnode/get_localname/
---
## XmlNode::get_LocalName() metod


Returnerar det lokala namnet på noden när den åsidosätts i en underklass.

```cpp
virtual String System::Xml::XmlNode::get_LocalName()=0
```


### Returvärde

Namnet på noden utan prefixet. Till exempel är **LocalName** **book** för elementet **<bk:book>**.

## Anmärkningar



Det returnerade namnet beror på [XmlNode::get_NodeType](../get_nodetype/) för noden: 

| Typ | Namn |
| --- | --- |
| [Attribute](../../../system/attribute/)| Det lokala namnet på attributet. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | Namnet på dokumenttypen. |
| Element | Det lokala namnet på elementet. |
| Entity | Namnet på entiteten. |
| EntityReference | Namnet på den refererade entiteten. |
| Notation | Namnet på notationen. |
| ProcessingInstruction | Målet för processinstruktionen. |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |


## Se även

* Klass [String](../../../system/string/)
* Klass [XmlNode](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)