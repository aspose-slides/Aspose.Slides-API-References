---
title: EastAsianLunisolarCalendar
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "تقويم القمر الشمسي شرق آسيا. يجب تخصيص كائنات هذه الفئة فقط باستخدام دالة System::MakeObject(). لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، لأنه سيتسبب في أخطاء وقت التشغيل و/أو أخطاء التأكيد. دائمًا قم بلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 105
url: /ar/system.globalization/eastasianlunisolarcalendar/
---
## EastAsianLunisolarCalendar فئة

تقويم صيني-آسيوي قمري شمسي. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تُنشئ أبداً نسخة من هذا النوع على المكدس أو باستخدام عامل new، حيث سيتسبب ذلك في أخطاء وقت تشغيل و/أو أخطاء تأكيد. قم دائماً بلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class EastAsianLunisolarCalendar : public System::Globalization::Calendar
```

## الأساليب

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
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](../../system/icloneable/clone/)() | ينشئ نسخة من الكائن الحالي ويعيد مؤشرًا مشتركًا لها. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة الأعداد العائمة بأسلوب C# حيث تعتبر NaNين متساويتين رغم أنه وفقًا للمعيار IEC 60559:1989 فإن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة الأعداد العائمة بأسلوب C# حيث تعتبر NaNين متساويتين رغم أنه وفقًا للمعيار IEC 60559:1989 فإن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | معلومات RTTI. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | يحصل على فهرس العصر الحالي. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | يحصل على قيمة العصر الحالي. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](../calendar/get_eras/)() const | يحصل على قائمة بالعصور الموجودة في التقويم. |
| virtual [Details::CalendarId](../../system.globalization.details/calendarid/) [get_ID](../calendar/get_id/)() const | يحصل على معرف التقويم. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | يتحقق مما إذا كان التقويم للقراءة فقط. |
| virtual [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](../calendar/get_maxsupporteddatetime/)() const | أقصى نقطة زمنية يدعمها التقويم. |
| virtual [DateTime](../../system/datetime/) [get_MinSupportedDateTime](../calendar/get_minsupporteddatetime/)() const | أدنى نقطة زمنية يدعمها التقويم. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | يحصل على آخر سنة يمكن تمثيلها برقم من رقمين. |
| int [GetCelestialStem](./getcelestialstem/)(int) const | يحصل على السمت السماوي. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | يحصل على يوم الشهر للنقطة الزمنية المحددة. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | يحصل على يوم الأسبوع للنقطة الزمنية المحددة. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | يحصل على يوم السنة للنقطة الزمنية المحددة. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | يحصل على عدد الأيام في الشهر المحدد. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int, int) const | يحصل على عدد الأيام في الشهر المحدد. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | يحصل على عدد الأيام في السنة المحددة. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | يحصل على عدد الأيام في السنة المحددة. |
| virtual int [GetEra](../calendar/getera/)([DateTime](../../system/datetime/)) const | يحصل على العصر للنقطة الزمنية المحددة. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تناظر طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | يحصل على الساعات للنقطة الزمنية المحددة. |
| virtual int [GetLeapMonth](../calendar/getleapmonth/)(int) const | يحصل على الشهر الكبيس للسنة المحددة. |
| virtual int [GetLeapMonth](../calendar/getleapmonth/)(int, int) const | يحصل على الشهر الكبيس للسنة المحددة. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | يحصل على الميلي ثانية للنقطة الزمنية المحددة. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | يحصل على الدقائق للنقطة الزمنية المحددة. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | يحصل على الشهر للنقطة الزمنية المحددة. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int) const | يحصل على عدد الأشهر في السنة المحددة. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int, int) const | يحصل على عدد الأشهر في السنة المحددة. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | يحصل على الثواني للنقطة الزمنية المحددة. |
| virtual int [GetSexagenaryYear](./getsexagenaryyear/)([DateTime](../../system/datetime/)) const | يحصل على السنة في الدورة الستينية. |
| int [GetTerrestrialBranch](./getterrestrialbranch/)(int) const | يحصل على الفرع الأرضي. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | يحصل على أسبوع السنة للنقطة الزمنية المحددة. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | يحصل على السنة للنقطة الزمنية المحددة. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق ما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. تناظر عامل C# 'is'. |
| virtual **bool** [IsLeapDay](../calendar/isleapday/)(int, int, int) const | يتحقق ما إذا كان اليوم كبيسًا. |
| virtual **bool** [IsLeapDay](../calendar/isleapday/)(int, int, int, int) const | يتحقق ما إذا كان اليوم كبيسًا. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int) const | يتحقق ما إذا كان الشهر كبيسًا. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int, int) const | يتحقق ما إذا كان الشهر كبيسًا. |
| virtual **bool** [IsLeapYear](../calendar/isleapyear/)(int) const | يتحقق ما إذا كانت السنة كبيسة. |
| virtual **bool** [IsLeapYear](../calendar/isleapyear/)(int, int) const | يتحقق ما إذا كانت السنة كبيسة. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | يتحقق من قيم السنة والشهر واليوم والعصر. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويتيح إنشاء نسخ ثانوية للصفوف المشتقة. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويتيح إنشاء نسخ ثانوية للصفوف المشتقة. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | يحصل على نسخة للقراءة فقط من التقويم. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | يضبط آخر سنة يمكن تمثيلها برقم من رقمين. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط المعامل القالبي n إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلًا من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلًا من ذلك. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | يبني كائن [DateTime](../../system/datetime/) من المكونات. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | يبني كائن [DateTime](../../system/datetime/) من المكونات. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | يحول السنة إلى سنة مكوّنة من 4 أرقام باستخدام خاصية TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تناظر طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلًا من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلًا من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |
## راجع أيضًا

* الفئة [Calendar](../calendar/)
* النطاق [System::Globalization](../)
* المكتبة [Aspose.Slides](../../)