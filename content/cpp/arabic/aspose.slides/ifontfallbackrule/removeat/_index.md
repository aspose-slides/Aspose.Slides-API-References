---
title: RemoveAt()
second_title: Aspose.Slides للغة C++ مرجع API
description: يزيل خط FallBack عند الفهرس المحدد في القائمة.
type: docs
weight: 92
url: /ar/aspose.slides/ifontfallbackrule/removeat/
---
## IFontFallBackRule::RemoveAt(int32_t) طريقة

يزيل خط FallBack عند الفهرس المحدد في القائمة.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::RemoveAt(int32_t index)=0
```

### Arguments

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري للخط المراد إزالته. |
## ملاحظات

```cpp
// إنشاء قاعدة تحتوي على قائمة من الخطوط.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//إزالة Tahoma من القائمة
newRule->RemoveAt(2);
```

## انظر أيضًا

* فئة [IFontFallBackRule](../)
* مساحة الأسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)