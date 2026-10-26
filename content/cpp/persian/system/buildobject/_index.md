---
title: BuildObject()
second_title: مرجع API Aspose.Slides برای C++
description: یک شیء را با مالکیت مشترک می‌سازد.
type: docs
weight: 2250
url: /fa/system/buildobject/
---
## System::BuildObject(Args\&&...) تابع


یک شیء با مالکیت مشترک می‌سازد.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T, SharedPtr<T>> System::BuildObject(Args &&... args)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | Type of object to build |
| Args | Argument types for object construction |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| args | Args\&&... | Arguments to forward to object constructor |

### مقدار بازگشتی

ObjectBuilder پیکربندی شده برای ساختن shared pointer construction
## توضیحات



یک SharedPtr<T> می‌سازد و یک builder برای آن باز می‌گرداند 
[Object](../object/) construction must be finished with [Get()](../get/) call 

## موارد مرتبط

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)