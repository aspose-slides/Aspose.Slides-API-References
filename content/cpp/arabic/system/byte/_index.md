---
title: Byte
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحتوي على طرق للعمل مع العدد الصحيح غير الموقع بثمانية بتات.
type: docs
weight: 157
url: /ar/system/byte/
---
## فئة Byte

يحتوي على طرق للتعامل مع عدد صحيح غير موقع بثمانية بتات.

```cpp
class Byte
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&) | يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى عدد صحيح غير موقع بثمانية بتات مكافئ. |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى عدد صحيح غير موقع بثمانية بتات مكافئ باستخدام معلومات التنسيق المقدمة. |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى عدد صحيح غير موقع بثمانية بتات مكافئ باستخدام معلومات التنسيق المقدمة ونمط الرقم. |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint8_t**\&) | يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى عدد صحيح غير موقع بثمانية بتات مكافئ. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint8_t**\&) | يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى عدد صحيح غير موقع بثمانية بتات مكافئ باستخدام معلومات التنسيق المقدمة ونمط الرقم. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint8_t**\&) |  |

## الحقول

| حقل | الوصف |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | أكبر قيمة ممكنة. |
| static constexpr [MinValue](./minvalue/) | أصغر قيمة ممكنة. |

## ملاحظات

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
هذا المثال البرمجي ينتج المخرجات التالية:
123
System::OverflowException: القيمة كانت إما كبيرة جدًا أو صغيرة جدًا بالنسبة إلى UInt8
10
*/
```

## انظر أيضًا

* نطاق [System](../)
* مكتبة [Aspose.Slides](../../)