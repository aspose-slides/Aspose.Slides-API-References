---
title: Int64
second_title: مرجع API الخاص بـ Aspose.Slides لـ C++
description: يحتوي على طرق للعمل مع عدد صحيح 64-بت.
type: docs
weight: 1054
url: /ar/system/int64/
---
## فئة Int64

تحتوي على طرق للعمل مع عدد صحيح 64-بت.

```cpp
class Int64
```

## الطرق

| طريقة | وصف |
| --- | --- |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&) | يحوِّل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى عدد صحيح موقّع 64-بت مكافئ. |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحوِّل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى عدد صحيح موقّع 64-بت مكافئ باستخدام معلومات التنسيق المقدمة. |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحوِّل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى عدد صحيح موقّع 64-بت مكافئ باستخدام معلومات التنسيق ونمط العدد المقدمة. |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int64_t**\&) | يحوِّل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى عدد صحيح موقّع 64-بت مكافئ. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int64_t**\&) | يحوِّل السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى عدد صحيح موقّع 64-بت مكافئ باستخدام معلومات التنسيق ونمط العدد المقدمة. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int64_t**\&) |  |

## الحقول

| حقل | وصف |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | أكبر قيمة ممكنة. |
| static constexpr [MinValue](./minvalue/) | أصغر قيمة ممكنة. |

## انظر أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)