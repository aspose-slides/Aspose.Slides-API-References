---
title: UInt64
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحتوي على طرق للعمل مع عدد صحيح غير موقع 64-بت.
type: docs
weight: 1990
url: /ar/system/uint64/
---
## UInt64 هيكل

يحتوي على طرق للعمل مع عدد صحيح غير موقع 64-بت.

```cpp
class UInt64
```

## طرق

| Method | Description |
| --- | --- |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&) | يحول السلسلة المحددة التي تحتوي على تمثيل نصّي للعدد إلى عدد صحيح غير موقع 64-بت مكافئ. |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحول السلسلة المحددة التي تحتوي على تمثيل نصّي للعدد إلى عدد صحيح غير موقع 64-بت مكافئ باستخدام معلومات التنسيق المقدّمة. |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحول السلسلة المحددة التي تحتوي على تمثيل نصّي للعدد إلى عدد صحيح غير موقع 64-بت مكافئ باستخدام معلومات التنسيق ونمط العدد المقدّمة. |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint64_t**\&) | يحول السلسلة المحددة التي تحتوي على تمثيل نصّي للعدد إلى عدد صحيح غير موقع 64-بت مكافئ. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint64_t**\&) | يحول السلسلة المحددة التي تحتوي على تمثيل نصّي للعدد إلى عدد صحيح غير موقع 64-بت مكافئ باستخدام معلومات التنسيق ونمط العدد المقدّرة. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint64_t**\&) |  |

## حقول

| Field | Description |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | أكبر قيمة ممكنة. |
| static constexpr [MinValue](./minvalue/) | أصغر قيمة ممكنة. |

## أنظر أيضًا

* Namespace [System](../)
* Library [Aspose.Slides](../../)