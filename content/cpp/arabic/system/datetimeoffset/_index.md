---
title: DateTimeOffset
second_title: Aspose.Slides للغة C++ دليل المرجع
description: "يحتوي على تاريخ ووقت اليوم بالنسبة إلى التوقيت العالمي المنسق. يجب تخصيص كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام عامل new، حيث سيؤدي ذلك إلى أخطاء وقت تشغيل أو أخطاء تأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 235
url: /ar/system/datetimeoffset/
---
## DateTimeOffset فئة

يحتوي على التاريخ والوقت من اليوم بالنسبة إلى التوقيت العالمي المنسق. يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../makeobject/) فقط. لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام عامل new، لأن ذلك سيتسبب في أخطاء تشغيلية و/أو أخطاء تأكيدية. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class DateTimeOffset
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [DateTimeOffset](./) [Add](./add/)([TimeSpan](../timespan/)) const | يضيف فترة زمنية محددة إلى الكائن [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddDays](./adddays/)(**double**) const | يضيف عددًا محددًا من الأيام إلى الكائن [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddHours](./addhours/)(**double**) const | يضيف عددًا محددًا من الساعات إلى الكائن [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | يضيف عددًا محددًا من المللي ثانية إلى الكائن [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMinutes](./addminutes/)(**double**) const | يضيف عددًا محددًا من الدقائق إلى الكائن [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMonths](./addmonths/)(int) const | يضيف عددًا محددًا من الشهور إلى الكائن [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddSeconds](./addseconds/)(**double**) const | يضيف عددًا محددًا من الثواني إلى الكائن [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddTicks](./addticks/)(**int64_t**) const | يضيف عددًا محددًا من النقرات إلى الكائن [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddYears](./addyears/)(int) const | يضيف عددًا محددًا من السنوات إلى الكائن [DateTimeOffset](./). |
| static int [Compare](./compare/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | يقارن بين كائنين من نوع [DateTimeOffset](./). |
| int [CompareTo](./compareto/)(const [DateTimeOffset](./)\&) const | يقارن بين كائنين من نوع [DateTimeOffset](./). |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | يقارن بين كائنين من نوع [DateTimeOffset](./). |
| constexpr [DateTimeOffset](./datetimeoffset/)() | منشئ افتراضي. |
|  [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/)) | منشئ. |
|  [DateTimeOffset](./datetimeoffset/)(**int64_t**, [TimeSpan](../timespan/)) | منشئ. |
|  [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/), [TimeSpan](../timespan/)) | منشئ. |
|  [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, [TimeSpan](../timespan/)) | منشئ. |
|  [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, [TimeSpan](../timespan/)) | منشئ. |
|  [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [TimeSpan](../timespan/)) | منشئ. |
| static **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | يتحقق مما إذا كان كائنان من نوع [DateTimeOffset](./) يمثلان نفس نقطة الزمن. |
| **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&) const | يتحقق مما إذا كان كائنان من نوع [DateTimeOffset](./) يمثلان نفس نقطة الزمن. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | يتحقق مما إذا كان كائنان من نوع [DateTimeOffset](./) يمثلان نفس نقطة الزمن. |
| **bool** [EqualsExact](./equalsexact/)(const [DateTimeOffset](./)\&) const | يتحقق مما إذا كان كائنان من نوع [DateTimeOffset](./) يمثلان نفس نقطة الزمن ولهما نفس الإزاحة. |
| **bool** [EqualsExact](./equalsexact/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | يتحقق مما إذا كان كائنان من نوع [DateTimeOffset](./) يمثلان نفس نقطة الزمن ولهما نفس الإزاحة. |
| static [DateTimeOffset](./) [FromFileTime](./fromfiletime/)(**int64_t**) | يحول وقت الملف [Convert](../convert/)[Windows](../../system.windows/) إلى تاريخ ووقت مع إزاحة الوقت المحلي. |
| static [DateTimeOffset](./) [FromUnixTimeMilliseconds](./fromunixtimemilliseconds/)(**int64_t**) | [Convert](../convert/) وقت يونكس إلى كائن [DateTimeOffset](./). |
| static [DateTimeOffset](./) [FromUnixTimeSeconds](./fromunixtimeseconds/)(**int64_t**) | [Convert](../convert/) وقت يونكس إلى كائن [DateTimeOffset](./). |
| [DateTime](../datetime/) [get_Date](./get_date/)() const | يحصل على عنصر التاريخ من الكائن الحالي. |
| [DateTime](../datetime/) [get_DateTime](./get_datetime/)() const | يحصل على قيمة [DateTime](../datetime/). |
| int [get_Day](./get_day/)() const | يحصل على يوم الشهر من الكائن الحالي. |
| [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | يحصل على يوم الأسبوع من الكائن الحالي. |
| int [get_DayOfYear](./get_dayofyear/)() const | يحصل على يوم السنة من الكائن الحالي. |
| int [get_Hour](./get_hour/)() const | يحصل على عنصر الساعة من الكائن الحالي. |
| [DateTime](../datetime/) [get_LocalDateTime](./get_localdatetime/)() const | يحصل على قيمة [DateTime](../datetime/) التي تمثل التاريخ والوقت المحلي. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | يحصل على عنصر المللي ثانية من الكائن الحالي. |
| int [get_Minute](./get_minute/)() const | يحصل على عنصر الدقيقة من الكائن الحالي. |
| int [get_Month](./get_month/)() const | يحصل على عنصر الشهر من الكائن الحالي. |
| static [DateTimeOffset](./) [get_Now](./get_now/)() | يحصل على [DateTimeOffset](./) الذي تم تعيين تاريخ ووقته إلى الوقت المحلي الحالي وتم تعيين إزاحته إلى إزاحة الوقت المحلي. |
| constexpr [TimeSpan](../timespan/) [get_Offset](./get_offset/)() const | يحصل على الإزاحة من التوقيت العالمي المتناغم (UTC). |
| constexpr int [get_Second](./get_second/)() const | يحصل على عنصر الثانية من الكائن الحالي. |
| **int64_t** [get_Ticks](./get_ticks/)() const | يحصل على عدد النقرات في الكائن الحالي. |
| [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | يحصل على وقت اليوم من الكائن الحالي. |
| [DateTime](../datetime/) [get_UtcDateTime](./get_utcdatetime/)() const | يحصل على قيمة [DateTime](../datetime/) التي تمثل تاريخ ووقت UTC. |
| static [DateTimeOffset](./) [get_UtcNow](./get_utcnow/)() | يحصل على [DateTimeOffset](./) الذي تم تعيين تاريخ ووقته إلى وقت UTC الحالي وإزاحته هي [TimeSpan::Zero](../timespan/zero/). |
| **int64_t** [get_UtcTicks](./get_utcticks/)() const | يحصل على عدد النقرات في الكائن الحالي بوقت UTC. |
| int [get_Year](./get_year/)() const | يحصل على عنصر السنة من الكائن الحالي. |
| int [GetHashCode](./gethashcode/)() const | يحصل على رمز التجزئة لكائن [DateTimeOffset](./) الحالي. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| **bool** [operator!=](./operator_not_equal/)(const [DateTimeOffset](./)\&) const | يحدد ما إذا كان الكائن الحالي والكائن [DateTimeOffset](./) المحدد يمثلان قيم تاريخ ووقت متميزة. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTimeOffset](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | يعيد نسخة جديدة من فئة [DateTimeOffset](./) تمثل قيمة التاريخ والوقت التي هي مجموع القيمة التي يمثلها الكائن الحالي والفاصل الزمني المحدد. |
| [DateTimeOffset](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | يعيد نسخة جديدة من فئة [DateTimeOffset](./) تمثل قيمة التاريخ والوقت الناتجة عن طرح الفاصل الزمني المحدد من القيمة التي يمثلها الكائن الحالي. |
| [TimeSpan](../timespan/) [operator-](./operator_minus/)(const [DateTimeOffset](./)\&) const | يعيد نسخة من فئة [TimeSpan](../timespan/) تمثل الفاصل الزمني بين قيم التاريخ والوقت التي يمثلها الكائن الحالي والكائن المحدد. |
| **bool** [operator<](./operator_less/)(const [DateTimeOffset](./)\&) const | يحدد ما إذا كان الكائن الحالي يمثل قيمة التاريخ والوقت التي هي أسبق من القيمة التي يمثلها الكائن [DateTimeOffset](./) المحدد. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| **bool** [operator<=](./operator_less_equal/)(const [DateTimeOffset](./)\&) const | يحدد ما إذا كان الكائن الحالي يمثل قيمة التاريخ والوقت التي هي أسبق أو مساوية للقيمة التي يمثلها الكائن [DateTimeOffset](./) المحدد. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| **bool** [operator==](./operator_equal_equal/)(const [DateTimeOffset](./)\&) const | يحدد ما إذا كان الكائن الحالي والكائن [DateTimeOffset](./) المحدد يمثلان نفس قيمة التاريخ والوقت. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| **bool** [operator>](./operator_greater/)(const [DateTimeOffset](./)\&) const | يحدد ما إذا كان الكائن الحالي يمثل قيمة التاريخ والوقت التي هي لاحقة للقيمة التي يمثلها الكائن [DateTimeOffset](./) المحدد. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| **bool** [operator>=](./operator_greater_equal/)(const [DateTimeOffset](./)\&) const | يحدد ما إذا كان الكائن الحالي يمثل قيمة التاريخ والوقت التي هي لاحقة أو مساوية للقيمة التي يمثلها الكائن [DateTimeOffset](./) المحدد. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&) | يحول السلسلة المحددة إلى ما يعادل [DateTimeOffset](./). |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | يحول السلسلة المحددة إلى كائن [DateTimeOffset](./) باستخدام موفر الصيغة المحدد ونمط التنسيق. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | يحول السلسلة المحددة إلى كائن [DateTimeOffset](./) باستخدام الصيغة المحددة، موفر الصيغة ونمط التنسيق. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | يحول السلسلة المحددة إلى كائن [DateTimeOffset](./) باستخدام الصيغ المحددة، موفر الصيغة ونمط التنسيق. |
| [DateTimeOffset](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | يطرح فترة زمنية محددة من الكائن الحالي. |
| [TimeSpan](../timespan/) [Subtract](./subtract/)(const [DateTimeOffset](./)\&) const | يطرح قيمة [DateTimeOffset](./) محددة من الكائن الحالي. |
| **int64_t** [ToFileTime](./tofiletime/)() const | يحول الكائن الحالي إلى وقت ملف [Windows](../../system.windows/). |
| [DateTimeOffset](./) [ToLocalTime](./tolocaltime/)() const | يحول الكائن الحالي إلى كائن يمثل الوقت المحلي. |
| [DateTimeOffset](./) [ToOffset](./tooffset/)([TimeSpan](../timespan/)) const | يستبدل إزاحة الكائن الحالي بالإزاحة المحددة. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | يحول الكائن الحالي إلى سلسلة باستخدام الصيغة المحددة وموفر الصيغة. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | يحول الكائن الحالي إلى سلسلة باستخدام موفر الصيغة المحدد. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | يحول الكائن الحالي إلى سلسلة باستخدام الصيغة المحددة. |
| [String](../string/) [ToString](./tostring/)() const | يحول الكائن الحالي إلى سلسلة. |
| [DateTimeOffset](./) [ToUniversalTime](./touniversaltime/)() const | يحول الكائن الحالي إلى كائن يمثل وقت UTC. |
| **int64_t** [ToUnixTimeMilliseconds](./tounixtimemilliseconds/)() const | يحصل على عدد المللي ثوانٍ منذ بداية عهد يونكس. |
| **int64_t** [ToUnixTimeSeconds](./tounixtimeseconds/)() const | يحصل على عدد الثواني منذ بداية عهد يونكس. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTimeOffset](./)\&) | يحاول تحويل السلسلة المحددة إلى كائن [DateTimeOffset](./). |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | يحاول تحويل السلسلة المحددة إلى كائن [DateTimeOffset](./) باستخدام موفر الصيغة والنمط المحدد. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | يحاول تحويل السلسلة المحددة إلى كائن [DateTimeOffset](./) باستخدام الصيغ المحددة، موفر الصيغة والنمط. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | يحاول تحويل السلسلة المحددة إلى كائن [DateTimeOffset](./) باستخدام الصيغة، موفر الصيغة والنمط المحدد. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | يعيد كائن [TypeInfo](../typeinfo/) يمثل بنية [TimeSpan](../timespan/). |

## الحقول

| الحقل | الوصف |
| --- | --- |
| static constexpr [MaxOffset](./maxoffset/) | يحصل على أقصى إزاحة بالنقرات. |
| static [MaxValue](./maxvalue/) | يحصل على أكبر قيمة [DateTimeOffset](./). |
| static constexpr [MinOffset](./minoffset/) | يحصل على أدنى إزاحة بالنقرات. |
| static [MinValue](./minvalue/) | يحصل على أقدم قيمة [DateTimeOffset](./). |
| static [UnixEpoch](./unixepoch/) | يحصل على بداية عهد يونكس. |

## انظر أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)