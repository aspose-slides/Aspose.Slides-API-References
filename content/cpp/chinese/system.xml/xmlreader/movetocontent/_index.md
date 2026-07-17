---
title: MoveToContent()
second_title: Aspose.Slides C++ API 参考
description: "检查当前节点是否为内容节点（非空白文本、CDATA、Element、EndElement、EntityReference 或 EndEntity）。如果节点不是内容节点，阅读器会跳过并前进到下一个内容节点或文件结束。它会跳过以下类型的节点：ProcessingInstruction、DocumentType、Comment、Whitespace 或 SignificantWhitespace。"
type: docs
weight: 833
url: /zh/system.xml/xmlreader/movetocontent/
---
## XmlReader::MoveToContent() 方法

检查当前节点是否为内容节点（非空白文本、**CDATA**、**Element**、**EndElement**、**EntityReference** 或 **EndEntity**）。如果节点不是内容节点，阅读器会跳过并前进到下一个内容节点或文件结束。它会跳过以下类型的节点：**ProcessingInstruction**、**DocumentType**、**Comment**、**Whitespace** 或 **SignificantWhitespace**。

```cpp
virtual XmlNodeType System::Xml::XmlReader::MoveToContent()
```

### 返回值

方法找到的当前节点的[XmlReader::get_NodeType](../get_nodetype/)值，或者如果阅读器已到达输入流的末尾，则为[XmlNodeType::None](../../xmlnodetype/)。

## 另请参见

* 枚举 [XmlNodeType](../../xmlnodetype/)
* 类 [XmlReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)