---
title: XmlKnownDtds
second_title: Aspose.Slides for C++ API 參考
description: "Resolvers::XmlKnownDtds 列舉由 Resolvers::XmlPreloadedResolver 使用，並定義 Resolvers::XmlPreloadedResolver 可辨識的已知 DTD。"
type: docs
weight: 14
url: /zh-hant/system.xml.resolvers/xmlknowndtds/
---
## XmlKnownDtds 列舉

The [Resolvers::XmlKnownDtds](./) 列舉由 [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) 使用，並定義 [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) 可辨識的哪些已知 DTD。

```cpp
enum class XmlKnownDtds
```

### 值

| 名稱 | 值 | 描述 |
| --- | --- | --- |
| None | 0 | 指定 [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) 不會識別任何預先定義的 DTD。 |
| Xhtml10 | 1 | 指定 [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) 將會識別在 XHTML 1.0 中定義的 DTD 和實體。 |
| Rss091 | 2 | 指定 [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) 將會識別在 RSS 0.91 中定義的 DTD 和實體。 |
| All | 65535 | 指定 [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) 將會識別所有目前支援的 DTD。這是預設行為。 |

## 另見

* 命名空間 [System::Xml::Resolvers](../)
* 函式庫 [Aspose.Slides](../../)