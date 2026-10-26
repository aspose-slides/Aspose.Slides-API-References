---
title: FindAll()
second_title: مرجع API Aspose.Slides برای C++
description: تمام عناصری را که با شرایط تعریف‌شده توسط پیش‌شرط مشخص شده مطابقت دارند، برمی‌گرداند.
type: docs
weight: 664
url: /fa/system/array/findall/
---
## Array::FindAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) method


تمام عناصری را که با شرایط تعریف‌شده توسط پیش‌شرط مشخص شده مطابقت دارند، برمی‌گرداند.

```cpp
static System::ArrayPtr<T> System::Array<T>::FindAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) برای جستجوی عناصر در |
| match | [System::Predicate](../../predicate/)\<T\> | یک پیش‌شرط که شرایط مطابقت عناصر آرایه را تعریف می‌کند |

### مقدار بازگشت

یک [Array](../) حاوی تمام عناصری که شرایط تعریف‌شده توسط پیش‌شرط مشخص شده را برآورده می‌کنند، اگر یافت شود؛ در غیر این صورت، یک [Array](../) خالی.

## موارد مرتبط

* تعریف نوع [ArrayPtr](../../arrayptr/)
* تعریف نوع [Predicate](../../predicate/)
* کلاس [Array](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)