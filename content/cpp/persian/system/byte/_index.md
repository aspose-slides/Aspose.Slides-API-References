---
title: Byte
second_title: مرجع API Aspose.Slides برای C++
description: متدهایی را برای کار با عدد صحیح بدون علامت 8 بیتی فراهم می‌کند.
type: docs
weight: 157
url: /fa/system/byte/
---
## کلاس Byte

Contains methods to work with the unsigned 8-bit integer.

```cpp
class Byte
```

## متدها

| متد | توضیح |
| --- | --- |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&) | رشتهٔ مشخص‌شده که حاوی نمایش عددی به صورت رشته‌ای است را به عدد صحیح بدون علامت 8 بیتی معادل تبدیل می‌کند. |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشتهٔ مشخص‌شده که حاوی نمایش عددی به صورت رشته‌ای است را با استفاده از اطلاعات قالب‌بندی ارائه‌شده به عدد صحیح بدون علامت 8 بیتی معادل تبدیل می‌کند. |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشتهٔ مشخص‌شده که حاوی نمایش عددی به صورت رشته‌ای است را با استفاده از اطلاعات قالب‌بندی و سبک عدد ارائه‌شده به عدد صحیح بدون علامت 8 بیتی معادل تبدیل می‌کند. |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint8_t**\&) | رشتهٔ مشخص‌شده که حاوی نمایش عددی به صورت رشته‌ای است را به عدد صحیح بدون علامت 8 بیتی معادل تبدیل می‌کند. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint8_t**\&) | رشتهٔ مشخص‌شده که حاوی نمایش عددی به صورت رشته‌ای است را با استفاده از اطلاعات قالب‌بندی و سبک عدد ارائه‌شده به عدد صحیح بدون علامت 8 بیتی معادل تبدیل می‌کند. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint8_t**\&) |  |

## فیلدها

| فیلد | توضیح |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | بزرگ‌ترین مقدار ممکن. |
| static constexpr [MinValue](./minvalue/) | کوچک‌ترین مقدار ممکن. |

## توضیحات

```cpp
#include <system/byte.h>

using namespace System;

int main()
{
  auto b1 = Byte::Parse(u"123");
  std::cout << static_cast<uint32_t>(b1) << std::endl;

  try
  {
    auto b2 = Byte::Parse(u"345");
    std::cout << static_cast<uint32_t>(b2) << std::endl;
  }
  catch (const OverflowException &ex)
  {
    std::cerr << ex.what() << std::endl;
  }

  uint8_t b3 = 0;
  if (Byte::TryParse(u"10", b3))
  {
    std::cout << static_cast<uint32_t>(b3) << std::endl;
  }
  else
  {
    std::cerr << "Something went wrong." << std::endl;
  }

  return 0;
}
/*
این مثال کد خروجی زیر را تولید می‌کند:
123
System::OverflowException: مقدار یا خیلی بزرگ بود یا خیلی کوچک برای UInt8
10
*/
```

## موارد مرتبط

* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)