---
title: WriteDocType()
second_title: Aspose.Slides for C++ API 参考
description: 当在派生类中被重写时，写入带有指定名称和可选属性的 DOCTYPE 声明。
type: docs
weight: 79
url: /zh/system.xml/xmlwriter/writedoctype/
---
## XmlWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) 方法

当在派生类中被重写时，写入带有指定名称和可选属性的 DOCTYPE 声明。

```cpp
virtual void System::Xml::XmlWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | DOCTYPE 的名称。此值必须非空。 |
| pubid | const [String](../../../system/string/)\& | 如果非空，它还会写入 PUBLIC \"pubid\" \"sysid\"，其中 **pubid** 和 **sysid** 将被给定参数的值替换。 |
| sysid | const [String](../../../system/string/)\& | 如果 **pubid** 为 **nullptr** 且 **sysid** 为非空，它写入 SYSTEM \"sysid\"，其中 **sysid** 将被该参数的值替换。 |
| subset | const [String](../../../system/string/)\& | 如果非空，它写入 [subset]，其中 subset 将被该参数的值替换。 |

## 另请参阅

* 类 [String](../../../system/string/)
* 类 [XmlWriter](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)