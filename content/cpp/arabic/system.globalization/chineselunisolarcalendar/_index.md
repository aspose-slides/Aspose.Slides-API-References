---
title: ChineseLunisolarCalendar
second_title: مرجع API Aspose.Slides للـ C++
description: "تقويم صيني قمري شمسي. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقم أبدًا بإنشاء نسخة من هذا النوع على المكدس أو باستخدام operator new، حيث سيؤدي ذلك إلى أخطاء وقت تشغيل و/أو أخطاء في عبارات التحقق. دائمًا قم بلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 27
url: /ar/system.globalization/chineselunisolarcalendar/
---
## ChineseLunisolarCalendar فئة

تقويم صيني قمري شمسي. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم أبدًا بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيؤدي إلى أخطاء وقت تشغيل أو أخطاء في عبارات التحقق. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class ChineseLunisolarCalendar : public System::Globalization::EastAsianLunisolarCalendar
```

## طرق

| طريقة | الوصف |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | يضيف أيامًا إلى نقطة الزمن. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | يضيف ساعات إلى نقطة الزمن. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | يضيف مللي ثانية إلى نقطة الزمن. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | يضيف دقائق إلى نقطة الزمن. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | يضيف أشهرًا إلى نقطة الزمن. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | يضيف ثوانٍ إلى نقطة الزمن. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | يضيف أسابيع إلى نقطة الزمن. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | يضيف سنوات إلى نقطة الزمن. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | معلومات RTTI. |
|  [ChineseLunisolarCalendar](./chineselunisolarcalendar/)() | منشئ افتراضي. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | ينشئ نسخة من الكائن الحالي ويعيد مؤشرًا مشتركًا إليها. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالة C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي على نمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي على نمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | تحاكي مقارنة النقطة العائمة على نمط C# حيث تُعتبر NaNين متساويتين رغم أنه وفقًا لـ IEC 60559:1989 فإن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | تحاكي مقارنة النقطة العائمة على نمط C# حيث تُعتبر NaNين متساويتين رغم أنه وفقًا لـ IEC 60559:1989 فإن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](../eastasianlunisolarcalendar/get_algorithmtype/)() const override | معلومات RTTI. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | يحصل على فهرس العصر الحالي. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | يحصل على قيمة العصر الحالي. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | يحصل على قائمة العصور الموجودة في التقويم. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | يفحص إذا كان التقويم للقراءة فقط. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | أقصى نقطة زمنية يدعمها التقويم. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | أدنى نقطة زمنية يدعمها التقويم. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | يحصل على آخر سنة يمكن تمثيلها برقمين. |
| int [GetCelestialStem](../eastasianlunisolarcalendar/getcelestialstem/)(int) const | يحصل على الجذر السماوي. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل عداد الإشارة المرتبط بالكائن. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | يحصل على يوم الشهر للنقطة الزمنية المحددة. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | يحصل على يوم الأسبوع للنقطة الزمنية المحددة. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | يحصل على يوم السنة للنقطة الزمنية المحددة. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | يحصل على عدد الأيام في شهر معين. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | يحصل على عدد الأيام في شهر معين. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | يحصل على عدد الأيام في شهر معين. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | يحصل على عدد الأيام في سنة معينة. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | يحصل على عدد الأيام في سنة معينة. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | يحصل على العصر للنقطة الزمنية المحددة. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | يحصل على الساعات للنقطة الزمنية المحددة. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | يحصل على الشهر الكبيس للسنة المحددة. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | يحصل على الشهر الكبيس للسنة المحددة. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | يحصل على الشهر الكبيس للسنة المحددة. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | يحصل على المللي ثانية للنقطة الزمنية المحددة. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | يحصل على الدقائق للنقطة الزمنية المحددة. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | يحصل على الشهر للنقطة الزمنية المحددة. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | يحصل على عدد الأشهر في السنة المحددة. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | معلومات RTTI. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | معلومات RTTI. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | يحصل على الثواني للنقطة الزمنية المحددة. |
| virtual int [GetSexagenaryYear](../eastasianlunisolarcalendar/getsexagenaryyear/)([DateTime](../../system/datetime/)) const | يحصل على السنة في الدورة الستينيتية. |
| int [GetTerrestrialBranch](../eastasianlunisolarcalendar/getterrestrialbranch/)(int) const | يحصل على الفرع الأرضي. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | يحصل على أسبوع السنة للنقطة الزمنية المحددة. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | يحصل على السنة للنقطة الزمنية المحددة. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير معامل C# 'is'. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | يفحص إذا كان اليوم كبيسًا. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | يفحص إذا كان اليوم كبيسًا. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | يفحص إذا كان اليوم كبيسًا. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | يفحص إذا كان الشهر كبيسًا. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | يفحص إذا كان الشهر كبيسًا. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | يفحص إذا كان الشهر كبيسًا. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | يفحص إذا كانت السنة كبيسة. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | يفحص إذا كانت السنة كبيسة. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | يفحص إذا كانت السنة كبيسة. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | يفحص قيم السنة، الشهر، اليوم والعصر. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعها مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ كل هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | مشغل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | يحصل على نسخة للقراءة فقط من التقويم. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع القيم مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | يضبط آخر سنة يمكن تمثيلها برقمين. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النمطي رقم n إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | يبني كائن [DateTime](../../system/datetime/) من المكونات. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | يبني كائن [DateTime](../../system/datetime/) من المكونات. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | يحوّل السنة إلى سنة من أربعة أرقام باستخدام الخاصية TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك قفل عبارة C# lock(). استدعها مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر كل هياكل البيانات الداخلية. |

## حقول

| حقل | الوصف |
| --- | --- |
| static constexpr [ChineseEra](./chineseera/) | العصر الصيني الحالي. |

## أنظر أيضًا

* فئة [EastAsianLunisolarCalendar](../eastasianlunisolarcalendar/)
* نطاق [System::Globalization](../)
* مكتبة [Aspose.Slides](../../)