---
title: operator+()
second_title: Aspose.Slides برای مرجع API C++
description: یک نمونه ساخته شده به صورت پیش‌فرض از کلاس Nullable<T> را برمی‌گرداند.
type: docs
weight: 209
url: /fa/system/nullable/operator_plus/
---
## Nullable::operator+(std::nullptr_t) const متد

یک نمونه ساخته‌شده به صورت پیش‌فرض از کلاس Nullable<T> را برمی‌گرداند.

```cpp
Nullable<T> System::Nullable<T>::operator+(std::nullptr_t) const
```

## Nullable::operator+(const T1\&) const متد

مقادیر nullable و non-nullable را جمع می‌کند.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator+(const T1 &other) const -> Nullable<decltype(get_Value()+other)>
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع عملوند راست. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| other | const T1\& | مقدار برای افزودن. |

### مقدار بازگشت

نتیجه جمع.

## Nullable::operator+(const Nullable\<T1\>\&) const متد

مقادیر nullable را جمع می‌کند.

```cpp
template<typename T1> auto System::Nullable<T>::operator+(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value()+other.get_Value())>
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع عملوند راست. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | مقدار برای افزودن. |

### مقدار بازگشت

نتیجه جمع.

## مراجع

* کلاس [Nullable](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)