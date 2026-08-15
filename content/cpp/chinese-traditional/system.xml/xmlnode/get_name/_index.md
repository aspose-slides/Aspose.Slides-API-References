---
title: get_Name()
second_title: Aspose.Slides for C++ API 參考
description: 當在衍生類別中被覆寫時，返回節點的限定名稱。
type: docs
weight: 1
url: /zh-hant/system.xml/xmlnode/get_name/
---
## XmlNode::get_Name() method

返回節點的限定名稱，當在衍生類別中被覆寫時。

```cpp
virtual String System::Xml::XmlNode::get_Name()=0
```

### 返回值

節點的限定名稱。

## 備註

返回的名稱取決於節點的 [XmlNode::get_NodeType](../get_nodetype/)：

| 類型 | 名稱 |
| --- | --- |
| [Attribute](../../../system/attribute/) | 屬性的限定名稱。 |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | 文件類型名稱。 |
| Element | 元素的限定名稱。 |
| Entity | 實體的名稱。 |
| EntityReference | 所參照實體的名稱。 |
| Notation | 表示法名稱。 |
| ProcessingInstruction | 處理指令的目標。 |
| [Text](../../../system.text/) | #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/) | #xml-declaration |

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlNode](../)
* 名稱空間 [System::Xml](../../)
* 程式庫 [Aspose.Slides](../../../)