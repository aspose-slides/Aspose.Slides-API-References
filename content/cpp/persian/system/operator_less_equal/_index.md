---
title: operator<=()
second_title: Aspose.Slides برای C++ مرجع API
description: 
type: docs
weight: 2107
url: /fa/system/operator_less_equal/
---
## System::operator<=(std::nullptr_t, DateTime) تابع




```cpp
constexpr bool System::operator<=(std::nullptr_t, DateTime)
```

## System::operator<=(std::nullptr_t, const DateTimeOffset\&) تابع




```cpp
constexpr bool System::operator<=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator<=(std::nullptr_t, const Nullable\<T\>\&) تابع


همیشه مقدار نادرست را برمی‌گرداند.

```cpp
template<typename T> bool System::operator<=(std::nullptr_t, const Nullable<T> &)
```

## System::operator<=(const T1\&, const Nullable\<T2\>\&) تابع


مشخص می‌کند که آیا مقدار مشخص‌شده کمتر یا برابر مقدار نمایان‌شده توسط شیء [Nullable](../nullable/) موردنظر است با اعمال [operator<=()](./) روی این مقادیر.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<=(const T1 &some, const Nullable<T2> &other)
```


### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T1 | نوع مقدار مقایسه‌گر اول |
| T2 | نوع زیربنایی شیء [Nullable](../nullable/) که مقدار مقایسه‌گر دوم را نشان می‌دهد |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| some | const T1\& | یک ارجاع ثابت به مقداری که به عنوان مقایسه‌گر اول استفاده می‌شود |
| other | const [Nullable](../nullable/)\<T2\>\& | یک ارجاع ثابت به شیء [Nullable](../nullable/) که مقدار نمایان‌شده آن به عنوان مقایسه‌گر دوم استفاده می‌شود |

### مقدار بازگشتی

True اگر مقایسه‌گر اول کمتر یا برابر مقایسه‌گر دوم باشد، در غیر این صورت false

```cpp
constexpr bool System::operator<=(std::nullptr_t, TimeSpan)
```

## موارد مرتبط

* کلاس [DateTime](../datetime/)
* کلاس [DateTimeOffset](../datetimeoffset/)
* کلاس [Nullable](../nullable/)
* کلاس [TimeSpan](../timespan/)
* ساختار [IsNullable](../isnullable/)
* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)