---
title: Build()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: إنشاء كائن بملكية مباشرة.
type: docs
weight: 2289
url: /ar/system/build/
---
## System::Build(Args\&&...) دالة

إنشاء كائن بملكية مباشرة.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T> System::Build(Args &&... args)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | نوع الكائن لإنشائه |
| Args | أنواع المعاملات لإنشاء الكائن |

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| args | Args\&&... | الوسائط لتمريرها إلى مُنشئ الكائن |

### قيمة الإرجاع

ObjectBuilder مُكوَّن لإنشاء كائن مباشر

## ملاحظات

[Object](../object/) يجب أن ينتهي الإنشاء بـ [Get()](../get/)

## انظر أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)