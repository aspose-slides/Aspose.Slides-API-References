---
title: get_LocalName()
second_title: Aspose.Slides dla C++ - odniesienie do API
description: Zwraca lokalną nazwę węzła, gdy jest przesłonięta w klasie pochodnej.
type: docs
weight: 209
url: /pl/system.xml/xmlnode/get_localname/
---
## XmlNode::get_LocalName() metoda


Zwraca lokalną nazwę węzła, gdy jest przesłonięta w klasie pochodnej.

```cpp
virtual String System::Xml::XmlNode::get_LocalName()=0
```


### Wartość zwracana

Nazwa węzła z usuniętym prefiksem. Na przykład, **LocalName** to **book** dla elementu **<bk:book>**.
## Uwagi



Zwracana nazwa zależy od [XmlNode::get_NodeType](../get_nodetype/) węzła: 

| Typ | Nazwa |
| --- | --- |
| [Attribute](../../../system/attribute/)| Lokalna nazwa atrybutu. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | Nazwa typu dokumentu. |
| Element | Lokalna nazwa elementu. |
| Entity | Nazwa encji. |
| EntityReference | Nazwa odwołanej encji. |
| Notation | Nazwa notacji. |
| ProcessingInstruction | Cel instrukcji przetwarzania. |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |


## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlNode](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)