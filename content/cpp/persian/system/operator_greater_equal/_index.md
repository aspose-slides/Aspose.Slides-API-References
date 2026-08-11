---
title: operator>=()
second_title: مرجع API Aspose.Slides برای C++
description: 
type: docs
weight: 2133
url: /fa/system/operator_greater_equal/
---
## System::operator>=(std::nullptr_t, DateTime) تابع




```cpp
constexpr bool System::operator>=(std::nullptr_t, DateTime)
```

## System::operator>=(std::nullptr_t, const DateTimeOffset\&) تابع




```cpp
constexpr bool System::operator>=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator>=(std::nullptr_t, const Nullable\<T\>\&) تابع


همیشه false برمی‌گرداند.

```cpp
template<typename T> bool System::operator>=(std::nullptr_t, const Nullable<T> &)
```

## System::operator>=(const T1\&, const Nullable\<T2\>\&) تابع


مشخص می‌کند آیا مقدار مشخص‌شده بزرگ‌تر یا مساوی مقدار نمایان‌شده توسط شیء [Nullable](../nullable/) است با اعمال [operator>=()](./) بر این مقادیر.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator>=(const T1 &some, const Nullable<T2> &other)
```


### Template parameters

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع مقدار مقایسه‌گر اول |
| T2 | نوع پایهٔ شیء [Nullable](../nullable/) که مقدار مقایسه‌گر دوم را نشان می‌دهد |

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| some | const T1\& | یک ارجاع ثابت به مقداری که به عنوان مقایسه‌گر اول استفاده می‌شود |
| other | const [Nullable](../nullable/)\<T2\>\& | یک ارجاع ثابت به شیء [Nullable](../nullable/) که مقدار نمایان‌شده آن به عنوان مقایسه‌گر دوم استفاده می‌شود |

### Return Value

True اگر مقایسه‌گر اول بزرگ‌تر یا مساوی مقایسه‌گر دوم باشد، در غیر این صورت - false

## System::operator>=(std::nullptr_t, TimeSpan) تابع




```cpp
constexpr bool System::operator>=(std::nullptr_t, TimeSpan)
```

## موارد مرتبط

* کلاس [DateTime](../datetime/)
* کلاس [DateTimeOffset](../datetimeoffset/)
* کلاس [Nullable](../nullable/)
* کلاس [TimeSpan](../timespan/)
* ساختار [IsNullable](../isnullable/)
* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)