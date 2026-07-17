---
title: XmlOutputMethod
second_title: Aspose.Slides for C++ API 参考
description: 指定用于序列化 XmlWriter 输出的方法。
type: docs
weight: 846
url: /zh/system.xml/xmloutputmethod/
---
## XmlOutputMethod 枚举

指定用于序列化 [XmlWriter](../xmlwriter/) 输出的方法。

```cpp
enum class XmlOutputMethod
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Xml | 0 | 根据 XML 1.0 规则进行序列化。 |
| Html | 1 | 根据 XSLT 指定的 HTML 规则进行序列化。 |
| Text | 2 | 仅对文本块进行序列化。 |
| AutoDetect | 3 | 在运行时使用 XSLT 规则在 [XmlOutputMethod::Xml](./) 和 [XmlOutputMethod::Html](./) 输出方法之间进行选择。 |

## 另见

* 命名空间 [System::Xml](../)
* 库 [Aspose.Slides](../../)