---
title: Double
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: يحتوي على أساليب للعمل مع عدد الفاصلة العائمة بدقة مزدوجة.
type: docs
weight: 1574
url: /ar/system/double/
---
## بنية Double

يحتوي على أساليب للعمل مع عدد الفاصلة العائمة بدقة مزدوجة.

```cpp
class Double
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| static **double** [Parse](./parse/)(const [String](../string/)\&) | يحوِّل السلسلة المحددة التي تحتوي على تمثيل النصي لعدد إلى القيمة العائمة بدقة مزدوجة المكافئة. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحوِّل السلسلة المحددة التي تحتوي على تمثيل النصي لعدد إلى القيمة العائمة بدقة مزدوجة المكافئة باستخدام معلومات التنسيق المقدمة. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | يحوِّل السلسلة المحددة التي تحتوي على تمثيل النصي لعدد إلى القيمة العائمة بدقة مزدوجة المكافئة باستخدام معلومات التنسيق المقدمة ونمط الرقم. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **double**\&) | يحوِّل السلسلة المحددة التي تحتوي على تمثيل النصي لعدد إلى القيمة العائمة بدقة مزدوجة المكافئة. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **double**\&) | يحوِّل السلسلة المحددة التي تحتوي على تمثيل النصي لعدد إلى القيمة العائمة بدقة مزدوجة المكافئة باستخدام معلومات التنسيق المقدمة ونمط الرقم. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **double**\&) |  |
## الحقول

| الحقل | الوصف |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | أصغر قيمة موجبة أكبر من الصفر. |
| static constexpr [MaxValue](./maxvalue/) | أكبر قيمة ممكنة. |
| static constexpr [MinValue](./minvalue/) | أصغر قيمة ممكنة. |
| static constexpr [NaN](./nan/) | قيمة ليست عددًا. |
| static constexpr [NegativeInfinity](./negativeinfinity/) | اللانهاية السالبة. |
| static constexpr [PositiveInfinity](./positiveinfinity/) | اللانهاية الموجبة. |
## انظر أيضًا

* Namespace [System](../)
* Library [Aspose.Slides](../../)