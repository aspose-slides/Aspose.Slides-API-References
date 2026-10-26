---
title: get_Value()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca wartość węzła.
type: docs
weight: 14
url: /pl/system.xml/xmlnode/get_value/
---
## XmlNode::get_Value() metoda

Zwraca wartość węzła.

```cpp
virtual String System::Xml::XmlNode::get_Value()
```

### Wartość zwracana

Zwracana wartość zależy od [XmlNode::get_NodeType](../get_nodetype/) węzła: 

| Typ | Wartość |
| --- | --- |
| [Attribute](../../../system/attribute/)| Wartość atrybutu. |
| CDATASection | Zawartość sekcji CDATA. |
| Comment | Zawartość komentarza. |
| Document | `nullptr`. |
| DocumentFragment | `nullptr`. |
| DocumentType | `nullptr`. |
| Element | `nullptr`. Możesz użyć XmlElement::InnerText lub wartości [XmlElement::get_InnerXml](../../xmlelement/get_innerxml/), aby uzyskać wartość węzła elementu. |
| Entity | `nullptr`. |
| EntityReference | `nullptr`. |
| Notation | `nullptr`. |
| ProcessingInstruction | Cała zawartość z wyłączeniem celu. |
| [Text](../../../system.text/)| Zawartość węzła tekstowego. |
| SignificantWhitespace | Znaki białych znaków. Białe znaki mogą składać się z jednego lub wielu znaków spacji, powrotów karetki, znaków końca linii lub tabulacji. |
| Whitespace | Znaki białych znaków. Białe znaki mogą składać się z jednego lub wielu znaków spacji, powrotów karetki, znaków końca linii lub tabulacji. |
| [XmlDeclaration](../../xmldeclaration/)| Zawartość deklaracji (czyli wszystko pomiędzy `<?xml` a `?>`). |

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlNode](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)