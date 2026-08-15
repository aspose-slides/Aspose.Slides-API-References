---
title: MoveToContent()
second_title: Aspose.Slides C++ API 參考
description: "檢查目前節點是否為內容（非空白文字、CDATA、Element、EndElement、EntityReference，或 EndEntity）節點。如果節點不是內容節點，讀取器會跳至下一個內容節點或檔案結尾。它會跳過以下類型的節點：ProcessingInstruction、DocumentType、Comment、Whitespace 或 SignificantWhitespace。"
type: docs
weight: 833
url: /zh-hant/system.xml/xmlreader/movetocontent/
---
## XmlReader::MoveToContent() 方法


檢查目前節點是否為內容（非空白字元文字、**CDATA**、**Element**、**EndElement**、**EntityReference** 或 **EndEntity**）節點。如果節點不是內容節點，讀取器會跳過至下一個內容節點或檔案結尾。它會跳過以下類型的節點：**ProcessingInstruction**、**DocumentType**、**Comment**、**Whitespace** 或 **SignificantWhitespace**。

```cpp
virtual XmlNodeType System::Xml::XmlReader::MoveToContent()
```


### 返回值

此方法找到的目前節點的 [XmlReader::get_NodeType](../get_nodetype/) 值，若讀取器已達到輸入串流的結尾，則為 [XmlNodeType::None](../../xmlnodetype/)。

## 另見

* 列舉 [XmlNodeType](../../xmlnodetype/)
* 類別 [XmlReader](../)
* 命名空間 [System::Xml](../../)
* 程式庫 [Aspose.Slides](../../../)