---
title: InitObject()
second_title: مرجع API Aspose.Slides برای C++
description: آغاز مقداردهی اولیه یک شیء با مالکیت مشترک.
type: docs
weight: 2263
url: /fa/system/initobject/
---
## System::InitObject(const SharedPtr\<T\>\&) function

آغاز مقداردهی اولیه یک شیء با مالکیت مشترک.

```cpp
template<typename T> Details::ObjectBuilder<T, SharedPtr<T>> System::InitObject(const SharedPtr<T> &object)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع شیء برای مقداردهی اولیه |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | [Object](../object/) برای مقداردهی اولیه |

### مقدار بازگشت

ObjectBuilder پیکربندی شده برای ساخت اشاره‌گر مشترک

## توضیحات

[Object](../object/) مقداردهی اولیه باید با فراخوانی [Get()](../get/) تمام شود

## موارد مرتبط

* Typedef [SharedPtr](../sharedptr/)
* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)