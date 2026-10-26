---
title: get_Value()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vrací hodnotu uzlu.
type: docs
weight: 14
url: /cs/system.xml/xmlnode/get_value/
---
## XmlNode::get_Value() metoda


Vrací hodnotu uzlu.

```cpp
virtual String System::Xml::XmlNode::get_Value()
```


### Návratová hodnota

Vrácená hodnota závisí na [XmlNode::get_NodeType](../get_nodetype/) uzlu: 

| Typ | Hodnota |
| --- | --- |
| [Attribute](../../../system/attribute/)| Hodnota atributu. |
| CDATASection | Obsah sekce CDATA. |
| Comment | Obsah komentáře. |
| Document | `nullptr`. |
| DocumentFragment | `nullptr`. |
| DocumentType | `nullptr`. |
| Element | `nullptr`. Můžete použít XmlElement::InnerText nebo [XmlElement::get_InnerXml](../../xmlelement/get_innerxml/) k získání hodnoty uzlu elementu. |
| Entity | `nullptr`. |
| EntityReference | `nullptr`. |
| Notation | `nullptr`. |
| ProcessingInstruction | Celý obsah kromě cíle. |
| [Text](../../../system.text/)| Obsah textového uzlu. |
| SignificantWhitespace | Znaky mezery. Mezery mohou tvořit jeden nebo více znaků mezery, návratů vozíku, znaků nového řádku nebo tabulátorů. |
| Whitespace | Znaky mezery. Mezery mohou tvořit jeden nebo více znaků mezery, návratů vozíku, znaků nového řádku nebo tabulátorů. |
| [XmlDeclaration](../../xmldeclaration/)| Obsah deklarace (tj. vše mezi `<?xml a ?>`). |

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlNode](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)