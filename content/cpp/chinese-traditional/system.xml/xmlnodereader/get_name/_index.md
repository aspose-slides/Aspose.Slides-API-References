---
title: get_Name()
second_title: Aspose.Slides for C++ API 參考
description: 傳回目前節點的限定名稱。
type: docs
weight: 14
url: /zh-hant/system.xml/xmlnodereader/get_name/
---
## XmlNodeReader::get_Name() 方法


傳回目前節點的限定名稱。

```cpp
String System::Xml::XmlNodeReader::get_Name() override
```


### 回傳值

目前節點的限定名稱。例如，**Name** 為 **bk:book**，對應元素 **<bk:book>**。

## 備註



回傳的名稱取決於節點的 [XmlNodeReader::get_NodeType](../get_nodetype/) 值。以下節點類型會回傳所列的值。所有其他節點類型則回傳空字串。 

| 節點類型 | 名稱 |
| --- | --- |
| [Attribute](../../../system/attribute/)| 屬性的名稱。 |
| DocumentType| 文件類型的名稱。 |
| Element| 標籤名稱。 |
| EntityReference| 參照的實體名稱。 |
| ProcessingInstruction| 處理指令的目標。 |
| [XmlDeclaration](../../xmldeclaration/)| 文字字串 `xml`。 |


## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlNodeReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)