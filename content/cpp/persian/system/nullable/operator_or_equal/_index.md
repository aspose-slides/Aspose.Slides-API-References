---
title: operator|=()
second_title: Aspose.Slides برای مرجع API C++
description: عملگر operator|=() را بر روی مقداری که توسط شیء فعلی نمایان‌سازی شده است اعمال می‌کند، به‌طوری که مقدار مشخص‌شده به‌عنوان آرگومان سمت راست استفاده شود.
type: docs
weight: 261
url: /fa/system/nullable/operator_or_equal/
---
## Nullable::operator|=(bool) متد

Applies [operator|=()](./) to the value represented by the current object using the specified value as a right-side argument.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator|=(bool other)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | پارامتر قالب برای فعال‌سازی SFINAE. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| other | **bool** | یک مقدار بولی که به عنوان مقدار سمت راست [operator|=()](./) اعمال شده بر روی مقدار نمایان‌ساز شیء جاری استفاده می‌شود. |

## مقدار بازگشت

یک مرجع به خود.

## موارد مرتبط

* کلاس [Nullable](../)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)