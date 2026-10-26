---
title: XmlKnownDtds
second_title: Aspose.Slides for C++ API 参考
description: "Resolvers::XmlKnownDtds 枚举由 Resolvers::XmlPreloadedResolver 使用，并定义了 Resolvers::XmlPreloadedResolver 可以识别的已知 DTD。"
type: docs
weight: 14
url: /zh/system.xml.resolvers/xmlknowndtds/
---
## XmlKnownDtds 枚举

[Resolvers::XmlKnownDtds](./) 枚举由 [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) 使用，并定义了 [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) 可以识别的已知 DTD。

```cpp
enum class XmlKnownDtds
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | 0 | 指定 [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) 不会识别任何预定义的 DTD。 |
| Xhtml10 | 1 | 指定 [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) 将识别在 XHTML 1.0 中定义的 DTD 和实体。 |
| Rss091 | 2 | 指定 [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) 将识别在 RSS 0.91 中定义的 DTD 和实体。 |
| All | 65535 | 指定 [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) 将识别所有当前支持的 DTD。这是默认行为。 |

## 另见

* 命名空间 [System::Xml::Resolvers](../)
* 库 [Aspose.Slides](../../)