---
title: ToArray()
second_title: مرجع API لـ Aspose.Slides لـ C++
description: ينشئ ويرجع مصفوفة تحتوي على جميع الخطوط الاحتياطية لهذه القاعدة.
type: docs
weight: 105
url: /ar/aspose.slides/ifontfallbackrule/toarray/
---
## IFontFallBackRule::ToArray() طريقة


ينشئ ويرجع مصفوفة تحتوي على جميع الخطوط الاحتياطية لهذا القاعدة.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray()=0
```


### قيمة الإرجاع

مصفوفة من [System::String](../../../system/string/)
## ملاحظات



```cpp
// إنشاء قاعدة تحتوي على قائمة من الخطوط.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//احصل على جميع أسماء الخطوط كمصفوفة
ArrayPtr<String> fontNames = newRule->ToArray();
```


## IFontFallBackRule::ToArray(int32_t, int32_t) طريقة


ينشئ ويرجع مصفوفة تحتوي على جميع الخطوط الاحتياطية من النطاق المحدد في القائمة.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray(int32_t startIndex, int32_t count)=0
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| startIndex | **int32_t** | فهرس أول خط للإضافة. |
| count | **int32_t** | عدد الخطوط للإضافة. |

### قيمة الإرجاع

مصفوفة من [System::String](../../../system/string/)
## ملاحظات



```cpp
// إنشاء قاعدة تحتوي على قائمة من الخطوط.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//احصل على آخر اسمين للخطوط كمصفوفة
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```


## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [String](../../../system/string/)
* فئة [IFontFallBackRule](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)