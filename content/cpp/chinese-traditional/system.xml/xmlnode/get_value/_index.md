---
title: get_Value()
second_title: Aspose.Slides for C++ API 參考
description: 傳回節點的值。
type: docs
weight: 14
url: /zh-hant/system.xml/xmlnode/get_value/
---
## XmlNode::get_Value() method


傳回節點的值。

```cpp
virtual String System::Xml::XmlNode::get_Value()
```


### 回傳值

傳回的值取決於節點的[XmlNode::get_NodeType](../get_nodetype/)：

| 類型 | 值 |
| --- | --- |
| [Attribute](../../../system/attribute/)| 屬性的值。 |
| CDATASection | CDATA 區段的內容。 |
| Comment | 註解的內容。 |
| Document | `nullptr`. |
| DocumentFragment | `nullptr`. |
| DocumentType | `nullptr`. |
| Element | `nullptr`. 您可以使用 XmlElement::InnerText 或 [XmlElement::get_InnerXml](../../xmlelement/get_innerxml/) 值來存取元素節點的值。 |
| Entity | `nullptr`. |
| EntityReference | `nullptr`. |
| Notation | `nullptr`. |
| ProcessingInstruction | 整個內容（不含目標）。 |
| [Text](../../../system.text/)| 文字節點的內容。 |
| SignificantWhitespace | 空白字元。空白可以由一個或多個空格字元、換行符、換行字元或製表符組成。 |
| Whitespace | 空白字元。空白可以由一個或多個空格字元、換行符、換行字元或製表符組成。 |
| [XmlDeclaration](../../xmldeclaration/)| 宣告的內容（即位於 `<?xml and ?>` 之間的所有內容）。 |

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlNode](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)