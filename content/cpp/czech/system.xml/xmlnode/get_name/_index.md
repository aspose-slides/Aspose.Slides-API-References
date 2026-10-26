---
title: get_Name()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vrací kvalifikovaný název uzlu, pokud je v odvozené třídě přepsán.
type: docs
weight: 1
url: /cs/system.xml/xmlnode/get_name/
---
## XmlNode::get_Name() metoda


Vrací kvalifikovaný název uzlu, pokud je přepsán v odvozené třídě.

```cpp
virtual String System::Xml::XmlNode::get_Name()=0
```


### Návratová hodnota

Kvalifikovaný název uzlu.
## Poznámky



Vrácený název závisí na [XmlNode::get_NodeType](../get_nodetype/) uzlu: 

| Typ | Název |
| --- | --- |
| [Attribute](../../../system/attribute/)| Kvalifikovaný název atributu. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | Název typu dokumentu. |
| Element | Kvalifikovaný název elementu. |
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