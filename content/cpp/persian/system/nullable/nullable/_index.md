---
title: Nullable()
second_title: مرجع API Aspose.Slides برای C++
description: نمونه‌ای را می‌سازد که مقدار null را نشان می‌دهد.
type: docs
weight: 1
url: /fa/system/nullable/nullable/
---
## Nullable::Nullable() سازنده

یک نمونه را می‌سازد که مقدار null را نشان می‌دهد.

```cpp
System::Nullable<T>::Nullable()
```

## Nullable::Nullable(std::nullptr_t) سازنده

یک نمونه را می‌سازد که null را نشان می‌دهد.

```cpp
System::Nullable<T>::Nullable(std::nullptr_t)
```

## Nullable::Nullable(const T1\&) سازنده

یک نمونه از کلاس [Nullable](../) می‌سازد که مقدار مشخص‌شده را (در صورت لزوم) به مقدار نوع پایه T تبدیل می‌کند.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const T1 &value)
```

### پارامترهای قالب

| پارامتر | شرح |
| --- | --- |
| T1 | نوع مقدار مشخص‌شده |

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | const T1\& | یک مرجع ثابت به مقداری که توسط شیء تازه ساخته‌شده [Nullable](../) نشان داده می‌شود |

## Nullable::Nullable(const Nullable\<T1\>\&) سازنده

یک نمونه را می‌سازد که مقداری را نشان می‌دهد که توسط شیء [Nullable](../) مشخص‌شده نمایان شده است. شیء nullable مشخص‌شده ممکن است مقداری از نوع متفاوتی نسبت به نوع پایه نمونه ساخته‌شده داشته باشد؛ در این حالت مقدار نمایان‌شده به نوع T تبدیل می‌شود.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const Nullable<T1> &value)
```

### پارامترهای قالب

| پارامتر | شرح |
| --- | --- |
| T1 | نوع مقداری که توسط شیء [Nullable](../) مشخص‌شده نمایان می‌شود |

## موارد مرتبط

* کلاس [Nullable](../)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)