---
title: Remove()
second_title: Aspose.Slides لـ C++ مرجع API
description: يزيل أول ظهور لخط FallBack محدد من القائمة.
type: docs
weight: 79
url: /ar/aspose.slides/ifontfallbackrule/remove/
---
## IFontFallBackRule::Remove(System::String) طريقة

يزيل أول ظهور لخط FallBack محدد من القائمة.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::Remove(System::String fontName)=0
```

### المُدخلات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | اسم الخط لإزالته من القائمة. |

## ملاحظات

```cpp
// إنشاء قاعدة تحتوي على قائمة من الخطوط.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//إزالة Tahoma من القائمة
newRule->Remove(u"Tahoma");
```

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [IFontFallBackRule](../)
* مساحة الأسماء [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)