---
title: operator=()
second_title: مرجع API Aspose.Slides برای C++
description: یک مقدار null به شیء جاری اختصاص می‌دهد.
type: docs
weight: 14
url: /fa/system/nullable/operator_equal/
---
## Nullable::operator=(std::nullptr_t) متد

یک مقدار null به شیء جاری اختصاص می‌دهد.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator=(std::nullptr_t)
```

### مقدار بازگشت

[Nullable](../) شیئی که مقدار null-مانند را نشان می‌دهد.

## Nullable::operator=(const T1\&) متد

مقدار فعلی نمایان‌ شده در شیء را با مقدار مشخص شده جایگزین می‌کند.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value &&!std::is_null_pointer<T1>::value, Nullable<T> &>::type System::Nullable<T>::operator=(const T1 &x)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| The | نوع مقدار جدیدی که توسط شیء جاری نمایان می‌شود |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | const T1\& | مقدار جدیدی که توسط شیء جاری نمایان می‌شود |

### مقدار بازگشت

یک ارجاع به خود

## Nullable::operator=(const Nullable\<T1\>\&) متد

مقدار فعلی نمایان‌ شده در شیء را با مقدار مشخص شده جایگزین می‌کند.

```cpp
template<typename T1> Nullable<T> & System::Nullable<T>::operator=(const Nullable<T1> &x)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| The | نوع مقدار جدیدی که توسط شیء جاری نمایان می‌شود |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | const [Nullable](../)\<T1\>\& | مقدار جدیدی که توسط شیء جاری نمایان می‌شود |

### مقدار بازگشت

یک ارجاع به خود

## موارد مرتبط

* Class [Nullable](../)
* Struct [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)