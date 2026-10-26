---
title: get_LocalName()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vrací lokální název uzlu, pokud je v odvozené třídě přepsán.
type: docs
weight: 209
url: /cs/system.xml/xmlnode/get_localname/
---
## XmlNode::get_LocalName() method


Vrací lokální název uzlu, pokud je přepsán v odvozené třídě.

```cpp
virtual String System::Xml::XmlNode::get_LocalName()=0
```


### Návratová hodnota

Název uzlu s odstraněnou předponou. Například **LocalName** je **book** pro prvek **<bk:book>**.
## Poznámky



Vrácený název závisí na [XmlNode::get_NodeType](../get_nodetype/) uzlu: 

| Typ | Název |
| --- | --- |
| [Attribute](../../../system/attribute/)| Lokální název atributu. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | Název typu dokumentu. |
| Element | Lokální název elementu. |
| Entity | Název entity. |
| EntityReference | Název odkazované entity. |
| Notation | Název notace. |
| ProcessingInstruction | Cíl instrukce zpracování. |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |


## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlNode](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)