---
title: operator-=()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمونه از کلاس Nullable که نمایانگر مقدار null است را بر می‌گرداند.
type: docs
weight: 248
url: /fa/system/nullable/operator_minus_equal/
---
## Nullable::operator-=(T1) متد

یک نمونه از کلاس [Nullable](../) که نمایانگر مقدار null است را برمی‌گرداند.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-=(T1)
```

## Nullable::operator-=(const T1\&) متد

عملیات [operator-=()](./) را بر روی مقدار نمایانده توسط شیء جاری اعمال می‌کند، به‌طوری که مقدار مشخص‌شده به‌عنوان آرگومان سمت راست استفاده می‌شود.

```cpp
template<typename T1,typename> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator-=(const T1 &other)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع مقداری که به‌عنوان مقدار سمت راست [operator-=()](./) استفاده می‌شود |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| other | const T1\& | یک مرجع ثابت به مقداری که به‌عنوان مقدار سمت راست [operator-=()](./) اعمال‌شده بر مقدار نمایانده توسط شیء جاری استفاده می‌شود. |

### مقدار بازگشتی

یک ارجاع به خود

## Nullable::operator-=(const Nullable\<T1\>\&) متد

عملیات [operator-=()](./) را بر روی مقدار نمایانده توسط شیء جاری اعمال می‌کند، به‌طوری که مقدار نمایانده توسط شیء [Nullable](../) مشخص‌شده به‌عنوان آرگومان سمت راست استفاده می‌شود.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator-=(const Nullable<T1> &other)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع زیرین یک شیء [Nullable](../) که مقدار نمایانده توسط آن به‌عنوان آرگومان سمت راست [operator-=()](./) استفاده می‌شود |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | یک مرجع ثابت به شیء [Nullable](../) که مقدار نمایانده توسط آن به‌عنوان آرگومان سمت راست [operator-=()](./) اعمال‌شده بر مقدار نمایانده توسط شیء جاری استفاده می‌شود. |

### مقدار بازگشتی

یک ارجاع به خود

## موارد مرتبط

* کلاس [Nullable](../)
* ساختار [IsNullable](../../isnullable/)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)