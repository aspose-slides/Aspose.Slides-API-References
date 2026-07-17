---
title: WriteStartElement()
second_title: Aspose.Slides for C++ API 参考
description: 写入指定的起始标签，并将其与给定的命名空间和前缀关联。
type: docs
weight: 235
url: /zh/system.xml/xmltextwriter/writestartelement/
---
## XmlTextWriter::WriteStartElement(const String\&, const String\&, const String\&) 方法

写入指定的起始标签，并将其与给定的命名空间和前缀关联。

```cpp
void System::Xml::XmlTextWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 元素的命名空间前缀。 |
| localName | const [String](../../../system/string/)\& | 元素的本地名称。 |
| ns | const [String](../../../system/string/)\& | 与元素关联的命名空间 URI。如果此命名空间已经在作用域内且已有关联的前缀，则写入器会自动写入该前缀。 |

## 另请参见

* 类 [String](../../../system/string/)
* 类 [XmlTextWriter](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)