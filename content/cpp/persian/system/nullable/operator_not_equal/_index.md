---
title: operator!=()
second_title: مرجع API Aspose.Slides برای C++
description: تشخیص می‌دهد که آیا مقدار نمایندهٔ شیء فعلی تهی (null) نیست.
type: docs
weight: 144
url: /fa/system/nullable/operator_not_equal/
---
## Nullable::operator!=(std::nullptr_t) const متد

تعیین می‌کند که آیا مقدار نمایندهٔ شیء فعلی تهی (null) نیست.

```cpp
bool System::Nullable<T>::operator!=(std::nullptr_t) const
```

### مقدار بازگشت

در صورتی که مقدار نمایندهٔ شیء فعلی تهی (null) نباشد، true؛ در غیر این صورت false

## Nullable::operator!=(const T1\&) const متد

تعیین می‌کند که آیا مقدار نمایندهٔ شیء فعلی با مقدار مشخص‌شده برابر نیست.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator!=(const T1 &other) const
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع مقداری که باید با آن مقایسه شود |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| other | const T1\& | یک ارجاع ثابت به مقداری که باید با آن مقایسه شود |

### مقدار بازگشت

در صورتی که مقدار نمایندهٔ شیء فعلی با مقدار مشخص‌شده برابر نباشد، true؛ در غیر این صورت false

## Nullable::operator!=(const Nullable\<T1\>\&) const متد

تعیین می‌کند که آیا مقدار نمایندهٔ شیء فعلی با مقدار نمایندهٔ شیء [Nullable](../) مشخص‌شده برابر نیست.

```cpp
template<typename T1> bool System::Nullable<T>::operator!=(const Nullable<T1> &other) const
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع زیرین شیء [Nullable](../) برای مقایسه |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | یک ارجاع ثابت به شیء [Nullable](../) برای مقایسه |

### مقدار بازگشت

در صورتی که مقدار نمایندهٔ شیء فعلی با مقدار نمایندهٔ شیء [Nullable](../) مشخص‌شده برابر نباشد، true؛ در غیر این صورت false

## موارد مرتبط

* کلاس [Nullable](../)
* ساختار [IsNullable](../../isnullable/)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)