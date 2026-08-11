---
title: TaiwanCalendar
second_title: مرجع API Aspose.Slides للغة C++
description: "تقويم تايوان. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject() . لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل أو أخطاء التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 326
url: /ar/system.globalization/taiwancalendar/
---
## فئة TaiwanCalendar

تقويم تايوان. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل أو أخطاء التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class TaiwanCalendar : public System::Globalization::Calendar
```
## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | يضيف أيامًا إلى نقطة الوقت. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | يضيف ساعات إلى نقطة الوقت. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | يضيف ميلي ثانية إلى نقطة الوقت. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | يضيف دقائق إلى نقطة الوقت. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | يضيف أشهرًا إلى نقطة الوقت. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | يضيف ثوانٍ إلى نقطة الوقت. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | يضيف أسابيع إلى نقطة الوقت. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | يضيف سنوات إلى نقطة الوقت. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | معلومات RTTI. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | ينشئ نسخة من الكائن الحالي ويعيد مؤشرًا مشتركًا إليه. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة نقطية عائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا تساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة نقطية عائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا تساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | يحصل على نوع الخوارزمية. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | يحصل على فهرس العصر الحالي. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | يحصل على قيمة العصر الحالي. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | يحصل على قائمة بالعصور الموجودة في التقويم. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | يتحقق مما إذا كان التقويم للقراءة فقط. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | أقصى نقطة زمنية يدعمها التقويم. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | أدنى نقطة زمنية يدعمها التقويم. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | يحصل على آخر سنة يمكن تمثيلها بأرقام مزدوجة. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const override | يحصل على يوم الشهر للنقطة الزمنية المحددة. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | يحصل على يوم الأسبوع للنقطة الزمنية المحددة. |
| int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const override | يحصل على يوم السنة للنقطة الزمنية المحددة. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | يحصل على عدد الأيام في شهر معين. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | يحصل على عدد الأيام في شهر معين. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | يحصل على عدد الأيام في شهر معين. |
| int [GetDaysInYear](./getdaysinyear/)(int, int) const override | يحصل على عدد الأيام في سنة معينة. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | يحصل على عدد الأيام في سنة معينة. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | يحصل على عدد الأيام في سنة معينة. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | يحصل على العصر للنقطة الزمنية المحددة. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تناظر طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | يحصل على الساعات للنقطة الزمنية المحددة. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | يحصل على الشهر الكبيس للسنة المحددة. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | يحصل على الشهر الكبيس للسنة المحددة. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | يحصل على الشهر الكبيس للسنة المحددة. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | يحصل على ميلي ثانية للنقطة الزمنية المحددة. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | يحصل على دقائق للنقطة الزمنية المحددة. |
| int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const override | يحصل على شهر للنقطة الزمنية المحددة. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | يحصل على عدد الأشهر في السنة المحددة. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | معلومات RTTI. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | معلومات RTTI. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | يحصل على ثوانٍ للنقطة الزمنية المحددة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | يحصل على أسبوع السنة للنقطة الزمنية المحددة. |
| int [GetYear](./getyear/)([DateTime](../../system/datetime/)) const override | يحصل على السنة للنقطة الزمنية المحددة. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. تناظر معامل C# 'is'. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | يتحقق مما إذا كان اليوم كبيسًا. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | يتحقق مما إذا كان اليوم كبيسًا. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | يتحقق مما إذا كان اليوم كبيسًا. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | يتحقق مما إذا كان الشهر كبيسًا. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | يتحقق مما إذا كان الشهر كبيسًا. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | يتحقق مما إذا كان الشهر كبيسًا. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | يتحقق مما إذا كانت السنة كبيسة. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | يتحقق مما إذا كانت السنة كبيسة. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | يتحقق مما إذا كانت السنة كبيسة. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | يتحقق من قيم السنة والشهر واليوم والعصر. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيء جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، بل يهيء كائنًا جديدًا ويسمح بإنشاء نسخ للأنماط الفرعية. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيء كائنًا جديدًا ويسمح بإنشاء نسخ للأنماط الفرعية. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | يحصل على نسخة قراءة فقط من التقويم. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | يضبط آخر سنة يمكن تمثيلها بأرقام مزدوجة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب n'th ليكون مؤشرًا ضعيفًا (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
|  [TaiwanCalendar](./taiwancalendar/)() | منشئ. |
| [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | يبني كائن [DateTime](../../system/datetime/) من المكونات. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | يبني كائن [DateTime](../../system/datetime/) من المكونات. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | يبني كائن [DateTime](../../system/datetime/) من المكونات. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | يحول السنة إلى سنة بأربع أرقام باستخدام خاصية TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تناظر طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## انظر أيضاً

* فئة [Calendar](../calendar/)
* مساحة الاسم [System::Globalization](../)
* مكتبة [Aspose.Slides](../../)