---
title: get_Name()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Zwraca w pełni kwalifikowaną nazwę węzła, gdy zostanie nadpisana w klasie pochodnej.
type: docs
weight: 1
url: /pl/system.xml/xmlnode/get_name/
---
## XmlNode::get_Name() metoda


Zwraca w pełni kwalifikowaną nazwę węzła, gdy zostanie nadpisana w klasie pochodnej.

```cpp
virtual String System::Xml::XmlNode::get_Name()=0
```


### Wartość zwracana

W pełni kwalifikowana nazwa węzła.
## Uwagi



Zwracana nazwa zależy od [XmlNode::get_NodeType](../get_nodetype/) węzła: 

| Typ | Nazwa |
| --- | --- |
| [Attribute](../../../system/attribute/)| W pełni kwalifikowana nazwa atrybutu. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | Nazwa typu dokumentu. |
| Element | W pełni kwalifikowana nazwa elementu. |
| Entity | Nazwa jednostki. |
| EntityReference | Nazwa odwołanej jednostki. |
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