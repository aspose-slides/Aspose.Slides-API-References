---
title: XmlSchemaContentProcessing
second_title: Aspose.Slides for C++ API 参考
description: 提供有关 any 和 anyAttribute 元素替换的验证模式的信息。
type: docs
weight: 976
url: /zh/system.xml.schema/xmlschemacontentprocessing/
---
## XmlSchemaContentProcessing 枚举

提供有关 **any** 和 **anyAttribute** 元素替换的验证模式的信息。

```cpp
enum class XmlSchemaContentProcessing
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | 0 | 文档项未进行验证。 |
| Skip | 1 | 文档项必须是良构 XML，并且不由模式验证。 |
| Lax | 2 | 如果找到关联的模式，文档项将被验证。否则不会抛出错误。 |
| Strict | 3 | 模式处理器必须找到与指示的命名空间关联的模式，以验证文档项。 |

## 另见

* 命名空间 [System::Xml::Schema](../)
* 库 [Aspose.Slides](../../)