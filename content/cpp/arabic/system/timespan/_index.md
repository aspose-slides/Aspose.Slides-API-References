---
title: TimeSpan
second_title: Aspose.Slides لـ C++ مرجع API
description: "يمثل فاصلًا زمنيًا. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم فئة System::SmartPtr لإدارة كائنات هذا النوع."
type: docs
weight: 1314
url: /ar/system/timespan/
---
## فئة TimeSpan

يمثل فاصلًا زمنيًا. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم فئة [System::SmartPtr](../smartptr/) لإدارة كائنات هذا النوع.

```cpp
class TimeSpan
```

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [TimeSpan](./) [Add](./add/)([TimeSpan](./)) const | يرجع نسخة جديدة من الفئة [TimeSpan](./) التي تمثل فاصلًا زمنيًا وهو مجموع الفواصل الزمنية التي تمثلها الكائنات الحالية والموضحة. |
| static constexpr int [Compare](./compare/)([TimeSpan](./), [TimeSpan](./)) | يقارن بين كائنين من نوع [TimeSpan](./). |
| constexpr int [CompareTo](./compareto/)([TimeSpan](./)) const | يقارن الكائن الحالي بالكائن المحدد. |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | يقارن الكائن الحالي بالكائن المحدد. |
| [TimeSpan](./) [Duration](./duration/)() const | يرجع نسخة جديدة من الكائن [TimeSpan](./) التي تكون قيمتها القيمة المطلقة للكائن الحالي. |
| constexpr **bool** [Equals](./equals/)([TimeSpan](./)) const | يحدد ما إذا كان الفاصل الزمني الممثل بالكائن الحالي يساوي الفاصل الزمني الممثل بالكائن المحدد. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | يحدد ما إذا كان الفاصل الزمني الممثل بالكائن الحالي يساوي الفاصل الزمني الممثل بالكائن المحدد. |
| static constexpr **bool** [Equals](./equals/)([TimeSpan](./), [TimeSpan](./)) | يرجع true إذا كان الكائنات المحددة تمثل نفس الفاصل الزمني، وإلا - false. |
| static [TimeSpan](./) [FromDays](./fromdays/)(**double**) | يرجع كائنًا جديدًا من نوع [TimeSpan](./) يمثل الفاصل المحدد. |
| static [TimeSpan](./) [FromHours](./fromhours/)(**double**) | يرجع كائنًا جديدًا من نوع [TimeSpan](./) يمثل الفاصل المحدد. |
| static [TimeSpan](./) [FromMilliseconds](./frommilliseconds/)(**double**) | يرجع كائنًا جديدًا من نوع [TimeSpan](./) يمثل الفاصل المحدد. |
| static [TimeSpan](./) [FromMinutes](./fromminutes/)(**double**) | يرجع كائنًا جديدًا من نوع [TimeSpan](./) يمثل الفاصل المحدد. |
| static [TimeSpan](./) [FromSeconds](./fromseconds/)(**double**) | يرجع كائنًا جديدًا من نوع [TimeSpan](./) يمثل الفاصل المحدد. |
| static constexpr [TimeSpan](./) [FromTicks](./fromticks/)(**int64_t**) | يرجع كائنًا جديدًا من نوع [TimeSpan](./) يمثل الفاصل المحدد. |
| constexpr int [get_Days](./get_days/)() const | يرجع جزء الأيام من الفاصل الزمني الممثل بالكائن [TimeSpan](./) الحالي. |
| constexpr int [get_Hours](./get_hours/)() const | يرجع جزء الساعات من الفاصل الزمني الممثل بالكائن [TimeSpan](./) الحالي. |
| constexpr int [get_Milliseconds](./get_milliseconds/)() const | يرجع جزء الميللي ثانية من الفاصل الزمني الممثل بالكائن [TimeSpan](./) الحالي. |
| constexpr int [get_Minutes](./get_minutes/)() const | يرجع جزء الدقائق من الفاصل الزمني الممثل بالكائن [TimeSpan](./) الحالي. |
| constexpr int [get_Seconds](./get_seconds/)() const | يرجع جزء الثواني من الفاصل الزمني الممثل بالكائن [TimeSpan](./) الحالي. |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | يرجع عدد فواصل 100 نانوثانية التي تشكل الفاصل الزمني الممثل بالكائن [TimeSpan](./) الحالي. |
| constexpr **double** [get_TotalDays](./get_totaldays/)() const | يرجع قيمة الكائن [TimeSpan](./) الحالي معبرًا عنها بأيام كاملة وكسرية. |
| constexpr **double** [get_TotalHours](./get_totalhours/)() const | يرجع قيمة الكائن [TimeSpan](./) الحالي معبرًا عنها بساعات كاملة وكسرية. |
| **double** [get_TotalMilliseconds](./get_totalmilliseconds/)() const | يرجع قيمة الكائن [TimeSpan](./) الحالي معبرًا عنها بميللي ثانية كاملة وكسرية. |
| constexpr **double** [get_TotalMinutes](./get_totalminutes/)() const | يرجع قيمة الكائن [TimeSpan](./) الحالي معبرًا عنها بدقائق كاملة وكسرية. |
| constexpr **double** [get_TotalSeconds](./get_totalseconds/)() const | يرجع قيمة الكائن [TimeSpan](./) الحالي معبرًا عنها بثوانٍ كاملة وكسرية. |
| int [GetHashCode](./gethashcode/)() const | يرجع رمز تجزئة للكائن الحالي. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| [TimeSpan](./) [Negate](./negate/)() const | يرجع نسخة جديدة من الكائن [TimeSpan](./) التي تمثل القيمة المعكوسة للكائن [TimeSpan](./) الحالي. |
| constexpr **bool** [operator!=](./operator_not_equal/)([TimeSpan](./)) const | يحدد ما إذا كان الفاصل الزمني الممثل بالكائن الحالي لا يساوي الفاصل الزمني الممثل بالكائن المحدد. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [TimeSpan](./) [operator+](./operator_plus/)([TimeSpan](./)) const | يرجع نسخة جديدة من فئة [TimeSpan](./) التي تمثل فاصلًا زمنيًا وهو مجموع الفواصل الزمنية التي تمثلها الكائنات الحالية والموضحة. |
| [TimeSpan](./) [operator+](./operator_plus/)() const | يعيد نفسه. |
| [TimeSpan](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](./)) | يعين للكائن الحالي الفاصل الزمني الذي هو مجموع الفواصل الزمنية التي تمثلها الكائنات الحالية والموضحة. |
| [TimeSpan](./) [operator-](./operator_minus/)([TimeSpan](./)) const | يرجع نسخة جديدة من فئة [TimeSpan](./) التي تمثل فاصلًا زمنيًا وهو نتيجة طرح الفاصل الزمني الممثل بالكائن المحدد من الفاصل الزمني الممثل بالكائن الحالي. |
| [TimeSpan](./) [operator-](./operator_minus/)() const | يرجع نسخة جديدة من الكائن [TimeSpan](./) التي تمثل القيمة المعكوسة للكائن [TimeSpan](./) الحالي. |
| [TimeSpan](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](./)) | يعين للكائن الحالي الفاصل الزمني الذي هو نتيجة طرح الفاصل الزمني الممثل بالكائن المحدد من الفاصل الزمني الممثل بالكائن الحالي. |
| [TimeSpan](./) [operator/](./operator_div/)(**double**) const |  |
| constexpr **double** [operator/](./operator_div/)([TimeSpan](./)) const |  |
| [TimeSpan](./)\& [operator/=](./operator_div_equal/)(**double**) |  |
| constexpr **bool** [operator<](./operator_less/)([TimeSpan](./)) const | يحدد ما إذا كان الفاصل الزمني الممثل بالكائن الحالي أقصر من الفاصل الزمني الممثل بالكائن المحدد. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([TimeSpan](./)) const | يحدد ما إذا كان الفاصل الزمني الممثل بالكائن الحالي أقصر من أو يساوي الفاصل الزمني الممثل بالكائن المحدد. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| constexpr [TimeSpan](./)\& [operator=](./operator_equal/)(const [TimeSpan](./)\&) | يضبط الفاصل الزمني الممثل بالكائن [TimeSpan](./) المحدد إلى الكائن [TimeSpan](./) الحالي. |
| constexpr **bool** [operator==](./operator_equal_equal/)([TimeSpan](./)) const | يحدد ما إذا كان الفاصل الزمني الممثل بالكائن الحالي يساوي الفاصل الزمني الممثل بالكائن المحدد. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([TimeSpan](./)) const | يحدد ما إذا كان الفاصل الزمني الممثل بالكائن الحالي أطول من الفاصل الزمني الممثل بالكائن المحدد. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([TimeSpan](./)) const | يحدد ما إذا كان الفاصل الزمني الممثل بالكائن الحالي أطول من أو يساوي الفاصل الزمني الم Represented by the specified object. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&) | تحول السلسلة إلى كائن [TimeSpan](./) مكافئ. |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | تحول السلسلة إلى كائن [TimeSpan](./) مكافئ باستخدام موفر الصيغة المحدد. |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | تحول السلسلة إلى كائن [TimeSpan](./) مكافئ باستخدام الصيغ المحددة، موفر الصيغة والأنماط. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | تحول السلسلة إلى كائن [TimeSpan](./) مكافئ باستخدام الصيغة المحددة، موفر الصيغة والأنماط. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| [TimeSpan](./) [Subtract](./subtract/)([TimeSpan](./)) const | يرجع نسخة جديدة من فئة [TimeSpan](./) التي تمثل فاصلًا زمنيًا وهو نتيجة طرح الفاصل الزمني الممثل بالكائن المحدد من الفاصل الزمني الممثل بالكائن الحالي. |
| constexpr [TimeSpan](./timespan/)() | ينشئ كائن [TimeSpan](./) يمثل فاصلًا زمنيًا صفرًا. |
| explicit constexpr [TimeSpan](./timespan/)(**int64_t**) | ينشئ نسخة من فئة [TimeSpan](./) تمثل الفاصل الزمني المحدد. |
|  [TimeSpan](./timespan/)(int, int, int) | ينشئ نسخة من فئة [TimeSpan](./) تمثل الفاصل الزمني الذي يساوي مجموع الساعات والدقائق والثواني المحددة. |
|  [TimeSpan](./timespan/)(int, int, int, int, int) | ينشئ نسخة من فئة [TimeSpan](./) تمثل الفاصل الزمني الذي يساوي مجموع الساعات والدقائق والثواني والميللي ثانية المحددة. |
| constexpr [TimeSpan](./timespan/)(const [TimeSpan](./)\&) | ينشئ كائن [TimeSpan](./) يمثل الفاصل الزمني المساوي للفاصل الزمني الممثل بالكائن [TimeSpan](./) المحدد. |
| [String](../string/) [ToString](./tostring/)() const | يرجع تمثيل السلسلة للفاصل الزمني الممثل بالكائن الحالي. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | يحول قيمة الكائن الحالي إلى تمثيل سلسلة مكافئ، باستخدام الصيغة المحددة. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | يحول قيمة الكائن الحالي إلى تمثيل سلسلة مكافئ، باستخدام الصيغة وموفر الصيغة المحددين. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [TimeSpan](./)\&) | تحول السلسلة إلى كائن [TimeSpan](./) مكافئ وتُرجع نتيجة التحويل. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | تحول السلسلة إلى كائن [TimeSpan](./) مكافئ باستخدام موفر الصيغة المحدد وتُرجع نتيجة التحويل. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | تحول السلسلة إلى كائن [TimeSpan](./) مكافئ باستخدام الصيغ المحددة وموفر الصيغة، وتُرجع نتيجة التحويل. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | تحول السلسلة إلى كائن [TimeSpan](./) مكافئ باستخدام الصيغة، موفر الصيغة والأنماط المحددة، وتُرجع نتيجة التحويل. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | تحول السلسلة إلى كائن [TimeSpan](./) مكافئ باستخدام الصيغ، موفر الصيغة والأنماط المحددة، وتُرجع نتيجة التحويل. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | تحول السلسلة إلى كائن [TimeSpan](./) مكافئ باستخدام الصيغة وموفر الصيغة المحددين، وتُرجع نتيجة التحويل. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | يرجع كائن [TypeInfo](../typeinfo/) يمثل بنية [TimeSpan](./). |

