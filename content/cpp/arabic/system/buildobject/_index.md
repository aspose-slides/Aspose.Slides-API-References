---
title: BuildObject()
second_title: Aspose.Slides للـ C++ مرجع API
description: إنشاء كائن بملكية مشتركة.
type: docs
weight: 2250
url: /ar/system/buildobject/
---
## System::BuildObject(Args\&&...) دالة

Build an object with shared ownership.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T, SharedPtr<T>> System::BuildObject(Args &&... args)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع الكائن الذي سيتم بناؤه |
| Args | أنواع الوسائط لإنشاء الكائن |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| args | Args\&&... | الوسائط التي ستمرر إلى منشئ الكائن |

### قيمة الإرجاع

ObjectBuilder مُكوَّن لإنشاء مؤشر مشترك

## ملاحظات

Creates a SharedPtr<T> and returns a builder for it 
[Object](../object/) يجب إكمال الإنشاء بـ [Get()](../get/) استدعاء

## انظر أيضًا

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)