---
title: Single
second_title: مرجع API Aspose.Slides برای C++
description: متدهایی برای کار با عدد شناور تک‌دقت شامل می‌شود.
type: docs
weight: 1899
url: /fa/system/single/
---
## ساختار تک

شامل متدهایی برای کار با عدد شناور تک‌دقت است.

```cpp
class Single
```

## متدها

| Method | Description |
| --- | --- |
| static **float** [Parse](./parse/)(const [String](../string/)\&) | رشتهٔ مشخص‌شده که حاوی نمایش عدد است را به مقدار عدد شناور تک‌دقت معادل تبدیل می‌کند. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشتهٔ مشخص‌شده که حاوی نمایش عدد است را با استفاده از اطلاعات قالب‌بندی ارائه‌شده به مقدار عدد شناور تک‌دقت معادل تبدیل می‌کند. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشتهٔ مشخص‌شده که حاوی نمایش عدد است را با استفاده از اطلاعات قالب‌بندی ارائه‌شده و سبک عدد به مقدار عدد شناور تک‌دقت معادل تبدیل می‌کند. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **float**\&) | رشتهٔ مشخص‌شده که حاوی نمایش عدد است را به مقدار عدد شناور تک‌دقت معادل تبدیل می‌کند. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **float**\&) | رشتهٔ مشخص‌شده که حاوی نمایش عدد است را با استفاده از اطلاعات قالب‌بندی ارائه‌شده و سبک عدد به مقدار عدد شناور تک‌دقت معادل تبدیل می‌کند. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **float**\&) |  |

## فیلدها

| Field | Description |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | کوچک‌ترین مقدار مثبت که بزرگ‌تر از صفر است. |
| static constexpr [MaxValue](./maxvalue/) | بزرگ‌ترین مقدار ممکن. |
| static constexpr [MinValue](./minvalue/) | کوچک‌ترین مقدار ممکن. |
| static constexpr [NaN](./nan/) | مقداری که عدد نیست. |
| static constexpr [NegativeInfinity](./negativeinfinity/) | بی‌نهایت منفی. |
| static constexpr [PositiveInfinity](./positiveinfinity/) | بی‌نهایت مثبت. |

## موارد مرتبط

* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)