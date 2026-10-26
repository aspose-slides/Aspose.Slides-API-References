---
title: LinkEmbedDecision
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد كيفية معالجة الكائن أثناء الحفظ.
type: docs
weight: 911
url: /ar/aspose.slides.export/linkembeddecision/
---
## تعداد LinkEmbedDecision

يحدد كيفية معالجة الكائن أثناء الحفظ.

```cpp
enum class LinkEmbedDecision
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Link | 0 | سيتم تخزين الكائن خارجيًا، مع الإشارة إليه عبر URL |
| Embed | 1 | يجب تضمين الكائن في ملف مُولَّد إذا أمكن. إذا كان التضمين غير ممكن، سيُستدعى GetUrl، وبحسب النتيجة، سيتم الإشارة إلى الكائن عبر URL أو تجاهله. |
| Ignore | 2 | سيتم تجاهل الكائن. |

## انظر أيضًا

* النطاق [Aspose::Slides::Export](../)
* المكتبة [Aspose.Slides](../../)