---
title: InitObject()
second_title: Aspose.Slides لـ C++ مرجع API
description: يبدأ تهيئة كائن مع ملكية مشتركة.
type: docs
weight: 2263
url: /ar/system/initobject/
---
## System::InitObject(const SharedPtr\<T\>\&) function

يبدأ تهيئة كائن مع ملكية مشتركة.

```cpp
template<typename T> Details::ObjectBuilder<T, SharedPtr<T>> System::InitObject(const SharedPtr<T> &object)
```

### معاملات القالب

| Parameter | Description |
| --- | --- |
| T | Type of object to initialize |

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | [Object](../object/) to initialize |

## قيمة الإرجاع

ObjectBuilder مكوّن لإنشاء مؤشرات مشتركة

## ملاحظات

[Object](../object/) يجب إكمال التهيئة باستخدام استدعاء [Get()](../get/)

## انظر أيضًا

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)