---
title: DateTime
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يمثل قيمة تاريخ ووقت محددة على استمرارية الزمن. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم أبداً الفئة System::SmartPtr لإدارة كائنات هذا النوع."
type: docs
weight: 222
url: /ar/system/datetime/
---
## فئة DateTime

يمثل قيمة تاريخ ووقت محددة على خط الزمن. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم أبداً فئة [System::SmartPtr](../smartptr/) لإدارة كائنات من هذا النوع.

```cpp
class DateTime
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [DateTime](./) [Add](./add/)([TimeSpan](../timespan/)) const | إرجاع نسخة جديدة من [DateTime](./) فئة تمثل قيمة تاريخ ووقت تنتج عن إضافة الفاصل الزمني المحدد إلى قيمة التاريخ والوقت الممثلة بواسطة الكائن الحالي. |
| [DateTime](./) [AddDays](./adddays/)(**double**) const | إرجاع نسخة جديدة من [DateTime](./) فئة تمثل قيمة التاريخ والوقت التي هي مجموع القيمة الممثلة بواسطة الكائن الحالي وعدد الأيام المحدد. |
| [DateTime](./) [AddHours](./addhours/)(**double**) const | إرجاع نسخة جديدة من [DateTime](./) فئة تمثل قيمة التاريخ والوقت التي هي مجموع القيمة الممثلة بواسطة الكائن الحالي وعدد الساعات المحدد. |
| [DateTime](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | إرجاع نسخة جديدة من [DateTime](./) فئة تمثل قيمة التاريخ والوقت التي هي مجموع القيمة الممثلة بواسطة الكائن الحالي وعدد الميليثواني المحدد. |
| [DateTime](./) [AddMinutes](./addminutes/)(**double**) const | إرجاع نسخة جديدة من [DateTime](./) فئة تمثل قيمة التاريخ والوقت التي هي مجموع القيمة الممثلة بواسطة الكائن الحالي وعدد الدقائق المحدد. |
| [DateTime](./) [AddMonths](./addmonths/)(int) const | إرجاع نسخة جديدة من [DateTime](./) فئة تمثل قيمة التاريخ والوقت التي هي مجموع القيمة الممثلة بواسطة الكائن الحالي وعدد الشهور المحدد. |
| [DateTime](./) [AddSeconds](./addseconds/)(**double**) const | إرجاع نسخة جديدة من [DateTime](./) فئة تمثل قيمة التاريخ والوقت التي هي مجموع القيمة الممثلة بواسطة الكائن الحالي وعدد الثواني المحدد. |
| [DateTime](./) [AddTicks](./addticks/)(**int64_t**) const | إرجاع نسخة جديدة من [DateTime](./) فئة تمثل قيمة التاريخ والوقت التي هي مجموع القيمة الممثلة بواسطة الكائن الحالي وعدد فواصل 100-نانوثانية المحدد. |
| [DateTime](./) [AddYears](./addyears/)(int) const | إرجاع نسخة جديدة من [DateTime](./) فئة تمثل قيمة التاريخ والوقت المساوية لتلك الممثلة بالكائن الحالي مع زيادة مكون السنة بالعدد المحدد. |
| static constexpr int [Compare](./compare/)([DateTime](./), [DateTime](./)) | يقارن قيمتين ممثلتين بواسطة مثيلات [DateTime](./) فئة ويعيد القيمة التي تشير إلى الموقع النسبي للقيم على خط الزمن. |
| constexpr int [CompareTo](./compareto/)([DateTime](./)) const | يقارن قيمتي تاريخ ووقت ممثلتين بواسطة الكائن الحالي ومثيل [DateTime](./) فئة ويعيد القيمة التي تشير إلى الموقع النسبي للقيم على خط الزمن. |
| constexpr [DateTime](./datetime/)() | يبني نسخة تمثل أصغر قيمة ممكنة للتاريخ والوقت مساوية لـ MinValue. |
| [DateTime](./datetime/)(int, int, int) | يبني نسخة تمثل قيمة تاريخ ووقت محددة كسنة وشهر ويوم معينين. |
| [DateTime](./datetime/)(int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | يبني نسخة تمثل قيمة تاريخ ووقت محددة كسنة، شهر، ويوم معين في التقويم المحدد. |
| [DateTime](./datetime/)(int, int, int, int, int, int) | يبني نسخة تمثل قيمة تاريخ ووقت محددة كسنة، شهر، يوم، ساعة، دقيقة وثانية معينة. |
| [DateTime](./datetime/)(int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | يبني نسخة تمثل قيمة تاريخ ووقت محددة كسنة، شهر، يوم، ساعة، دقيقة وثانية معينة. |
| [DateTime](./datetime/)(int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | يبني نسخة تمثل قيمة تاريخ ووقت محددة كسنة، شهر، يوم، ساعة، دقيقة وثانية في التقويم المحدد. |
| [DateTime](./datetime/)(int, int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | يبني نسخة تمثل قيمة تاريخ ووقت محددة كسنة، شهر، يوم، ساعة، دقيقة، ثانية ومليثانية معينة. |
| [DateTime](./datetime/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [DateTimeKind](../datetimekind/)) | يبني نسخة تمثل قيمة تاريخ ووقت محددة كسنة، شهر، يوم، ساعة، دقيقة، ثانية ومليثانية في التقويم المحدد. |
| [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/)) | يبني نسخة تمثل قيمة تاريخ ووقت محددة كعدد من التيكات. |
| [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/), **bool**) | يبني نسخة تمثل قيمة تاريخ ووقت محددة كعدد من التيكات. للاستخدام الداخلي. |
| [DateTime](./datetime/)(const [DateTime](./)\&) | ينسخ نسخة لإنشاء نسخة جديدة. |
| static int [DaysInMonth](./daysinmonth/)(int, int) | إرجاع عدد الأيام في الشهر المحدد من السنة المحددة. |
| static constexpr **bool** [Equals](./equals/)([DateTime](./), [DateTime](./)) | يحدد ما إذا كانت المثيلات المحددة من [DateTime](./) فئة تمثل نفس قيمة التاريخ والوقت. |
| constexpr **bool** [Equals](./equals/)([DateTime](./)) const | يحدد ما إذا كان المثيل المحدد من [DateTime](./) فئة يمثل نفس قيمة التاريخ والوقت كما الكائن الحالي. |
| static [DateTime](./) [FromBinary](./frombinary/)(**int64_t**) | يفك تسلسل قيمة التاريخ والوقت من عدد صحيح غير موقع 64-bit محدد ويضبط نسخة جديدة من [DateTime](./) فئة لتلك القيمة. |
| static [DateTime](./) [FromFileTime](./fromfiletime/)(**int64_t**) | تحويل وقت الملف المحدد إلى نسخة من [DateTime](./) فئة تمثل نفس قيمة التاريخ والوقت كوقت محلي. |
| static [DateTime](./) [FromFileTimeUtc](./fromfiletimeutc/)(**int64_t**) | تحويل وقت الملف المحدد إلى نسخة من [DateTime](./) فئة تمثل نفس قيمة التاريخ والوقت كوقت UTC. |
| static [DateTime](./) [FromOADate](./fromoadate/)(**double**) | إرجاع نسخة من [DateTime](./) فئة تمثل قيمة التاريخ والوقت المكافئة لتاريخ OLE Automation المحدد. |
| static [DateTime](./) [FromUnixTime](./fromunixtime/)(time_t) | تحويل قيمة وقت Unix المحددة إلى نسخة من [DateTime](./) فئة. للاستخدام الداخلي. |
| constexpr [DateTime](./) [get_Date](./get_date/)() const | إرجاع نسخة جديدة من [DateTime](./) فئة تمثل جزء التاريخ من التاريخ والوقت الممثلين بالكائن الحالي مع تعيين جميع مكونات جزء الوقت إلى 0. |
| int [get_Day](./get_day/)() const | إرجاع الرقم الترتيبي لليوم في الشهر الممثل بالكائن الحالي. |
| constexpr [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | إرجاع قيمة تمثل يوم الأسبوع الممثل بالكائن الحالي. |
| int [get_DayOfYear](./get_dayofyear/)() const | إرجاع الرقم الترتيبي لليوم في السنة الممثل بالكائن الحالي. |
| constexpr int [get_Hour](./get_hour/)() const | إرجاع مكون الساعة من قيمة التاريخ والوقت الممثل بالكائن الحالي. |
| constexpr [DateTimeKind](../datetimekind/) [get_Kind](./get_kind/)() const | إرجاع قيمة تمثل ما إذا كان التاريخ والوقت الممثل بالكائن الحالي هو محلي أو UTC أو لا شيء من الاثنين. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | إرجاع مكون المليثانية من قيمة التاريخ والوقت الممثل بالكائن الحالي. |
| constexpr int [get_Minute](./get_minute/)() const | إرجاع مكون الدقيقة من قيمة التاريخ والوقت الممثل بالكائن الحالي. |
| int [get_Month](./get_month/)() const | إرجاع الرقم الترتيبي للشهر في السنة الممثل بالكائن الحالي. |
| static [DateTime](./) [get_Now](./get_now/)() | إرجاع نسخة من [DateTime](./) فئة تمثل الوقت الحالي كوقت محلي. |
| constexpr int [get_Second](./get_second/)() const | إرجاع مكون الثانية من قيمة التاريخ والوقت الممثل بالكائن الحالي. |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | إرجاع عدد فواصل 100 نانوثانية المنقضية منذ 0:00:00 UTC، 1 يناير 0001 في التقويم الغريغوري حتى التاريخ والوقت الممثلين بالكائن الحالي. |
| constexpr [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | إرجاع القيمة التي تمثل الفاصل الزمني من بداية اليوم الممثل بالكائن الحالي حتى قيمة التاريخ والوقت الممثل بالكائن الحالي. |
| static [DateTime](./) [get_Today](./get_today/)() | إرجاع نسخة من [DateTime](./) فئة تمثل التاريخ الحالي مع تعيين جميع مكونات جزء الوقت إلى 0. |
| static [DateTime](./) [get_UtcNow](./get_utcnow/)() | إرجاع نسخة من [DateTime](./) فئة تمثل الوقت الحالي كوقت UTC. |
| int [get_Year](./get_year/)() const | إرجاع السنة الممثلة بالكائن الحالي. |
| void [GetDateComponents](./getdatecomponents/)(int\&, int\&, int\&) const | الحصول على أجزاء التاريخ. للاستخدام الداخلي. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)() const | إرجاع مصفوفة من السلاسل حيث كل عنصر هو تمثيل نصي للكائن الحالي مُنسّق بأحد المحددات القياسية لتنسيق التاريخ والوقت. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t) const | إرجاع مصفوفة من السلاسل حيث كل عنصر هو تمثيل نصي للكائن الحالي مُنسّق بالمحدد القياسي لتنسيق التاريخ والوقت المحدد. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | إرجاع مصفوفة من السلاسل حيث كل عنصر هو تمثيل نصي للكائن الحالي مُنسّق بأحد المحددات القياسية لتنسيق التاريخ والوقت ومزود التنسيق المحدد. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | إرجاع مصفوفة من السلاسل حيث كل عنصر هو تمثيل نصي للكائن الحالي مُنسّق بالمحدد القياسي لتنسيق التاريخ والوقت ومزود التنسيق المحدد. |
| int [GetHashCode](./gethashcode/)() const | إرجاع قيمة تجزئة (hash) للكائن الحالي. |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)() const | يحدد ما إذا كانت قيمة التاريخ والوقت الممثلة بالكائن الحالي تقع ضمن نطاق التوقيت الصيفي للمنطقة الزمنية الحالية. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | يحدد ما إذا كانت السنة المحددة سنة كبيسة. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| constexpr **bool** [operator!=](./operator_not_equal/)([DateTime](./)) const | يحدد ما إذا كان الكائن الحالي والكائن [DateTime](./) المحدد يمثلان قيم تاريخ ووقت متميزة. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTime](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | إرجاع نسخة جديدة من [DateTime](./) فئة تمثل قيمة التاريخ والوقت التي هي مجموع القيمة الممثلة بالكائن الحالي والفاصل الزمني المحدد. |
| [DateTime](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](../timespan/)) | يضبط الكائن الحالي إلى قيمة التاريخ والوقت التي هي مجموع القيمة الممثلة به والفاصل الزمني المحدد. |
| [DateTime](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | إرجاع نسخة جديدة من [DateTime](./) فئة تمثل قيمة التاريخ والوقت التي هي نتيجة طرح الفاصل الزمني المحدد من القيمة الممثلة بالكائن الحالي. |
| constexpr [TimeSpan](../timespan/) [operator-](./operator_minus/)([DateTime](./)) const | إرجاع نسخة من [TimeSpan](../timespan/) فئة تمثل الفاصل الزمني بين قيم التاريخ والوقت الممثلة بالكائن الحالي والكائن المحدد. |
| [DateTime](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](../timespan/)) | يضبط الكائن الحالي إلى قيمة التاريخ والوقت التي هي نتيجة طرح الفاصل الزمني المحدد من قيمة التاريخ والوقت الممثلة بالكائن الحالي. |
| constexpr **bool** [operator<](./operator_less/)([DateTime](./)) const | يحدد ما إذا كان الكائن الحالي يمثل قيمة تاريخ ووقت أقدم من القيمة الممثلة بواسطة الكائن [DateTime](./) المحدد. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([DateTime](./)) const | يحدد ما إذا كان الكائن الحالي يمثل قيمة تاريخ ووقت أقدم أو مساوية للقيمة الممثلة بواسطة الكائن [DateTime](./) المحدد. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| [DateTime](./)\& [operator=](./operator_equal/)(const [DateTime](./)\&) | يعين القيمة الممثلة بواسطة المثيل [DateTime](./) المحدد إلى الكائن الحالي. |
| constexpr **bool** [operator==](./operator_equal_equal/)([DateTime](./)) const | يحدد ما إذا كان الكائن الحالي والكائن [DateTime](./) المحدد يمثلان نفس قيمة التاريخ والوقت. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([DateTime](./)) const | يحدد ما إذا كان الكائن الحالي يمثل قيمة التاريخ والوقت التي تكون لاحقة للقيمة التي يمثلها الكائن [DateTime](./) المحدد. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([DateTime](./)) const | يحدد ما إذا كان الكائن الحالي يمثل قيمة التاريخ والوقت التي تكون لاحقة أو مساوية للقيمة التي يمثلها الكائن [DateTime](./) المحدد. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&) | يعكّ تمثيل السلسلة المحدد لقيمة التاريخ والوقت إلى الكائن [DateTime](./) المكافئ. |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | يعكّ تمثيل السلسلة المحدد لقيمة التاريخ والوقت إلى الكائن [DateTime](./) المكافئ باستخدام معلومات تنسيق مخصصة للثقافة. |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | يعكّ تمثيل السلسلة المحدد لقيمة التاريخ والوقت إلى الكائن [DateTime](./) المكافئ باستخدام التنسيق المحدد ومعلومات تنسيق مخصصة للثقافة. يجب أن يتطابق تنسيق تمثيل السلسلة مع التنسيق المحدد تمامًا. يرفع استثناءً إذا فشل التحويل. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | يعكّ تمثيل السلسلة المحدد لقيمة التاريخ والوقت إلى الكائن [DateTime](./) المكافئ باستخدام التنسيقات المحددة، ومعلومات تنسيق مخصصة للثقافة، والنمط. يجب أن يتطابق تنسيق تمثيل السلسلة مع أحد أو أكثر من التنسيقات المحددة تمامًا. يرفع استثناءً إذا فشل التحويل. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [SpecifyKind](./specifykind/)([DateTime](./), [DateTimeKind](../datetimekind/)) | يبني كائنًا جديدًا [DateTime](./) يمثل نفس عدد العلامات كما في الكائن [DateTime](./) المحدد ويمثل الوقت المحلي أو وقت UTC أو لا شيء حسب ما يحدده الوسيط **kind**. |
| [DateTime](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | يعيد نسخة جديدة من فئة [DateTime](./) تمثل قيمة التاريخ والوقت الناتجة عن طرح الفاصل الزمني المحدد من القيمة التي يمثلها الكائن الحالي. |
| constexpr [TimeSpan](../timespan/) [Subtract](./subtract/)([DateTime](./)) const | يعيد نسخة من فئة [TimeSpan](../timespan/) تمثل الفاصل الزمني بين قيمتي التاريخ والوقت التي يمثلها الكائن الحالي والكائن المحدد. |
| **int64_t** [ToBinary](./tobinary/)() const | يسلسل الكائن الحالي. |
| **int64_t** [ToFileTime](./tofiletime/)() const | يعيد قيمة تمثل قيمة التاريخ والوقت التي يمثلها الكائن الحالي كوقت ملف. |
| **int64_t** [ToFileTimeUtc](./tofiletimeutc/)() const | يحوّل قيمة التاريخ والوقت التي يمثلها الكائن الحالي إلى وقت ملف بتوقيت UTC. |
| [DateTime](./) [ToLocalTime](./tolocaltime/)() const | يعيد نسخة جديدة من فئة [DateTime](./) تمثل قيمة التاريخ والوقت التي يمثلها الكائن الحالي كوقت محلي. |
| [String](../string/) [ToLongDateString](./tolongdatestring/)() const | يعيد سلسلة تحتوي على تمثيل تاريخ طويل للكائن الحالي. |
| [String](../string/) [ToLongTimeString](./tolongtimestring/)() const | يعيد سلسلة تحتوي على تمثيل وقت طويل للكائن الحالي. |
| **double** [ToOADate](./tooadate/)() const | يعيد قيمة التاريخ والوقت التي يمثلها الكائن الحالي ك تاريخ OLE Automation. |
| [String](../string/) [ToShortDateString](./toshortdatestring/)() const | يعيد سلسلة تحتوي على تمثيل تاريخ قصير للكائن الحالي. |
| [String](../string/) [ToShortTimeString](./toshorttimestring/)() const | يعيد سلسلة تحتوي على تمثيل وقت قصير للكائن الحالي. |
| [String](../string/) [ToString](./tostring/)() const | يعيد تمثيل السلسلة لقيمة التاريخ والوقت التي يمثلها الكائن الحالي باستخدام قواعد التنسيق المعرفة من قبل الثقافة الحالية. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | يعيد تمثيل السلسلة لقيمة التاريخ والوقت التي يمثلها الكائن الحالي باستخدام التنسيق المحدد وقواعد التنسيق المعرفة من قبل الثقافة الحالية. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | يعيد تمثيل السلسلة لقيمة التاريخ والوقت التي يمثلها الكائن الحالي باستخدام معلومات التنسيق المحددة. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | يعيد تمثيل السلسلة لقيمة التاريخ والوقت التي يمثلها الكائن الحالي باستخدام معلومات التنسيق المحددة. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [DateTime](./) [ToUniversalTime](./touniversaltime/)() const | يعيد نسخة جديدة من فئة [DateTime](./) تمثل قيمة التاريخ والوقت التي يمثلها الكائن الحالي كوقت UTC. |
| time_t [ToUnixTime](./tounixtime/)() const | يعيد قيمة تمثل قيمة التاريخ والوقت التي يمثلها الكائن الحالي كوقت يونكس. FOR INTERNAL USE. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTime](./)\&) | يعكّ تمثيل السلسلة المحدد لقيمة التاريخ والوقت إلى الكائن [DateTime](./) المكافئ. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | يعكّ تمثيل السلسلة المحدد لقيمة التاريخ والوقت إلى الكائن [DateTime](./) المكافئ باستخدام معلومات تنسيق مخصصة للثقافة والنمط المحدد. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | يعكّ تمثيل السلسلة المحدد لقيمة التاريخ والوقت إلى الكائن [DateTime](./) المكافئ باستخدام التنسيق المحدد ومعلومات تنسيق مخصصة للثقافة والنمط. يجب أن يتطابق تنسيق تمثيل السلسلة مع التنسيق المحدد تمامًا. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | يعكّ تمثيل السلسلة المحدد لقيمة التاريخ والوقت إلى الكائن [DateTime](./) المكافئ باستخدام التنسيقات المحددة، ومعلومات تنسيق مخصصة للثقافة، والنمط. يجب أن يتطابق تنسيق تمثيل السلسلة مع أحد أو أكثر من التنسيقات المحددة تمامًا. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | يعيد كائن [TypeInfo](../typeinfo/) يحتوي على معلومات حول هذه الفئة. |
## الحقول

| الحقل | الوصف |
| --- | --- |
| static constexpr [MaxTicks](./maxticks/) | عدد الـ 100 نانوثانية في الفاصل الزمني بين القيمة الصغرى الممكنة والقيمة الكبرى الممكنة [DateTime](./). |
| static [MaxValue](./maxvalue/) | نسخة من فئة [DateTime](./) تمثل أقصى قيمة ممكنة للتاريخ والوقت. |
| static constexpr [MinTicks](./minticks/) | الحد الأدنى لعدد العلامات التي يمكن أن تمثلها نسخة من فئة [DateTime](./). |
| static [MinValue](./minvalue/) | نسخة من فئة [DateTime](./) تمثل أصغر قيمة ممكنة للتاريخ والوقت. |
| static constexpr [TicksPerDay](./ticksperday/) | عدد العلامات في اليوم. |
| static constexpr [TicksPerHour](./ticksperhour/) | عدد العلامات في الساعة. |
| static constexpr [TicksPerMicrosecond](./tickspermicrosecond/) | عدد العلامات في الميكروثانية. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | عدد العلامات في المللي ثانية. |
| static constexpr [TicksPerMinute](./ticksperminute/) | عدد العلامات في الدقيقة. |
| static constexpr [TicksPerSecond](./tickspersecond/) | عدد العلامات في الثانية. |
| static [UnixEpoch](./unixepoch/) | نسخة من فئة [DateTime](./) تمثل بداية حقبة يونكس (1970.01.01 00:00:00). |
## ملاحظات

```cpp
#include "system/console.h"
#include "system/date_time.h"

int main()
{
  using namespace System;

  // أنشئ نسخة من الفئة 'DateTime'.
  DateTime dateTime{1990, 10, 30};

  // طبع النسخة بعدة صيغ.
  Console::WriteLine(dateTime.ToShortDateString());
  Console::WriteLine(dateTime.ToShortTimeString());
  Console::WriteLine(dateTime.ToString());

  return 0;
}
/*
هذا المثال البرمجي ينتج المخرجات التالية:
30.10.1990
0:00
30.10.1990 0:00:00
*/
```

## انظر أيضًا

* Namespace [System](../)
* Library [Aspose.Slides](../../)