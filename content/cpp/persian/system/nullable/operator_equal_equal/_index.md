---
title: operator==()
second_title: مرجع API Aspose.Slides برای C++
description: تعیین می‌کند که آیا مقدار نمایان‌شده توسط شیء جاری تهی است.
type: docs
weight: 118
url: /fa/system/nullable/operator_equal_equal/
---
## Nullable::operator==(std::nullptr_t) const متد


تعیین می‌کند که آیا مقدار نمایان‌شده توسط شیٔ فعلی تهی (null) است یا خیر.

```cpp
bool System::Nullable<T>::operator==(std::nullptr_t) const
```


### مقدار بازگشت

درست اگر مقدار نمایان‌شده توسط شیٔ فعلی تهی باشد، در غیر این صورت - نادرست

## Nullable::operator==(const T1\&) const متد


تعیین می‌کند که آیا مقدار نمایان‌شده توسط شیٔ فعلی برابر با مقدار مشخص‌شده است یا خیر.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator==(const T1 &other) const
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع مقدار برای مقایسه |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| other | const T1\& | یک مرجع ثابت به مقدار برای مقایسه |

### مقدار بازگشت

درست اگر مقدار نمایان‌شده توسط شیٔ فعلی برابر با مقدار مشخص‌شده باشد، در غیر این صورت - نادرست

## Nullable::operator==(const Nullable\<T1\>\&) const متد


تعیین می‌کند که آیا مقدار نمایان‌شده توسط شیٔ فعلی برابر با مقدار نمایان‌شده توسط شیٔ [Nullable](../) مشخص‌شده است یا خیر.

```cpp
template<typename T1> bool System::Nullable<T>::operator==(const Nullable<T1> &other) const
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع پایهٔ شیٔ [Nullable](../) برای مقایسه |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | یک مرجع ثابت به شیٔ [Nullable](../) برای مقایسه |

### مقدار بازگشت

درست اگر مقدار نمایان‌شده توسط شیٔ فعلی برابر با مقدار نمایان‌شده توسط شیٔ [Nullable](../) مشخص‌شده باشد، در غیر این صورت - نادرست

## مشاهده نیز

* کلاس [Nullable](../)
* ساختار [IsNullable](../../isnullable/)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)