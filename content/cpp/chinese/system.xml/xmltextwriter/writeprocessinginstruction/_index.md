---
title: WriteProcessingInstruction()
second_title: Aspose.Slides for C++ API 参考
description: "将处理指令写出，并在名称和文本之间留有一个空格，如下所示：<?name text?>。"
type: docs
weight: 326
url: /zh/system.xml/xmltextwriter/writeprocessinginstruction/
---
## XmlTextWriter::WriteProcessingInstruction(String, String) 方法

将处理指令写出，并在名称和文本之间留有一个空格，如下所示：**<?name text?>**。

```cpp
void System::Xml::XmlTextWriter::WriteProcessingInstruction(String name, String text) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | 处理指令的名称。 |
| text | [String](../../../system/string/) | [Text](../../../system.text/) 要包含在处理指令中。 |
## 备注

此方法用于在已调用 [XmlTextWriter::WriteStartDocument](../writestartdocument/) 之后创建 XML 声明。 
## 另见

* 类 [String](../../../system/string/)
* 类 [XmlTextWriter](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)