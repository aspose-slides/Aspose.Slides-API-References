---
title: ToArray()
second_title: Aspose.Slides برای C++ مرجع API
description: یک آرایه ایجاد می‌کند و باز می‌گرداند که شامل تمام شکل‌ها است.
type: docs
weight: 326
url: /fa/aspose.slides/shapecollection/toarray/
---
## ShapeCollection::ToArray() متد

یک آرایه ایجاد می‌کند و بازمی‌گرداند که شامل تمام شکل‌ها است.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray() override
```

### مقدار بازگشتی

یک آرایه از اشیاء [IShape](../../ishape/).

## ShapeCollection::ToArray(int32_t, int32_t) متد

یک آرایه ایجاد می‌کند و بازمی‌گرداند که شامل تمام شکل‌ها در بازهٔ مشخص شده است.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray(int32_t startIndex, int32_t count) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| startIndex | **int32_t** | اندیس اولین شکلی که باید بازگردانده شود. |
| count | **int32_t** | تعداد شکل‌هایی که باید بازگردانده شوند. |

### مقدار بازگشتی

یک آرایه از اشیاء [IShape](../../ishape/).

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IShape](../../ishape/)
* کلاس [ShapeCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)