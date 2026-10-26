---
title: XmlKnownDtds
second_title: مرجع API Aspose.Slides للـ C++
description: "التعداد Resolvers::XmlKnownDtds يُستخدم بواسطة Resolvers::XmlPreloadedResolver ويحدد أي من DTDs المعروفة التي يتعرف عليها Resolvers::XmlPreloadedResolver."
type: docs
weight: 14
url: /ar/system.xml.resolvers/xmlknowndtds/
---
## XmlKnownDtds enum

The [Resolvers::XmlKnownDtds](./) enumeration is used by the [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) and defines which well-known DTDs that the [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) recognizes.

```cpp
enum class XmlKnownDtds
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| None | 0 | يحدد أن [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) لن يتعرف على أي من DTDs المحددة مسبقًا. |
| Xhtml10 | 1 | يحدد أن [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) سيتعرف على DTDs والكيانات المعرفة في XHTML 1.0. |
| Rss091 | 2 | يحدد أن [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) سيتعرف على DTDs والكيانات المعرفة في RSS 0.91. |
| All | 65535 | يحدد أن [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) سيتعرف على جميع DTDs المدعومة حاليًا. هذا هو السلوك الافتراضي. |

## انظر أيضًا

* النطاق [System::Xml::Resolvers](../)
* المكتبة [Aspose.Slides](../../)