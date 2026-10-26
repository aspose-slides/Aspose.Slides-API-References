---
title: StaticCast_noexcept()
second_title: Aspose.Slides برای مرجع API C++
description: تبدیل ایستا را بر روی اشیاء SmartPtr انجام می‌دهد.
type: docs
weight: 2549
url: /fa/system/staticcast_noexcept/
---
## System::StaticCast_noexcept(SmartPtr\<TFrom\> const\&) تابع

این تابع تبدیل ایستا را بر روی اشیاء [SmartPtr](../smartptr/) انجام می‌دهد.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast_noexcept(SmartPtr<TFrom> const &obj)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TTo | نوع pointee هدف. |
| TFrom | نوع pointee منبع. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | اشاره‌گر منبع. |

### مقدار بازگشتی

نتیجه تبدیل اگر تبدیل مجاز باشد یا در غیر این صورت nullptr.

منسوخ‌شده
:   برای سازگاری با نسخه‌های قبلی باقی مانده است. به جای آن از AsCast استفاده کنید.

## System::StaticCast_noexcept(WeakPtr\<TFrom\> const\&) تابع


این تابع تبدیل ایستا را بر روی اشیاء [WeakPtr](../weakptr/) انجام می‌دهد.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast_noexcept(WeakPtr<TFrom> const &obj)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TTo | نوع pointee هدف. |
| TFrom | نوع pointee منبع. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | اشاره‌گر منبع. |

### مقدار بازگشتی

نتیجه تبدیل اگر تبدیل مجاز باشد یا در غیر این صورت nullptr.

منسوخ‌شده
:   برای سازگاری با نسخه‌های قبلی باقی مانده است. به جای آن از AsCast استفاده کنید.

## System::StaticCast_noexcept(const TFrom\&) تابع


این تابع تبدیل ایستا را بر روی اشیاء Exception انجام می‌دهد.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast_noexcept(const TFrom &obj)
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

### مقدار بازگشتی

نتیجه تبدیل اگر تبدیل مجاز باشد یا در غیر این صورت nullptr.

منسوخ‌شده
:   برای سازگاری با نسخه‌های قبلی باقی مانده است. به جای آن از AsCast استفاده کنید.

## System::StaticCast_noexcept(SmartPtr\<TFrom\>) تابع


این تابع تبدیل ایستا را بر روی اشیاء به اشیاء Exception انجام می‌دهد.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast_noexcept(SmartPtr<TFrom> obj) noexcept
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TTo | نوع Exception هدف. |
| TFrom | [Object](../object/) type. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | اشاره‌گر منبع. |

### مقدار بازگشتی

نتیجه تبدیل اگر تبدیل مجاز باشد یا در غیر این صورت nullptr.

منسوخ‌شده
:   برای سازگاری با نسخه‌های قبلی باقی مانده است. به جای آن از AsCast استفاده کنید.

## موارد مرتبط

* کلاس [SmartPtr](../smartptr/)
* کلاس [WeakPtr](../weakptr/)
* کلاس [Object](../object/)
* ساختار [IsExceptionWrapper](../isexceptionwrapper/)
* ساختار [CastResult](../castresult/)
* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)