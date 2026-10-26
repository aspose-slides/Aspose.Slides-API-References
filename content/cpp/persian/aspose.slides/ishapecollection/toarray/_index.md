---
title: ToArray()
second_title: مرجع API Aspose.Slides برای C++
description: یک آرایه ایجاد می‌کند که شامل تمام اشکال است و آن را برمی‌گرداند.
type: docs
weight: 287
url: /fa/aspose.slides/ishapecollection/toarray/
---
## IShapeCollection::ToArray() متد


آرایه‌ای ایجاد می‌کند که شامل همهٔ اشکال است و آن را برمی‌گرداند.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray()=0
```


### مقدار بازگشتی

آرایه‌ای از اشیاء [IShape](../../ishape/).

## IShapeCollection::ToArray(int32_t, int32_t) متد


آرایه‌ای ایجاد می‌کند که شامل تمام اشکال در بازهٔ مشخص شده است و آن را برمی‌گرداند.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray(int32_t startIndex, int32_t count)=0
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| startIndex | **int32_t** | شاخص اولین شکلی که باید برگردانده شود. |
| count | **int32_t** | تعداد اشکالی که باید برگردانده شوند. |

### مقدار بازگشتی

آرایه‌ای از اشیاء [IShape](../../ishape/).

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IShape](../../ishape/)
* کلاس [IShapeCollection](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)