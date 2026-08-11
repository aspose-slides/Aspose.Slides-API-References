---
title: operator<()
second_title: Aspose.Slides برای C++ مرجع API
description: 
type: docs
weight: 2094
url: /fa/system/operator_less/
---
## System::operator<(std::nullptr_t, DateTime) تابع




```cpp
constexpr bool System::operator<(std::nullptr_t, DateTime)
```

## System::operator<(std::nullptr_t, const DateTimeOffset\&) تابع




```cpp
constexpr bool System::operator<(std::nullptr_t, const DateTimeOffset &)
```

## System::operator<(std::nullptr_t, const Nullable\<T\>\&) تابع


همیشه false برمی‌گرداند.

```cpp
template<typename T> bool System::operator<(std::nullptr_t, const Nullable<T> &)
```

## System::operator<(const T1\&, const Nullable\<T2\>\&) تابع


مشخص می‌کند آیا مقدار مشخص شده کمتر از مقداری است که توسط شیء [Nullable](../nullable/) مشخص شده نمایان می‌شود، با اعمال [operator<()](./) بر این مقادیر.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<(const T1 &some, const Nullable<T2> &other)
```


### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T1 | The type of the first comparand value |
| T2 | The underlying type of the [Nullable](../nullable/) object that represents the second comparand value |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| some | const T1\& | A constant reference to the value that is to be used as the first comparand |
| other | const [Nullable](../nullable/)\<T2\>\& | A constant reference to the [Nullable](../nullable/) object the represented value of which is to be used as the second comparand |

### مقدار بازگشت

True اگر مقایسه‌گر اول کمتر از مقایسه‌گر دوم باشد، در غیر این صورت - false

## System::operator<(std::nullptr_t, TimeSpan) تابع




```cpp
constexpr bool System::operator<(std::nullptr_t, TimeSpan)
```

## موارد مرتبط

* کلاس [DateTime](../datetime/)
* کلاس [DateTimeOffset](../datetimeoffset/)
* کلاس [Nullable](../nullable/)
* کلاس [TimeSpan](../timespan/)
* ساختار [IsNullable](../isnullable/)
* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)