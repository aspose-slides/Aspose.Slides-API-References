---
title: operator-()
second_title: مرجع API Aspose.Slides برای C++
description: مقدارهای nullable و null-pointed را کسر می‌کند.
type: docs
weight: 222
url: /fa/system/nullable/operator_minus/
---
## Nullable::operator-(T1) const متد

مقدارهای nullable و null-pointed را کسر می‌کند.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-(T1) const
```

### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع عملوند سمت راست، باید nullptr_t باشد. |

### مقدار بازگشت

شیء [Nullable](../) خالی.

## Nullable::operator-(const T1&) const متد

مقدارهای nullable و non-nullable را کسر می‌کند.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator-(const T1 &other) const -> Nullable<decltype(get_Value() - other)>
```

### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع عملوند سمت راست. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| other | const T1\& | مقداری که باید از آن کم شود. |

### مقدار بازگشت

نتیجهٔ تفریق.

## Nullable::operator-(const Nullable\<T1\>\&) const متد

مقدارهای nullable را کسر می‌کند.

```cpp
template<typename T1> auto System::Nullable<T>::operator-(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value() - other.get_Value())>
```

### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع عملوند سمت راست. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | مقداری که باید از آن کم شود. |

### مقدار بازگشت

نتیجهٔ تفریق.

## موارد مرتبط

* کلاس [Nullable](../)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)