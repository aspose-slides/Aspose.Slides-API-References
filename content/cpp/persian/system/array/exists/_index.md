---
title: Exists()
second_title: مرجع API Aspose.Slides برای C++
description: تعیین می‌کند که آیا شیء Array مشخص‌شده شامل عنصری است که الزامات پیش‌شرط مشخص‌شده را برآورده کند.
type: docs
weight: 781
url: /fa/system/array/exists/
---
## Array::Exists(ArrayPtr\<T\>, std::function\<bool(T)>) متد

تعیین می‌کند که آیا شی [Array](../) مشخص‌شده شامل عنصری است که الزامات پیش‌شرط مشخص‌شده را برآورده کند.

```cpp
static bool System::Array<T>::Exists(ArrayPtr<T> arr, std::function<bool(T)> match)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | آرایه‌ای که عنصر در آن جستجو می‌شود |
| match | std::function\<**bool**(T)> | شی تابعی که الزامات را تعریف می‌کند و بررسی می‌کند آیا عنصر آن‌ها را برآورده می‌کند |

### مقدار بازگشت

True اگر **arr** شامل عنصری باشد که الزامات تعریف‌شده توسط **match** را برآورده کند

## موارد مرتبط

* Typedef [ArrayPtr](../../arrayptr/)
* کلاس [Array](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)