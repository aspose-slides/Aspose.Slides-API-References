---
title: SByte
second_title: مرجع API Aspose.Slides للـ C++
description: يحتوي على طرق للعمل مع العدد الصحيح 8-bit.
type: docs
weight: 1873
url: /ar/system/sbyte/
---
## SByte struct

يحتوي على طرق للعمل مع العدد الصحيح الموقّع 8-bit.

```cpp
class SByte
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&) | يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لرقم إلى عدد صحيح موقع 8-bit مكافئ. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لرقم إلى عدد صحيح موقع 8-bit مكافئ باستخدام معلومات التنسيق المقدمة. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لرقم إلى عدد صحيح موقع 8-bit مكافئ باستخدام معلومات التنسيق المقدمة ونمط الرقم. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int8_t**\&) | يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لرقم إلى عدد صحيح موقع 8-bit مكافئ. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int8_t**\&) | يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل نصي لرقم إلى عدد صحيح موقع 8-bit مكافئ باستخدام معلومات التنسيق المقدمة ونمط الرقم. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int8_t**\&) |  |

## الحقول

| الحقل | الوصف |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | أكبر قيمة ممكنة. |
| static constexpr [MinValue](./minvalue/) | أصغر قيمة ممكنة. |

## انظر أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)