## الحقول

| الحقل | الوصف |
| --- | --- |
| static [MaxValue](./maxvalue/) | الكائن [TimeSpan](./) الذي يمثل أطول فاصل ممكن. |
| static [MinValue](./minvalue/) | /// الكائن [TimeSpan](./) الذي يمثل أقصر فاصل ممكن. |
| static constexpr [TicksPerDay](./ticksperday/) | عدد فواصل 100 نانوثانية في اليوم (فاصل 24 ساعة). |
| static constexpr [TicksPerHour](./ticksperhour/) | عدد فواصل 100 نانوثانية في الساعة. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | عدد فواصل 100 نانوثانية في الميلي ثانية. |
| static constexpr [TicksPerMinute](./ticksperminute/) | عدد فواصل 100 نانوثانية في الدقيقة. |
| static constexpr [TicksPerSecond](./tickspersecond/) | عدد فواصل 100 نانوثانية في الثانية. |
| static [Zero](./zero/) | الكائن [TimeSpan](./) الذي يمثل فاصلًا صفريًا. |

## ملاحظات

```cpp
#include "system/datetime.h"
#include "system/timespan.h"
#include <iostream>

int main()
{
  const auto date1 = System::DateTime(2021, 01, 01);
  const auto date2 = System::DateTime(2021, 10, 30);

  const auto interval = date2 - date1;

  std::cout << "Number of ticks: " << interval.get_Ticks() << std::endl;
  std::cout << "Number of milliseconds: " << interval.get_Milliseconds() << std::endl;
  std::cout << "Total number of milliseconds: " << interval.get_TotalMilliseconds() << std::endl;
  std::cout << "Number of minutes: " << interval.get_Minutes() << std::endl;
  std::cout << "Total number of minutes: " << interval.get_TotalMinutes() << std::endl;
  std::cout << "Number of hours: " << interval.get_Hours() << std::endl;
  std::cout << "Total number of hours: " << interval.get_Hours() << std::endl;
  std::cout << "Number of days: " << interval.get_Days() << std::endl;
  std::cout << "Total number of days: " << interval.get_TotalDays() << std::endl;

  return 0;
}
/*
هذا المثال البرمجي ينتج المخرجات التالية:
عدد النقرات: 260928000000000
عدد الميللي ثانية: 0
إجمالي عدد الميللي ثانية: 2.60928e+10
عدد الدقائق: 0
إجمالي عدد الدقائق: 434880
عدد الساعات: 0
إجمالي عدد الساعات: 0
عدد الأيام: 302
إجمالي عدد الأيام: 302
*/
```

## انظر أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)