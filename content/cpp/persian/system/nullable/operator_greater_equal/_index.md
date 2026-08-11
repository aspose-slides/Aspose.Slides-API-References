---
title: operator>=()
second_title: مرجع API Aspose.Slides برای C++
description: همیشه false را برمی‌گرداند.
type: docs
weight: 183
url: /fa/system/nullable/operator_greater_equal/
---
## Nullable::operator>=(std::nullptr_t) const متد

همیشه false را برمی‌گرداند.

```cpp
bool System::Nullable<T>::operator>=(std::nullptr_t) const
```

### مقدار بازگشت

همیشه - false

## Nullable::operator>=(const T1\&) const متد

مشخص می‌کند آیا مقدار نمایان‌شده توسط شیء جاری بزرگ‌تر یا مساوی مقدار نمایان‌شده توسط شیء مشخص شده است، با اعمال [operator>=()](./) بر این مقادیر.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>=(const T1 &other) const
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع زیرین مقدار برای مقایسه مقدار نمایان‌شده توسط شیء جاری با |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| other | const T1\& | یک مرجع ثابت به شیئی برای مقایسه با شیء جاری |

### مقدار بازگشت

در صورتی که مقدار نمایان‌شده توسط شیء جاری بزرگ‌تر یا مساوی مقدار نمایان‌شده توسط شیء مشخص شده باشد، true؛ در غیر این صورت - false

## Nullable::operator>=(const Nullable\<T1\>\&) const متد

مشخص می‌کند آیا مقدار نمایان‌شده توسط شیء جاری بزرگ‌تر یا مساوی مقدار نمایان‌شده توسط شیء [Nullable](../) مشخص شده است، با اعمال [operator>=()](./) بر این مقادیر.

```cpp
template<typename T1> bool System::Nullable<T>::operator>=(const Nullable<T1> &other) const
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع زیرین شیء [Nullable](../) برای مقایسه با |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | یک مرجع ثابت به شیء [Nullable](../) برای مقایسه با |

### مقدار بازگشت

در صورتی که مقدار نمایان‌شده توسط شیء جاری بزرگ‌تر یا مساوی مقدار نمایان‌شده توسط شیء [Nullable](../) باشد، true؛ در غیر این صورت - false

## موارد مرتبط

* Class [Nullable](../)
* Struct [IsNullable](../../isnullable/)
* فضای نام [System](../../)
* Library [Aspose.Slides](../../../)