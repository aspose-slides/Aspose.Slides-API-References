---
title: operator<()
second_title: مرجع API Aspose.Slides برای C++
description: همیشه مقدار false را برمی‌گرداند.
type: docs
weight: 170
url: /fa/system/nullable/operator_less/
---
## Nullable::operator<(std::nullptr_t) const متد

همیشه مقدار false را برمی‌گرداند.

```cpp
bool System::Nullable<T>::operator<(std::nullptr_t) const
```

## Nullable::operator<(const T1\&) const متد

تشخیص می‌دهد که آیا مقدار نمایان‌شده توسط شیء جاری کمتر از مقدار مشخص شده است با اعمال [operator<()](./) بر این مقادیر.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<(const T1 &other) const
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T1 | نوع مقداری که با آن مقایسه می‌شود |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | یک مرجع ثابت به مقداری که با آن مقایسه می‌شود |

### مقدار بازگشت

در صورتی که مقدار نمایان‌شده توسط شیء جاری کمتر از مقدار مشخص شده باشد true برگردانده می‌شود، در غیر این صورت false

## Nullable::operator<(const Nullable\<T1\>\&) const متد

تشخیص می‌دهد که آیا مقدار نمایان‌شده توسط شیء جاری کمتر از مقدار نمایان‌شده توسط شیء [Nullable](../) مشخص شده است با اعمال [operator<()](./) بر این مقادیر.

```cpp
template<typename T1> bool System::Nullable<T>::operator<(const Nullable<T1> &other) const
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T1 | نوع پایهٔ شیء [Nullable](../) که با آن مقایسه می‌شود |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | یک مرجع ثابت به شیء [Nullable](../) که با آن مقایسه می‌شود |

### مقدار بازگشت

در صورتی که مقدار نمایان‌شده توسط شیء جاری کمتر از مقدار نمایان‌شده توسط شیء [Nullable](../) مشخص شده باشد true برگردانده می‌شود، در غیر این صورت false

## موارد مرتبط

* کلاس [Nullable](../)
* ساختار [IsNullable](../../isnullable/)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)