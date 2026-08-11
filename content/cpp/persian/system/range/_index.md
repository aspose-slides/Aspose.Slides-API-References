---
title: Range
second_title: Aspose.Slides برای C++ مرجع API
description: "یک بازه با ایندکس شروع و پایان را نشان می‌دهد. این نوع باید بر روی پشته اختصاص یابد و به توابع به‌صورت مقدار یا ارجاع پاس شود. هرگز از کلاس System::SmartPtr برای مدیریت اشیاء این نوع استفاده نکنید."
type: docs
weight: 1197
url: /fa/system/range/
---
## کلاس Range

یک بازه را با ایندکس شروع و پایان نشان می‌دهد. این نوع باید روی پشته اختصاص یابد و به صورت مقدار یا ارجاع به توابع پاس شود. هرگز از کلاس [System::SmartPtr](../smartptr/) برای مدیریت اشیاء این نوع استفاده نکنید.

```cpp
class Range : public System::Details::BoxableObjectBase
```

## متدها

| متد | توضیح |
| --- | --- |
| static constexpr [Range](./) [EndAt](./endat/)(const [Index](../index/)\&) | یک بازه ایجاد می‌کند که از ابتدای مجموعه شروع شده و در ایندکس پایان مشخص‌شده خاتمه می‌یابد. |
| **bool** [Equals](./equals/)(const [Range](./)\&) const | تعیین می‌کند که آیا بازه فعلی برابر با بازهٔ مشخص‌شده است یا خیر. |
| static constexpr [Range](./) [get_All](./get_all/)() | یک [Range](./) که کل مجموعه را نماینده می‌کند بازمی‌گرداند. |
| const [Index](../index/)\& [get_End](./get_end/)() const | اندیس End را دریافت می‌کند. |
| const [Index](../index/)\& [get_Start](./get_start/)() const | اندیس Start را دریافت می‌کند. |
| **int32_t** [GetHashCode](./gethashcode/)() const | کد هش برای بازه فعلی را بازمی‌گرداند. |
| [System::ValueTuple](../valuetuple/)\<**int32_t**, **int32_t**\> [GetOffsetAndLength](./getoffsetandlength/)(**int32_t**) const | آفست شروع صفر مبنا و طول را برای طول مجموعهٔ مشخص‌شده محاسبه می‌کند. |
| constexpr [Range](./range/)() | یک بازهٔ خالی ایجاد می‌کند. |
| constexpr [Range](./range/)(const [Index](../index/)\&, const [Index](../index/)\&) | یک [Range](./) را از ایندکس‌های شروع و پایان مشخص‌شده ایجاد می‌کند. |
| static constexpr [Range](./) [StartAt](./startat/)(const [Index](../index/)\&) | یک بازه ایجاد می‌کند که از ایندکس شروع مشخص‌شده آغاز شده و تا انتهای مجموعه ادامه می‌یابد. |

## موارد مرتبط

* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)