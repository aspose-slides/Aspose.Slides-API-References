---
title: HijriCalendar
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "تقويم هجري. يجب تخصيص كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تُنشئ أبدًا نسخة من هذا النوع على المكدس أو باستخدام معامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل و/أو أخطاء تأكيد. دائمًا غلف هذه الفئة بمؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 157
url: /ar/system.globalization/hijricalendar/
---
## فئة HijriCalendar

التقويم الهجري. يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تُنشئ أبدًا نسخة من هذا النوع على المكدس أو باستخدام عامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل و/أو أخطاء تأكيد. دائمًا غلف هذه الفئة بمؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class HijriCalendar : public System::Globalization::Calendar
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | يضيف أيامًا إلى نقطة الزمن. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | يضيف ساعات إلى نقطة الزمن. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | يضيف مليثوانٍ إلى نقطة الزمن. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | يضيف دقائق إلى نقطة الزمن. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | يضيف شهورًا إلى نقطة الزمن. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | يضيف ثوانٍ إلى نقطة الزمن. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | يضيف أسابيع إلى نقطة الزمن. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | يضيف سنوات إلى نقطة الزمن. |
| [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | معلومات RTTI. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | ينشئ نسخة من الكائن الحالي ويعيد مؤشرًا مشتركًا إليه. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaN قيمتين متساويتين بالرغم من أن IEC 60559:1989 تُعرّف NaN غير مساوية لأي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaN قيمتين متساويتين بالرغم من أن IEC 60559:1989 تُعرّف NaN غير مساوية لأي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للأغراض الداخلية فقط. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | يحصل على نوع الخوارزمية. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | يحصل على فهرس العصر الحالي. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | يحصل على قيمة العصر الحالي. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | يحصل على قائمة العصور الموجودة في التقويم. |
| int [get_HijriAdjustment](./get_hijriadjustment/)() const | يحصل على تعديل هجري. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | يتحقق مما إذا كان التقويم للقراءة فقط. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | أقصى نقطة زمنية يدعمها التقويم. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | أدنى نقطة زمنية يدعمها التقويم. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | يحصل على آخر سنة يمكن تمثيلها برقم من رقمين. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | يحصل على يوم الشهر للنقطة الزمنية المحددة. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | يحصل على يوم الأسبوع للنقطة الزمنية المحددة. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | يحصل على يوم السنة للنقطة الزمنية المحددة. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | يحصل على عدد الأيام في شهر محدد. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int, int) const | يحصل على عدد الأيام في شهر محدد. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | يحصل على عدد الأيام في سنة محددة. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | يحصل على عدد الأيام في سنة محددة. |
| virtual int [GetEra](../calendar/getera/)([DateTime](../../system/datetime/)) const | يحصل على العصر للنقطة الزمنية المحددة. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | يحصل على الساعات للنقطة الزمنية المحددة. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | يحصل على الشهر الكبيس للسنة المحددة. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | معلومات RTTI. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | معلومات RTTI. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | يحصل على مليثوانٍ للنقطة الزمنية المحددة. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | يحصل على دقائق للنقطة الزمنية المحددة. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | يحصل على شهر للنقطة الزمنية المحددة. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int) const | يحصل على عدد الشهور في السنة المحددة. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int, int) const | يحصل على عدد الشهور في السنة المحددة. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | يحصل على ثوانٍ للنقطة الزمنية المحددة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل نداء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | يحصل على أسبوع السنة للنقطة الزمنية المحددة. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | يحصل على السنة للنقطة الزمنية المحددة. |
| [HijriCalendar](./hijricalendar/)() | منشئ. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. تماثل عامل C# 'is'. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | يتحقق مما إذا كان اليوم كبيسًا. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | يتحقق مما إذا كان اليوم كبيسًا. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | يتحقق مما إذا كان اليوم كبيسًا. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | يتحقق مما إذا كان الشهر كبيسًا. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | يتحقق مما إذا كان الشهر كبيسًا. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | يتحقق مما إذا كان الشهر كبيسًا. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | يتحقق مما إذا كانت السنة كبيسة. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | يتحقق مما إذا كانت السنة كبيسة. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | يتحقق مما إذا كانت السنة كبيسة. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | يتحقق من قيم السنة، الشهر، اليوم والعصر. |
| void [Lock](../../system/object/lock/)() | ينفذ عملية القفل lock() في C#. استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويمكّن بناء نسخ الفئات المشتقة. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل التعيين. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويمكّن بناء نسخ الفئات المشتقة. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | يحصل على نسخة للقراءة فقط من التقويم. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي بـ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_HijriAdjustment](./set_hijriadjustment/)(int) | يضبط تعديل هجري. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | يضبط آخر سنة يمكن تمثيلها برقم من رقمين. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط وسيط القالب nth إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | يبني كائن [DateTime](../../system/datetime/) من المكونات. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | يبني كائن [DateTime](../../system/datetime/) من المكونات. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | يحوّل السنة إلى سنة من أربعة أرقام باستخدام خاصية TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ عملية إلغاء القفل lock() في C#. استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| virtual [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## الحقول

| الحقل | الوصف |
| --- | --- |
| static constexpr [HijriEra](./hijriera/) | العصر الهجري الحالي. |

## انظر أيضًا

* الفئة [Calendar](../calendar/)
* المساحة الاسمية [System::Globalization](../)
* المكتبة [Aspose.Slides](../../)