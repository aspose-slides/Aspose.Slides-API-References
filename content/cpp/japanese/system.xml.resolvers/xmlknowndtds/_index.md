---
title: XmlKnownDtds
second_title: Aspose.Slides for C++ API リファレンス
description: "Resolvers::XmlKnownDtds 列挙体は Resolvers::XmlPreloadedResolver によって使用され、Resolvers::XmlPreloadedResolver が認識する既知の DTD を定義します。"
type: docs
weight: 14
url: /ja/system.xml.resolvers/xmlknowndtds/
---
## XmlKnownDtds 列挙体

[Resolvers::XmlKnownDtds](./) 列挙体は [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) で使用され、[Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) が認識する既知の DTD を定義します。

```cpp
enum class XmlKnownDtds
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | 0 | [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) が事前定義された DTD を認識しないことを指定します。 |
| Xhtml10 | 1 | [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) が XHTML 1.0 で定義された DTD とエンティティを認識することを指定します。 |
| Rss091 | 2 | [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) が RSS 0.91 で定義された DTD とエンティティを認識することを指定します。 |
| All | 65535 | [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) が現在サポートされているすべての DTD を認識することを指定します。これは既定の動作です。 |

## 参照

* 名前空間 [System::Xml::Resolvers](../)
* ライブラリ [Aspose.Slides](../../)