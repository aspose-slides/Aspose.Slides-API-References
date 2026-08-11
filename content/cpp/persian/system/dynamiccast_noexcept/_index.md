---
title: DynamicCast_noexcept()
second_title: Aspose.Slides برای C++ مرجع API
description: تبدیل‌های منسوخ قدیمی. در نسخه‌های آینده حذف خواهند شد.
type: docs
weight: 2523
url: /fa/system/dynamiccast_noexcept/
---
## System::DynamicCast_noexcept(const TFrom\&) تابع

قدیم، تبدیل‌های منسوخ. در نسخه‌های آینده حذف خواهند شد.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast_noexcept(const TFrom &obj) noexcept
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TTo | نوع Exception هدف. |
| TFrom | نوع Exception منبع. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const TFrom\& | نشانگر منبع. |

### مقدار بازگشت

نتیجه تبدیل در صورتی که تبدیل مجاز باشد یا nullptr در غیر این صورت.

## توضیحات

تبدیل دینامیک بر روی اشیاء Exception انجام می‌دهد. منسوخ
:   برای سازگاری با نسخه‌های قبلی باقی مانده است. به جای آن از AsCast استفاده کنید.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\> const\&) تابع

تبدیل دینامیک بر روی اشیاء [SmartPtr](../smartptr/) انجام می‌دهد.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast_noexcept(SmartPtr<TFrom> const &obj) noexcept
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TTo | نوع pointee هدف. |
| TFrom | نوع pointee منبع. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | نشانگر منبع. |

### مقدار بازگشت

نتیجه تبدیل در صورتی که تبدیل مجاز باشد یا nullptr در غیر این صورت.

منسوخ
:   برای سازگاری با نسخه‌های قبلی باقی مانده است. به جای آن از AsCast استفاده کنید.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\>) تابع

تبدیل دینامیک بر روی اشیاء به اشیاء Exception انجام می‌دهد.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast_noexcept(SmartPtr<TFrom> obj) noexcept
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TTo | نوع Exception هدف. |
| TFrom | [Object](../object/) نوع. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | نشانگر منبع. |

### مقدار بازگشت

نتیجه تبدیل در صورتی که تبدیل مجاز باشد یا nullptr در غیر این صورت.

منسوخ
:   برای سازگاری با نسخه‌های قبلی باقی مانده است. به جای آن از AsCast استفاده کنید.

## موارد مرتبط

* کلاس [SmartPtr](../smartptr/)
* کلاس [Object](../object/)
* ساختار [IsExceptionWrapper](../isexceptionwrapper/)
* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)