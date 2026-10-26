---
title: LINQ_FirstOrDefault()
second_title: Aspose.Slides برای C++ مرجع API
description: اولین عنصر یک دنباله را برمی‌گرداند، یا اگر دنباله خالی باشد مقدار پیش‌فرض را باز می‌گرداند.
type: docs
weight: 66
url: /fa/system.collections.generic/ienumerable/linq_firstordefault/
---
## IEnumerable::LINQ_FirstOrDefault() متد

اولین عنصر یک دنباله را برمی‌گرداند، یا اگر دنباله خالی باشد مقدار پیش‌فرض را باز می‌گرداند.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault()
```

### مقدار بازگشت

اولین عنصر در دنباله یا مقدار پیش‌ساخت‌ شده اگر دنباله خالی باشد.

## IEnumerable::LINQ_FirstOrDefault(std::function\<bool(T)>) متد

اولین عنصری از دنباله که شرطی را ارضا می‌کند برمی‌گرداند یا اگر چنین عنصری یافت نشود، مقدار پیش‌فرض را باز می‌گرداند.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault(std::function<bool(T)> predicate)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | تابعی برای آزمون هر عنصر نسبت به یک شرط. |

### مقدار بازگشت

default(T) اگر منبع خالی باشد یا هیچ عنصری آزمون تعیین‌شده توسط predicate را پاس نکند؛ در غیر این صورت، اولین عنصر در منبع که آزمون تعیین‌شده توسط predicate را پاس می‌کند.

## موارد مرتبط

* کلاس [IEnumerable](../)
* فضای نام [System::Collections::Generic](../../)
* کتابخانه [Aspose.Slides](../../../)