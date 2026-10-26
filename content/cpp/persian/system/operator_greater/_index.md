---
title: operator>()
second_title: مرجع API Aspose.Slides برای C++
description: 
type: docs
weight: 2120
url: /fa/system/operator_greater/
---
## System::operator>(std::nullptr_t, DateTime) تابع




```cpp
constexpr bool System::operator>(std::nullptr_t, DateTime)
```

## System::operator>(std::nullptr_t, const DateTimeOffset\&) تابع




```cpp
constexpr bool System::operator>(std::nullptr_t, const DateTimeOffset &)
```

## System::operator>(std::nullptr_t, const Nullable\<T\>\&) تابع


همیشه مقدار false را برمی‌گرداند.

```cpp
template<typename T> bool System::operator>(std::nullptr_t, const Nullable<T> &)
```

## System::operator>(const T1\&, const Nullable\<T2\>\&) تابع


تعیین می‌کند که آیا مقدار مشخص‌شده بزرگتر از مقدار نمایان‌شده توسط شیء [Nullable](../nullable/) مشخص شده است، با اعمال [operator>()](./) بر روی این مقادیر.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator>(const T1 &some, const Nullable<T2> &other)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع اولین مقدار مقایسه‌کننده |
| T2 | نوع پایه شیء [Nullable](../nullable/) که مقدار مقایسه‌کننده دوم را نمایان می‌کند |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| some | const T1\& | یک ارجاع ثابت به مقداری که به عنوان اولین مقایسه‌کننده استفاده می‌شود |
| other | const [Nullable](../nullable/)\<T2\>\& | یک ارجاع ثابت به شیء [Nullable](../nullable/) که مقدار نمایان‌شدهٔ آن به عنوان دومین مقایسه‌کننده استفاده می‌شود |

### مقدار بازگشت

در صورتی که اولین مقایسه‌کننده بزرگتر از دومین مقایسه‌کننده باشد، True؛ در غیر این صورت - false

## System::operator>(std::nullptr_t, TimeSpan) تابع




```cpp
constexpr bool System::operator>(std::nullptr_t, TimeSpan)
```

## نگاه کنید به

* کلاس [DateTime](../datetime/)
* کلاس [DateTimeOffset](../datetimeoffset/)
* کلاس [Nullable](../nullable/)
* کلاس [TimeSpan](../timespan/)
* ساختار [IsNullable](../isnullable/)
* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)