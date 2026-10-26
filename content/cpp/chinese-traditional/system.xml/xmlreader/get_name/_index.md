---
title: get_Name()
second_title: Aspose.Slides for C++ API 參考
description: 當在衍生類別中被覆寫時，取得目前節點的限定名稱。
type: docs
weight: 27
url: /zh-hant/system.xml/xmlreader/get_name/
---
## XmlReader::get_Name() 方法

當在衍生類別中被覆寫時，取得目前節點的限定名稱。

```cpp
virtual String System::Xml::XmlReader::get_Name()
```

### 返回值

目前節點的限定名稱。例如，**Name** 為 **bk:book**，對於元素 **<bk:book>**。

## 備註

返回的名稱取決於節點的 [XmlReader::get_NodeType](../get_nodetype/) 值。以下節點類型返回列出的值。所有其他節點類型返回空字串。

| 節點類型 | 名稱 |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| 屬性的名稱。 |
| `DocumentType`| 文件類型名稱。 |
| `Element`| 標籤名稱。 |
| `EntityReference`| 參考的實體名稱。 |
| `ProcessingInstruction`| 處理指令的目標。 |
| [XmlDeclaration](../../xmldeclaration/)| 文字字串 `xml`。 |

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)