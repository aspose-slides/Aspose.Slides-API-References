---
title: MeasureCharacterRanges()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يعيد مصفوفة من المناطق، كل منها يحد مواضع الأحرف في السلسلة المحددة.
type: docs
weight: 508
url: /ar/system.drawing/graphics/measurecharacterranges/
---
## Graphics::MeasureCharacterRanges(const System::String&, const SharedPtr\<Font\>\&, RectangleF, const SharedPtr\<StringFormat\>\&) طريقة

تُرجِع مصفوفة من المناطق، كل منها يحدّ مواضع الأحرف في السلسلة المحددة.

```cpp
ArrayPtr<SharedPtr<Region>> System::Drawing::Graphics::MeasureCharacterRanges(const System::String &text, const SharedPtr<Font> &font, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | السلسلة التي سيتم قياسها |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | الخط المستخدم أثناء قياس السلسلة |
| layoutRect | [RectangleF](../../rectanglef/) | مستطيل التخطيط المستخدم أثناء قياس السلسلة |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\>\& | تنسيق السلسلة، يحتوي على نطاقات الأحرف التي ستقاس |

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [Region](../../region/)
* فئة [String](../../../system/string/)
* فئة [Font](../../font/)
* فئة [RectangleF](../../rectanglef/)
* فئة [StringFormat](../../stringformat/)
* فئة [Graphics](../)
* مساحة الاسم [System::Drawing](../../)
* مكتبة [Aspose.Slides](../../../)