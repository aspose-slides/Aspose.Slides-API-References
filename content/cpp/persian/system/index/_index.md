---
title: Index
second_title: مرجع API Aspose.Slides برای C++
description: "نمایانگر یک اندیس در یک مجموعه است. اندیس می‌تواند از ابتدا یا از انتها باشد. این نوع باید در پشته تخصیص یابد و به توابع به صورت مقدار یا ارجاع پاس داده شود. هرگز از کلاس System::SmartPtr برای مدیریت اشیاء این نوع استفاده نکنید."
type: docs
weight: 1015
url: /fa/system/index/
---
## کلاس Index

نمایانگر یک اندیس در یک مجموعه است. اندیس می‌تواند از ابتدا یا از انتها باشد. این نوع باید در پشته تخصیص یابد و به توابع به صورت مقدار یا ارجاع پاس داده شود. هرگز از کلاس [System::SmartPtr](../smartptr/) برای مدیریت اشیاء این نوع استفاده نکنید.

```cpp
class Index : public System::Details::BoxableObjectBase
```

## متدها

| متد | توضیح |
| --- | --- |
| **bool** [Equals](./equals/)(const [Index](./)\&) const | مشخص می‌کند که آیا نمونهٔ جاری و [Index](./) مشخص‌شده موقعیت یکسانی دارند. |
| static constexpr [Index](./) [FromEnd](./fromend/)(**int32_t**) | یک [Index](./) ایجاد می‌کند که نسبت به انتهای مجموعه است. |
| static constexpr [Index](./) [get_End](./get_end/)() | یک شیء [Index](./) دریافت می‌کند که انتهای یک مجموعه را نشان می‌دهد. |
| constexpr **bool** [get_IsFromEnd](./get_isfromend/)() const | یک مقدار دریافت می‌کند که نشان می‌دهد آیا اندیس از انتها است. |
| static constexpr [Index](./) [get_Start](./get_start/)() | یک شیء [Index](./) دریافت می‌کند که شروع یک مجموعه را نشان می‌دهد. |
| constexpr **int32_t** [get_Value](./get_value/)() const | مقدار اندیس را دریافت می‌کند. |
| **int32_t** [GetHashCode](./gethashcode/)() const | کد هش برای اندیس جاری را برمی‌گرداند. |
| **int32_t** [GetOffset](./getoffset/)(**int32_t**) const | [Index](./) فعلی را به یک افست از ابتدای مجموعه با طول مشخص تبدیل می‌کند. |
| constexpr [Index](./index/)() | یک نمونه می‌سازد که شروع یک مجموعه را نشان می‌دهد. |
| constexpr [Index](./index/)(**int32_t**) | یک نمونه می‌سازد که موقعیت مشخص از ابتدای مجموعه را نشان می‌دهد. |
| constexpr [Index](./index/)(**int32_t**, **bool**) | یک نمونه می‌سازد که اندیس مشخص‌شده را نشان می‌دهد. |

## مراجع

* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)