---
title: SByte
second_title: مرجع API Aspose.Slides برای C++
description: متدهایی برای کار با عدد صحیح ۸ بیتی را شامل می‌شود.
type: docs
weight: 1873
url: /fa/system/sbyte/
---
## SByte struct

متدهایی برای کار با عدد صحیح ۸ بیتی را شامل می‌شود.

```cpp
class SByte
```

## متدها

| متد | توضیح |
| --- | --- |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&) | رشتهٔ مشخص‌شده که شامل نمایش متنی عددی است را به عدد صحیح ۸ بیتی معادل تبدیل می‌کند. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشتهٔ مشخص‌شده که شامل نمایش متنی عددی است را با استفاده از اطلاعات قالب‌بندی ارائه‌شده به عدد صحیح ۸ بیتی معادل تبدیل می‌کند. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشتهٔ مشخص‌شده که شامل نمایش متنی عددی است را با استفاده از اطلاعات قالب‌بندی و سبک عددی ارائه‌شده به عدد صحیح ۸ بیتی معادل تبدیل می‌کند. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int8_t**\&) | رشتهٔ مشخص‌شده که شامل نمایش متنی عددی است را به عدد صحیح ۸ بیتی معادل تبدیل می‌کند. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int8_t**\&) | رشتهٔ مشخص‌شده که شامل نمایش متنی عددی است را با استفاده از اطلاعات قالب‌بندی و سبک عددی ارائه‌شده به عدد صحیح ۸ بیتی معادل تبدیل می‌کند. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int8_t**\&) |  |

## فیلدها

| فیلد | توضیح |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | بزرگ‌ترین مقدار ممکن. |
| static constexpr [MinValue](./minvalue/) | کوچک‌ترین مقدار ممکن. |

## مراجع

* Namespace [System](../)
* Library [Aspose.Slides](../../)