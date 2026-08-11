---
title: StaticCast()
second_title: Aspose.Slides برای C++ مرجع API
description: تبدیل استاتیک را بر روی اشیاء SmartPtr انجام می‌دهد.
type: docs
weight: 2562
url: /fa/system/staticcast/
---
## System::StaticCast(SmartPtr\<TFrom\> const\&) تابع


تبدیل استاتیک را بر روی اشیاء [SmartPtr](../smartptr/) انجام می‌دهد.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast(SmartPtr<TFrom> const &obj)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TTo | نوع هدف. |
| TFrom | نوع منبع. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | اشاره‌گر منبع. |

### مقدار بازگشت

نتیجه تبدیل در صورتی که تبدیل مجاز باشد.

منسوخ شده
:   برای سازگاری با نسخه‌های قبلی باقی مانده است. به‌جای آن از ExplicitCast استفاده کنید.

## System::StaticCast(WeakPtr\<TFrom\> const\&) تابع


تبدیل استاتیک را بر روی اشیاء [WeakPtr](../weakptr/) انجام می‌دهد.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast(WeakPtr<TFrom> const &obj)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TTo | نوع هدف. |
| TFrom | نوع منبع. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | اشاره‌گر منبع. |

### مقدار بازگشت

نتیجه تبدیل در صورتی که تبدیل مجاز باشد.

منسوخ شده
:   برای سازگاری با نسخه‌های قبلی باقی مانده است. به‌جای آن از ExplicitCast استفاده کنید.

## System::StaticCast(std::nullptr_t) تابع


تبدیل استاتیک اشیاء تهی را انجام می‌دهد.

```cpp
template<typename TTo> CastResult<TTo>::type System::StaticCast(std::nullptr_t)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TTo | نوع هدف. |

### مقدار بازگشت

nullptr.

منسوخ شده
:   برای سازگاری با نسخه‌های قبلی باقی مانده است. به‌جای آن از ExplicitCast استفاده کنید.

## System::StaticCast(TFrom) تابع


تخصیص ویژه برای انواع عددی.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(TFrom value)
```

## System::StaticCast(TTo) تابع


تبدیل از [String](../string/) به [String](../string/) را پردازش می‌کند.

```cpp
template<typename TTo> std::enable_if<std::is_same<TTo, System::String>::value, TTo>::type System::StaticCast(TTo value)
```

## System::StaticCast(const TFrom *) تابع


تخصیص ویژه برای انواع عددی.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom *value)
```

## System::StaticCast(const TFrom\&) تابع


تبدیل استاتیک را بر روی اشیاء غیر اشاره‌گر انجام می‌دهد.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_same<TFrom, System::String>::value &&!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&!std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom &obj)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TTo | نوع هدف. |
| TFrom | نوع منبع. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const TFrom\& | شی منبع. |

### مقدار بازگشت

نتیجه تبدیل در صورتی که تبدیل مجاز باشد.

منسوخ شده
:   برای سازگاری با نسخه‌های قبلی باقی مانده است. به‌جای آن از ExplicitCast استفاده کنید.

## System::StaticCast(const TFrom\&) تابع


تبدیل استاتیک را بر روی اشیاء Exception انجام می‌دهد.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast(const TFrom &obj)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TTo | نوع Exception هدف. |
| TFrom | نوع Exception منبع. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const TFrom\& | اشاره‌گر منبع. |

### مقدار بازگشت

نتیجه تبدیل در صورتی که تبدیل مجاز باشد.

منسوخ شده
:   برای سازگاری با نسخه‌های قبلی باقی مانده است. به‌جای آن از ExplicitCast استفاده کنید.

## System::StaticCast(SmartPtr\<TFrom\>) تابع


تبدیل استاتیک را بر روی Objects به اشیاء Exception انجام می‌دهد.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast(SmartPtr<TFrom> obj) noexcept
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TTo | نوع Exception هدف. |
| TFrom | نوع [Object](../object/). |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | اشاره‌گر منبع. |

### مقدار بازگشت

نتیجه تبدیل در صورتی که تبدیل مجاز باشد.

منسوخ شده
:   برای سازگاری با نسخه‌های قبلی باقی مانده است. به‌جای آن از ExplicitCast استفاده کنید.

## مراجع

* کلاس [SmartPtr](../smartptr/)
* کلاس [WeakPtr](../weakptr/)
* کلاس [String](../string/)
* کلاس [Object](../object/)
* ساختار [IsExceptionWrapper](../isexceptionwrapper/)
* ساختار [CastResult](../castresult/)
* ساختار [IsSmartPtr](../issmartptr/)
* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)