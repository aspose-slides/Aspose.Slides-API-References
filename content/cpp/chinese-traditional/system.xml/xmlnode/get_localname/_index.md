---
title: get_LocalName()
second_title: Aspose.Slides for C++ API 參考
description: 當在衍生類別中被覆寫時，返回節點的本地名稱。
type: docs
weight: 209
url: /zh-hant/system.xml/xmlnode/get_localname/
---
## XmlNode::get_LocalName() 方法

返回節點的本地名稱，當在衍生類別中被覆寫時。

```cpp
virtual String System::Xml::XmlNode::get_LocalName()=0
```

### 返回值

節點名稱，已移除前置詞。例如，**LocalName** 在元素 **<bk:book>** 中為 **book**。

## 備註

返回的名稱取決於節點的 [XmlNode::get_NodeType](../get_nodetype/)：

| Type | Name |
| --- | --- |
| [Attribute](../../../system/attribute/)| 屬性的本地名稱。 |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | 文件類型的名稱。 |
| Element | 元素的本地名稱。 |
| Entity | 實體的名稱。 |
| EntityReference | 被參照實體的名稱。 |
| Notation | 符號名稱。 |
| ProcessingInstruction | 處理指令的目標。 |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlNode](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)