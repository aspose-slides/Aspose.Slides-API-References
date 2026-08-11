---
title: BitVector32
second_title: مرجع API Aspose.Slides برای C++
description: یک بردار بیت ساده و سبک فراهم می‌کند که دسترسی آسان به عدد صحیح یا Boolean به ذخیره‌سازی 32 بیتی را ارائه می‌دهد.
type: docs
weight: 1
url: /fa/system.collections.specialized/bitvector32/
---
## BitVector32 کلاس

یک بردار بیت ساده و سبک را با دسترسی آسان به عدد صحیح یا [Boolean](../../system/boolean/) برای ذخیره‌سازی 32 bit فراهم می‌کند.

```cpp
class BitVector32
```

## متدها

| متد | توضیح |
| --- | --- |
|  [BitVector32](./bitvector32/)() | یک نمونه خالی جدید از [BitVector32](./) را مقداردهی اولیه می‌کند. |
|  [BitVector32](./bitvector32/)(**int32_t**) | یک نمونه جدید از ساختار [BitVector32](./) را با داده داخلی مشخص مقداردهی اولیه می‌کند. |
|  [BitVector32](./bitvector32/)(const [BitVector32](./)\&) | یک نمونه جدید از ساختار [BitVector32](./) را با اطلاعات موجود در مقدار مشخص شده مقداردهی اولیه می‌کند. |
| static **int32_t** [CreateMask](./createmask/)() | اولین ماسک در یک سری را ایجاد می‌کند. |
| static **int32_t** [CreateMask](./createmask/)(**int32_t**) | ماسک بعدی در یک سری را ایجاد می‌کند. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**) | اولین بخش در یک سری را با مقدار حداکثری مشخص شده ایجاد می‌کند. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**, **BitVector32::Section**) | بخش بعدی در یک سری را با مقدار حداکثری مشخص شده ایجاد می‌کند. |
| **bool** [Equals](./equals/)(const [BitVector32](./)\&) | تعیین می‌کند آیا شیء مشخص شده همان شیء فعلی است. |
| **int32_t** [get_Data](./get_data/)() | داده خام ذخیره شده در این بردار بیت را برمی‌گرداند... |
| **int32_t** [GetHashCode](./gethashcode/)() const | کد هش برای شیء فعلی را برمی‌گرداند. |
| **bool** [idx_get](./idx_get/)(**int32_t**) | مقداری را برمی‌گرداند که نشان می‌دهد آیا تمام بیت‌های مشخص شده تنظیم شده‌اند. |
| **int32_t** [idx_get](./idx_get/)(**BitVector32::Section**) | مقدار بخش مشخص شده را برمی‌گرداند. |
| void [idx_set](./idx_set/)(**int32_t**, **bool**) | مقداری را تنظیم می‌کند که نشان می‌دهد آیا تمام بیت‌های مشخص شده تنظیم شده‌اند. |
| void [idx_set](./idx_set/)(**BitVector32::Section**, **int32_t**) | مقدار برای بخش مشخص شده را تنظیم می‌کند. |
| static [String](../../system/string/) [ToString](./tostring/)(const [BitVector32](./)\&) | مقدار نمایان‌شده توسط پارامتر value را به رشته تبدیل می‌کند. |
| [String](../../system/string/) [ToString](./tostring/)() const | مقدار نمایان‌شده توسط شیء فعلی را به رشته تبدیل می‌کند. |

## موارد مرتبط

* فضای‌نام [System::Collections::Specialized](../)
* کتابخانه [Aspose.Slides](../../)