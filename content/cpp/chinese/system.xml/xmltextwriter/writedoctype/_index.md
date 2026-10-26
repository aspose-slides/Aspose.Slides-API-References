---
title: WriteDocType()
second_title: Aspose.Slides C++ API 参考
description: 使用指定的名称和可选属性写入 DOCTYPE 声明。
type: docs
weight: 222
url: /zh/system.xml/xmltextwriter/writedoctype/
---
## XmlTextWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) 方法

使用指定的名称和可选属性写入 DOCTYPE 声明。

```cpp
void System::Xml::XmlTextWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | DOCTYPE 的名称。此字段必须非空。 |
| pubid | const [String](../../../system/string/)\& | 如果非空，它还会写入 PUBLIC \"pubid\" \"sysid\"，其中 **pubid** 和 **sysid** 将被给定参数的值替换。 |
| sysid | const [String](../../../system/string/)\& | 如果 **pubid** 为 null 且 **sysid** 为非空，它会写入 SYSTEM \"sysid\"，其中 **sysid** 将被此参数的值替换。 |
| subset | const [String](../../../system/string/)\& | 如果非空，它会写入 [subset]，其中 subset 被此参数的值替换。 |

## 参见

* 类 [String](../../../system/string/)
* 类 [XmlTextWriter](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)