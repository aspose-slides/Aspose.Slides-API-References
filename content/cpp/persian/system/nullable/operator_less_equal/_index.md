---
title: operator<=()
second_title: Aspose.Slides برای C++ مرجع API
description: همیشه false برمی‌گرداند.
type: docs
weight: 196
url: /fa/system/nullable/operator_less_equal/
---
## Nullable::operator<=(std::nullptr_t) const method

همیشه false برمی‌گرداند.

```cpp
bool System::Nullable<T>::operator<=(std::nullptr_t) const
```

## Nullable::operator<=(const T1\&) const method

تعیین می‌کند که آیا مقدار نمایان شده توسط شیء جاری کمتر یا مساوی مقدار مشخص شده است با اعمال [operator<=()](./) به این مقادیر.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<=(const T1 &other) const
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

True اگر مقدار نمایان شده توسط شیء جاری کمتر یا مساوی مقدار مشخص شده باشد، در غیر اینصورت - false

## Nullable::operator<=(const Nullable\<T1\>\&) const method

تعیین می‌کند که آیا مقدار نمایان شده توسط شیء جاری کمتر یا مساوی مقدار نمایان شده توسط شیء [Nullable](../) مشخص شده است با اعمال [operator<=()](./) به این مقادیر.

```cpp
template<typename T1> bool System::Nullable<T>::operator<=(const Nullable<T1> &other) const
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع پایه‌ای شیء [Nullable](../) برای مقایسه |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | یک مرجع ثابت به شیء [Nullable](../) برای مقایسه |

### مقدار بازگشت

True اگر مقدار نمایان شده توسط شیء جاری کمتر یا مساوی مقدار نمایان شده توسط شیء [Nullable](../) باشد، در غیر اینصورت - false

## موارد مرتبط

* کلاس [Nullable](../)
* ساختار [IsNullable](../../isnullable/)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)