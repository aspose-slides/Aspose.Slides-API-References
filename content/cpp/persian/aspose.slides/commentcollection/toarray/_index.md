---
title: ToArray()
second_title: مرجع API Aspose.Slides برای C++
description: یک آرایه شامل تمام نظرات را ایجاد و برمی‌گرداند.
type: docs
weight: 105
url: /fa/aspose.slides/commentcollection/toarray/
---
## CommentCollection::ToArray() متد

یک آرایه شامل تمام نظرات را ایجاد و برمی‌گرداند.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray() override
```

### مقدار بازگشت

آرایه‌ای از [Comment](../../comment/).

## CommentCollection::ToArray(int32_t, int32_t) متد

یک آرایه شامل تمام نظرات از بازه مشخص‌شده را ایجاد و برمی‌گرداند.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray(int32_t startIndex, int32_t count) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| startIndex | **int32_t** | اندیس اولین نظر برای برگرداندن. |
| count | **int32_t** | تعداد نظراتی که باید برگردانده شوند. |

### مقدار بازگشت

آرایه‌ای از [Comment](../../comment/).

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IComment](../../icomment/)
* کلاس [CommentCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)