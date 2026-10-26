---
title: ToArray()
second_title: Aspose.Slides للغة C++ مرجع API
description: ينشئ ويعيد مصفوفة تحتوي على جميع خطوط FallBack لهذه القاعدة.
type: docs
weight: 144
url: /ar/aspose.slides/fontfallbackrule/toarray/
---
## FontFallBackRule::ToArray() طريقة

ينشئ ويعيد مصفوفة تحتوي على جميع خطوط FallBack لهذا القاعدة.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray() override
```

### قيمة الإرجاع

مصفوفة من [System::String](../../../system/string/)
## ملاحظات

```cpp
// إنشاء قاعدة تحتوي على قائمة من الخطوط.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// احصل على جميع أسماء الخطوط كمصفوفة.
ArrayPtr<String> fontNames = newRule->ToArray();
```

## FontFallBackRule::ToArray(int32_t, int32_t) طريقة

ينشئ ويعيد مصفوفة تحتوي على جميع خطوط FallBack من النطاق المحدد في القائمة.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray(int32_t startIndex, int32_t count) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| startIndex | **int32_t** | فهرس الخط الأول لإضافته. |
| count | **int32_t** | عدد الخطوط لإضافتها. |

### قيمة الإرجاع

مصفوفة من [System::String](../../../system/string/)
## ملاحظات

```cpp
// إنشاء قاعدة تحتوي على قائمة من الخطوط.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// احصل على آخر اسمين للخطوط كمصفوفة.
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [String](../../../system/string/)
* فئة [FontFallBackRule](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)