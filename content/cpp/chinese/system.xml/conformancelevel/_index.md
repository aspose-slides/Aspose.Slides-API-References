---
title: ConformanceLevel
second_title: Aspose.Slides for C++ API 参考
description: 指定 XmlReader 和 XmlWriter 对象执行的输入或输出检查的程度。
type: docs
weight: 625
url: /zh/system.xml/conformancelevel/
---
## ConformanceLevel 枚举

指定 [XmlReader](../xmlreader/) 和 [XmlWriter](../xmlwriter/) 对象执行的输入或输出检查的程度。

```cpp
enum class ConformanceLevel
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Auto | 0 | [XmlReader](../xmlreader/) 或 [XmlWriter](../xmlwriter/) 对象会自动检测应执行文档级还是片段级检查，并进行相应的检查。如果您正在包装另一个 [XmlReader](../xmlreader/) 或 [XmlWriter](../xmlwriter/) 对象，外层对象不会进行额外的符合性检查。符合性检查交由底层对象处理。 |
| Fragment | 1 | XML 数据是 [well-formed XML fragment](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities)，如 W3C 所定义。此符合性级别表示可能没有根元素但其他方面结构良好的 XML 文档。该级别的检查确保读取或写入的流可以被任何处理器作为 [XML 1.0 external parsed entity](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities) 消费。 |
| Document | 2 | XML 数据符合 W3C 所定义的良好结构 [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed) 规则。该级别的检查确保读取或写入的流可以被任何处理器作为 [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed) 消费。 |

## 另请参见

* 命名空间 [System::Xml](../)
* 库 [Aspose.Slides](../../)