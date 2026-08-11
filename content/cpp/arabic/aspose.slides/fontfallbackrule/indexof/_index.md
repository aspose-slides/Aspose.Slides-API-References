---
title: IndexOf()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يعيد فهرس القاعدة المحددة في المجموعة.
type: docs
weight: 157
url: /ar/aspose.slides/fontfallbackrule/indexof/
---
## FontFallBackRule::IndexOf(System::String) طريقة

يعيد فهرس القاعدة المحددة في المجموعة.

```cpp
int32_t Aspose::Slides::FontFallBackRule::IndexOf(System::String fontName) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | اسم الخط للبحث عنه. |

### قيمة الإرجاع

فهرس الخط أو -1 إذا لم يتم العثور على الخط في القائمة.

## ملاحظات

```cpp
// إنشاء قاعدة تحتوي على قائمة خطوط.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// الحصول على فهرس Tahoma.
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [FontFallBackRule](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)