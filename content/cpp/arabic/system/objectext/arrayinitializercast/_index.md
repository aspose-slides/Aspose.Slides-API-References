---
title: ArrayInitializerCast()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يقوم بتحويل القيم الأساسية للمصفوفة (التي يقوم C# بتحويلها ضمنيًا لكن C++ يبدو أنه لا يفعل ذلك).
type: docs
weight: 209
url: /ar/system/objectext/arrayinitializercast/
---
## ObjectExt::ArrayInitializerCast(From ...) طريقة

يقوم بتحويل القيم الأساسية للمصفوفة (التي يقوم C# بتحويلها ضمنيًا لكن C++ يبدو أنه لا يفعل ذلك).

```cpp
template<typename To,typename ...> static std::enable_if<(std::is_fundamental<To>::value), std::array<To, sizeof...(From)>>::type System::ObjectExt::ArrayInitializerCast(From ...args)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| To | نوع الهدف. |
| From | أنواع المصدر. |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| args | From ... | القيم التي سيتم تحويلها ودفعها إلى مصفوفة الهدف. |

### قيمة الإرجاع

[Array](../../array/) يحتوي على نسخ محوّلة من جميع المعطيات بنفس الترتيب.

## انظر أيضا

* الفئة [ObjectExt](../)
* النطاق [System](../../)
* المكتبة [Aspose.Slides](../../../)