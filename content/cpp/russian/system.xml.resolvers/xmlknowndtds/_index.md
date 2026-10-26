---
title: XmlKnownDtds
second_title: Aspose.Slides для C++ API Reference
description: "Перечисление Resolvers::XmlKnownDtds используется Resolvers::XmlPreloadedResolver и определяет, какие известные DTD распознает Resolvers::XmlPreloadedResolver."
type: docs
weight: 14
url: /ru/system.xml.resolvers/xmlknowndtds/
---
## XmlKnownDtds enum


Перечисление [Resolvers::XmlKnownDtds](./) используется [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) и определяет, какие известные DTD распознаёт [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/).

```cpp
enum class XmlKnownDtds
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | Указывает, что [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) не будет распознавать ни один из предопределённых DTD. |
| Xhtml10 | 1 | Указывает, что [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) будет распознавать DTD и сущности, определённые в XHTML 1.0. |
| Rss091 | 2 | Указывает, что [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) будет распознавать DTD и сущности, определённые в RSS 0.91. |
| All | 65535 | Указывает, что [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) будет распознавать все в данный момент поддерживаемые DTD. Это поведение по умолчанию. |

## See Also

* Пространство имен [System::Xml::Resolvers](../)
* Библиотека [Aspose.Slides](../../)