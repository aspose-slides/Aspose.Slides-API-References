---
title: Single
second_title: مرجع API ل Aspose.Slides للـ C++
description: يحتوي على طرق للعمل مع عدد الفاصلة العائمة بدقة مفردة.
type: docs
weight: 1899
url: /ar/system/single/
---
## بنية واحدة

يحتوي على طرق للعمل مع عدد الفاصلة العائمة بدقة مفردة.

```cpp
class Single
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| static **float** [Parse](./parse/)(const [String](../string/)\&) | يحول السلسلة المحددة التي تحتوي على تمثيل النص لعدد إلى قيمة عدد الفاصلة العائمة بدقة مفردة مكافئة. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحول السلسلة المحددة التي تحتوي على تمثيل النص لعدد إلى قيمة عدد الفاصلة العائمة بدقة مفردة مكافئة باستخدام معلومات التنسيق المقدمة. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحول السلسلة المحددة التي تحتوي على تمثيل النص لعدد إلى قيمة عدد الفاصلة العائمة بدقة مفردة مكافئة باستخدام معلومات التنسيق المقدمة ونمط الرقم. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **float**\&) | يحول السلسلة المحددة التي تحتوي على تمثيل النص لعدد إلى قيمة عدد الفاصلة العائمة بدقة مفردة مكافئة. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **float**\&) | يحول السلسلة المحددة التي تحتوي على تمثيل النص لعدد إلى قيمة عدد الفاصلة العائمة بدقة مفردة مكافئة باستخدام معلومات التنسيق المقدمة ونمط الرقم. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **float**\&) |  |

## الحقول

| حقل | الوصف |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | أصغر قيمة موجبة أكبر من الصفر. |
| static constexpr [MaxValue](./maxvalue/) | أكبر قيمة ممكنة. |
| static constexpr [MinValue](./minvalue/) | أصغر قيمة ممكنة. |
| static constexpr [NaN](./nan/) | قيمة ليست عددًا. |
| static constexpr [NegativeInfinity](./negativeinfinity/) | سالب لا نهائي. |
| static constexpr [PositiveInfinity](./positiveinfinity/) | موجب لا نهائي. |

## انظر أيضاً

* Namespace [System](../)
* Library [Aspose.Slides](../../)