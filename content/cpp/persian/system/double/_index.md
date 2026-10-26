---
title: Double
second_title: مرجع API Aspose.Slides برای C++
description: متدهایی را برای کار با عدد شناور دو مرتبه‌دقت فراهم می‌کند.
type: docs
weight: 1574
url: /fa/system/double/
---
## ساختار Double

متدهایی را برای کار با عدد شناور دو مرتبه‌دقت (double-precision) فراهم می‌کند.

```cpp
class Double
```

## متدها

| متد | توضیح |
| --- | --- |
| static **double** [Parse](./parse/)(const [String](../string/)\&) | رشتهٔ مشخص‌شده که نمایش متنی عدد را دارد به مقدار شناور دو مرتبه‌دقت معادل تبدیل می‌کند. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشتهٔ مشخص‌شده که نمایش متنی عدد را دارد به مقدار شناور دو مرتبه‌دقت معادل تبدیل می‌کند با استفاده از اطلاعات قالب‌بندی ارائه‌شده. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشتهٔ مشخص‌شده که نمایش متنی عدد را دارد به مقدار شناور دو مرتبه‌دقت معادل تبدیل می‌کند با استفاده از اطلاعات قالب‌بندی و سبک عدد ارائه‌شده. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **double**\&) | رشتهٔ مشخص‌شده که نمایش متنی عدد را دارد به مقدار شناور دو مرتبه‌دقت معادل تبدیل می‌کند. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **double**\&) | رشتهٔ مشخص‌شده که نمایش متنی عدد را دارد به مقدار شناور دو مرتبه‌دقت معادل تبدیل می‌کند با استفاده از اطلاعات قالب‌بندی و سبک عدد ارائه‌شده. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **double**\&) |  |

## فیلدها

| فیلد | توضیح |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | کوچک‌ترین مقدار مثبت که بزرگتر از صفر است. |
| static constexpr [MaxValue](./maxvalue/) | بزرگ‌ترین مقدار ممکن. |
| static constexpr [MinValue](./minvalue/) | کوچک‌ترین مقدار ممکن. |
| static constexpr [NaN](./nan/) | مقداری که عدد نیست. |
| static constexpr [NegativeInfinity](./negativeinfinity/) | منفی بی‌نهایت. |
| static constexpr [PositiveInfinity](./positiveinfinity/) | مثبت بی‌نهایت. |

## موارد مرتبط

* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)