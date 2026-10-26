---
title: operator-()
second_title: Aspose.Slides برای C++ مرجع API
description: تعداد روزهای بین دو روز از هفته را محاسبه می‌کند.
type: docs
weight: 2172
url: /fa/system/operator_minus/
---
## System::operator-(DayOfWeek, DayOfWeek) تابع

تعداد روزهای بین دو روز از هفته را محاسبه می‌کند.

```cpp
auto System::operator-(DayOfWeek a, DayOfWeek b)
```

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| a | [DayOfWeek](../dayofweek/) | عملیات‌گر minuend |
| b | [DayOfWeek](../dayofweek/) | عملیات‌گر subtrahend |

### مقدار بازگشت

تعداد روزهای بین روزهای کاری **a** و **b**؛ مقدار بازگشت عددی منفی است اگر **اگر** *goes* پس از ****

## System::operator-(const T\&, const Decimal\&) تابع

یک نمونه جدید از کلاس [Decimal](../decimal/) را برمی‌گرداند که مقداری را نشان می‌دهد که نتیجهٔ تفریق مقدار نمایندهٔ شیء [Decimal](../decimal/) مشخص شده از مقدار مشخص شده است.

```cpp
template<typename T,typename _> Decimal System::operator-(const T &x, const Decimal &d)
```

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| x | const T\& | مقداری که از آن کم می‌شود |
| d | const [Decimal](../decimal/)\& | شیء [Decimal](../decimal/) نمایانگر مقدار کسر شده |

### مقدار بازگشت

یک نمونه جدید از کلاس [Decimal](../decimal/) که مقدار نتیجهٔ تفریق **d** از **x** را نشان می‌دهد.

## System::operator-(MulticastDelegate\<T\>, MulticastDelegate\<T\>) تابع

تمام فراخوانی‌های بازگشتی در نمایندهٔ دست راست را از انتهای فهرست فراخوانی‌های نمایندهٔ دست چپ جدا می‌کند.

```cpp
template<typename T> MulticastDelegate<T> System::operator-(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | نماینده‌ای که فراخوانی‌ها از آن حذف می‌شوند. |
| rhv | MulticastDelegate\<T\> | نماینده‌ای که فراخوانی‌های آن حذف می‌شوند. |

### مقدار بازگشت

نماینده‌ای را برمی‌گرداند که شامل فراخوانی‌های مقدار دست چپ است، اما بدون فراخوانی‌های مقدار دست راست.

## System::operator-(const T1\&, const Nullable\<T2\>\&) تابع

مقادیر غیرقابل‌null و nullable را کم می‌کند.

```cpp
template<typename T1,typename T2,typename> auto System::operator-(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some - other.get_Value())>
```

### پارامترهای قالب

| پارامتر | توضیحات |
| --- | --- |
| T1 | نوع عملوند چپ. |
| T2 | نوع عملوند راست. |

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| some | const T1\& | عملوند چپ. |
| other | const [Nullable](../nullable/)\<T2\>\& | عملوند راست. |

### مقدار بازگشت

نتیجهٔ تفریق.

## موارد مرتبط

* Enum [DayOfWeek](../dayofweek/)
* کلاس [Decimal](../decimal/)
* کلاس [Nullable](../nullable/)
* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)