---
title: TrueForAll()
second_title: Aspose.Slides برای C++ مرجع API
description: مشخص می‌کند که آیا تمام عناصر موجود در آرایهٔ مشخص‌شده، شرایط تعریف‌شده توسط پیش‌شرط مشخص‌شده را برآورده می‌کنند یا خیر.
type: docs
weight: 677
url: /fa/system/array/trueforall/
---
## Array::TrueForAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) متد

تعیین می‌کند که آیا تمام عناصر موجود در آرایهٔ مشخص‌شده با شرایط تعریف‌شده توسط پیش‌شرط مشخص‌شده مطابقت دارند یا خیر.

```cpp
static bool System::Array<T>::TrueForAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### پارامترها
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) عناصری که باید با شرایط مطابقت داده شوند |
| match | [System::Predicate](../../predicate/)\<T\> | یک پیش‌شرط که شرایط مطابقت عناصر آرایه را تعریف می‌کند |

### مقدار بازگشت
در صورتی که تمام عناصر آرایه arr شرایط تعریف‌شده توسط پیش‌شرط match را برآورده کنند، true؛ در غیر این صورت false

## موارد مرتبط

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* کلاس [Array](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)