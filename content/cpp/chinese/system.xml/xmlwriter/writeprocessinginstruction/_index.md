---
title: WriteProcessingInstruction()
second_title: Aspose.Slides for C++ API 参考
description: "当在派生类中重写时，写出一个处理指令，在名称和文本之间有空格，如下所示：<?name text?>。"
type: docs
weight: 196
url: /zh/system.xml/xmlwriter/writeprocessinginstruction/
---
## XmlWriter::WriteProcessingInstruction(String, String) 方法

When overridden in a derived class, writes out a processing instruction with a space between the name and text as follows: **<?name text?>**.

```cpp
virtual void System::Xml::XmlWriter::WriteProcessingInstruction(String name, String text)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | The name of the processing instruction. |
| text | [String](../../../system/string/) | The text to include in the processing instruction. |
## 备注

此方法用于在已调用 [XmlWriter::WriteStartDocument](../writestartdocument/) 之后创建 XML 声明。 
## 另请参见

* 类 [String](../../../system/string/)
* 类 [XmlWriter](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)