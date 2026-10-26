---
title: operator>()
second_title: مرجع API Aspose.Slides برای C++
description: همیشه مقدار false را برمی‌گرداند.
type: docs
weight: 157
url: /fa/system/nullable/operator_greater/
---
## Nullable::operator>(std::nullptr_t) const متد

همیشه مقدار false را برمی‌گرداند.

```cpp
bool System::Nullable<T>::operator>(std::nullptr_t) const
```

## Nullable::operator>(const T1\&) const متد

تعیین می‌کند آیا مقدار نمایان‌شده توسط شیء فعلی بزرگ‌تر از مقدار مشخص‌شده است با اعمال [operator>()](./) بر این مقادیر.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>(const T1 &other) const
```

### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع مقدار برای مقایسه |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| other | const T1\& | یک مرجع ثابت به مقدار برای مقایسه |

### مقدار برگشت

در صورتی که مقدار نمایان‌شده توسط شیء فعلی بزرگ‌تر از مقدار مشخص‌شده باشد، true؛ در غیر این صورت - false

## Nullable::operator>(const Nullable\<T1\>\&) const متد

تعیین می‌کند آیا مقدار نمایان‌شده توسط شیء فعلی بزرگ‌تر از مقدار نمایان‌شده توسط شیء [Nullable](../) مشخص‌شده است با اعمال [operator>()](./) بر این مقادیر.

```cpp
template<typename T1> bool System::Nullable<T>::operator>(const Nullable<T1> &other) const
```

### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع زیرین شیء [Nullable](../) برای مقایسه |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | یک مرجع ثابت به شیء [Nullable](../) برای مقایسه |

### مقدار برگشت

در صورتی که مقدار نمایان‌شده توسط شیء فعلی بزرگ‌تر از مقدار نمایان‌شده توسط شیء [Nullable](../) مشخص‌شده باشد، true؛ در غیر این صورت - false

## مراجع

* کلاس [Nullable](../)
* ساختار [IsNullable](../../isnullable/)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)