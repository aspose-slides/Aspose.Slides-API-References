---
title: CompressionLevel
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد مستويات ضغط ZIP لملف OpenXML. المستويات الأعلى توفر ضغطًا أفضل على حساب معالجة أبطأ.
type: docs
weight: 846
url: /ar/aspose.slides.export/compressionlevel/
---
## CompressionLevel تعداد

يحدد مستويات ضغط ZIP لملف OpenXML. المستويات الأعلى توفر ضغطًا أفضل على حساب معالجة أبطأ.

```cpp
enum class CompressionLevel
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| None | 0 | لا يتم تطبيق أي ضغط. تُخزن الملفات كما هي. |
| Level1 | 1 | أسرع ضغط مع أدنى نسبة ضغط. |
| Level2 | 2 | ضغط أسرع مع نسبة ضغط أفضل قليلاً من [CompressionLevel::Level1](./). |
| Level3 | 3 | يوفر ضغطًا أفضل من [CompressionLevel::Level2](./) مع تأثير متوسط على الأداء. |
| Level4 | 4 | يوفر ضغطًا أفضل من [CompressionLevel::Level3](./). |
| Level5 | 5 | يوفر ضغطًا محسّنًا مقارنةً بـ [CompressionLevel::Level4](./) مع وقت معالجة إضافي. |
| Level6 | 6 | ضغط قياسي، يقدم توازنًا جيدًا بين سرعة الضغط وحجم الملف. مستوى الضغط الافتراضي. |
| Level7 | 7 | يوفر ضغطًا أعلى من [CompressionLevel::Level6](./) مع معالجة أبطأ. |
| Level8 | 8 | يوفر ضغطًا أعلى من [CompressionLevel::Level7](./). |
| Level9 | 9 | أقصى ضغط. ينتج أصغر حجم ملف مع أبطأ سرعة معالجة. |

## انظر أيضًا

* مساحة الاسم [Aspose::Slides::Export](../)
* مكتبة [Aspose.Slides](../../)