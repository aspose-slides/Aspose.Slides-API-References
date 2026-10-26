---
title: IndexOf()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يعيد فهرس القاعدة المحددة في المجموعة.
type: docs
weight: 118
url: /ar/aspose.slides/ifontfallbackrule/indexof/
---
## IFontFallBackRule::IndexOf(System::String) طريقة


يُرجع فهرس القاعدة المحددة في المجموعة.

```cpp
virtual int32_t Aspose::Slides::IFontFallBackRule::IndexOf(System::String fontName)=0
```


### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | اسم الخط للبحث عنه. |

### قيمة الإرجاع

فهرس الخط أو -1 إذا لم يتم العثور على الخط في القائمة.
## ملاحظات



```cpp
// إنشاء قاعدة تحتوي على قائمة من الخطوط.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//احصل على فهرس Tahoma
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```


## انظر أيضاً

* الفئة [String](../../../system/string/)
* الفئة [IFontFallBackRule](../)
* فضاء الاسم [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)