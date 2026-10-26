---
title: get_Name()
second_title: Aspose.Slides for C++ API 參考
description: 傳回目前節點的限定名稱。
type: docs
weight: 14
url: /zh-hant/system.xml/xmlvalidatingreader/get_name/
---
## XmlValidatingReader::get_Name() 方法

Returns the qualified name of the current node.

```cpp
String System::Xml::XmlValidatingReader::get_Name() override
```

### 回傳值

The qualified name of the current node. For example, **Name** is **bk:book** for the element **<bk:book>**.

## 備註

The name returned is dependent on the XmlValidatingReader::NodeType of the node. The following node types return the listed values. All other node types return an empty string. 

| 節點類型 | 名稱 |
| --- | --- |
| [Attribute](../../../system/attribute/)| 屬性的名稱。 |
| DocumentType| 文件類型名稱。 |
| Element| 標籤名稱。 |
| EntityReference| 參照的實體名稱。 |
| ProcessingInstruction| 處理指示的目標。 |
| [XmlDeclaration](../../xmldeclaration/)| 字面字串 `xml`。 |

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlValidatingReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)