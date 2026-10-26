---
title: UInt32
second_title: Aspose.Slides لـ C++ مرجع API
description: يحتوي على طرق للعمل مع عدد صحيح غير موقع 32-بت.
type: docs
weight: 1977
url: /ar/system/uint32/
---
## هيكل UInt32

يحتوي على طرق للعمل مع عدد صحيح غير موقع 32-بت.

```cpp
class UInt32
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&) | يحوّل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى عدد صحيح غير موقع 32-بت مكافئ. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحوّل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى عدد صحيح غير موقع 32-بت مكافئ باستخدام معلومات التنسيق المقدمة. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحوّل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى عدد صحيح غير موقع 32-بت مكافئ باستخدام معلومات التنسيق المقدمة ونمط العدد. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint32_t**\&) | يحوّل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى عدد صحيح غير موقع 32-بت مكافئ. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint32_t**\&) | يحوّل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى عدد صحيح غير موقع 32-بت مكافئ باستخدام معلومات التنسيق المقدمة ونمط العدد. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint32_t**\&) |  |

## الحقول

| الحقل | الوصف |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | أكبر قيمة ممكنة. |
| static constexpr [MinValue](./minvalue/) | أصغر قيمة ممكنة. |

## انظر أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)