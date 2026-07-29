---
title: get_Value()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar värdet för noden.
type: docs
weight: 14
url: /sv/system.xml/xmlnode/get_value/
---
## XmlNode::get_Value() metod


Returnerar värdet för noden.

```cpp
virtual String System::Xml::XmlNode::get_Value()
```


### Returvärde

Det returnerade värdet beror på [XmlNode::get_NodeType](../get_nodetype/) för noden: 

| Typ | Värde |
| --- | --- |
| [Attribute](../../../system/attribute/) | Värdet på attributet. |
| CDATASection | Innehållet i CDATA-sektionen. |
| Comment | Innehållet i kommentaren. |
| Document | `nullptr`. |
| DocumentFragment | `nullptr`. |
| DocumentType | `nullptr`. |
| Element | `nullptr`. Du kan använda XmlElement::InnerText eller [XmlElement::get_InnerXml](../../xmlelement/get_innerxml/) värden för att komma åt elementnodens värde. |
| Entity | `nullptr`. |
| EntityReference | `nullptr`. |
| Notation | `nullptr`. |
| ProcessingInstruction | Hela innehållet exklusive målet. |
| [Text](../../../system.text/) | Innehållet i textnoden. |
| SignificantWhitespace | Tecken för blanksteg. Blanksteg kan bestå av en eller flera mellanslag, vagnretur, radmatning eller tabulatorer. |
| Whitespace | Tecken för blanksteg. Blanksteg kan bestå av en eller flera mellanslag, vagnretur, radmatning eller tabulatorer. |
| [XmlDeclaration](../../xmldeclaration/) | Innehållet i deklarationen (det vill säga allt mellan `<?xml och ?>`). |

## Se också

* Klass [String](../../../system/string/)
* Klass [XmlNode](../)
* Namnrymd [System::Xml](../../)
* Library [Aspose.Slides](../../../)