---
title: XmlKnownDtds
second_title: Aspose.Slides pro C++ - dokumentace API
description: "Výčet Resolvers::XmlKnownDtds je používán Resolvers::XmlPreloadedResolver a určuje, které dobře známé DTD jsou rozpoznávány Resolvers::XmlPreloadedResolver."
type: docs
weight: 14
url: /cs/system.xml.resolvers/xmlknowndtds/
---
## XmlKnownDtds enumerace

Výčet [Resolvers::XmlKnownDtds](./) je používán [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) a určuje, které dobře známé DTD jsou rozpoznávány [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/).

```cpp
enum class XmlKnownDtds
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| None | 0 | Určuje, že [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) nebude rozpoznávat žádné z předdefinovaných DTD. |
| Xhtml10 | 1 | Určuje, že [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) bude rozpoznávat DTD a entity definované v XHTML 1.0. |
| Rss091 | 2 | Určuje, že [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) bude rozpoznávat DTD a entity definované v RSS 0.91. |
| All | 65535 | Určuje, že [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) bude rozpoznávat všechny aktuálně podporované DTD. Toto je výchozí chování. |

## Viz také

* Jmenný prostor [System::Xml::Resolvers](../)
* Knihovna [Aspose.Slides](../../)