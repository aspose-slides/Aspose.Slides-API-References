---
title: DateTimeFormatInfo
second_title: "مرجع API لـ Aspose.Slides للغة C++"
description: "مجموعة من معايير تنسيق التاريخ والوقت. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام عامل new، حيث سيسبّب ذلك أخطاء وقت التشغيل أو أعطال التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 66
url: /ar/system.globalization/datetimeformatinfo/
---
## DateTimeFormatInfo فئة

مجموعة من معايير تنسيق التاريخ والوقت. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام عامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أعطال التأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class DateTimeFormatInfo : public virtual System::Object,
                           public System::IFormatProvider,
                           public System::ICloneable
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | ينسخ معلومات التنسيق. |
| [DateTimeFormatInfo](./datetimeformatinfo/)() | منشئ افتراضي، ينشئ معلومات تنسيق ثابتة. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaNانان متساويتين رغم أن IEC 60559:1989 تنص على أن NaN لا تساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaNانان متساويتين رغم أن IEC 60559:1989 تنص على أن NaN لا تساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedDayNames](./get_abbreviateddaynames/)() const | يحصل على أسماء أيام مختصرة. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedMonthGenitiveNames](./get_abbreviatedmonthgenitivenames/)() const | يحصل على أسماء الشهور المختصرة بصيغة المضاف إليه. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedMonthNames](./get_abbreviatedmonthnames/)() const | يحصل على أسماء الشهور المختصرة. |
| [String](../../system/string/) [get_AMDesignator](./get_amdesignator/)() const | يحصل على محدد AM. |
| [SharedPtr](../../system/sharedptr/)\<[Calendar](../calendar/)\> [get_Calendar](./get_calendar/)() const | يحصل على التقويم المرتبط بالمُنسق. |
| [CalendarWeekRule](../calendarweekrule/) [get_CalendarWeekRule](./get_calendarweekrule/)() const | يحصل على قاعدة أسبوع التقويم المرتبطة بالمُنسق. |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | يحصل على مُنسق التاريخ والوقت للخيط الحالي. |
| [String](../../system/string/) [get_DateSeparator](./get_dateseparator/)() const | يحصل على فاصل التاريخ. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_DayNames](./get_daynames/)() const | يحصل على أسماء الأيام. |
| [DayOfWeek](../../system/dayofweek/) [get_FirstDayOfWeek](./get_firstdayofweek/)() const | يحصل على أول يوم في الأسبوع. |
| [String](../../system/string/) [get_FullDateTimePattern](./get_fulldatetimepattern/)() const | يحصل على نمط التاريخ والوقت الكامل. |
| static const [DateTimeFormatInfoPtr](../datetimeformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | يحصل على مُنسق التاريخ والوقت الثابت. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | يتحقق مما إذا كان المُنسق للقراءة فقط. |
| [String](../../system/string/) [get_LongDatePattern](./get_longdatepattern/)() const | يحصل على نمط التاريخ الطويل. |
| [String](../../system/string/) [get_LongTimePattern](./get_longtimepattern/)() const | يحصل على نمط الوقت الطويل. |
| [String](../../system/string/) [get_MonthDayPattern](./get_monthdaypattern/)() const | يحصل على نمط يوم الشهر. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_MonthGenitiveNames](./get_monthgenitivenames/)() const | يحصل على أسماء الشهور بصيغة المضاف إليه. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_MonthNames](./get_monthnames/)() const | يحصل على أسماء الشهور. |
| [String](../../system/string/) [get_NativeCalendarName](./get_nativecalendarname/)() const | يحصل على اسم التقويم الأصلي إذا كان متاحًا. |
| [String](../../system/string/) [get_PMDesignator](./get_pmdesignator/)() const | يحصل على محدد PM. |
| [String](../../system/string/) [get_RFC1123Pattern](./get_rfc1123pattern/)() const | يحصل على نمط RFC1123. |
| [String](../../system/string/) [get_ShortDatePattern](./get_shortdatepattern/)() const | يحصل على نمط التاريخ المختصر. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_ShortestDayNames](./get_shortestdaynames/)() const | يحصل على أقصر أسماء أيام ممكنة. |
| [String](../../system/string/) [get_ShortTimePattern](./get_shorttimepattern/)() const | يحصل على نمط الوقت المختصر. |
| [String](../../system/string/) [get_SortableDateTimePattern](./get_sortabledatetimepattern/)() const | يحصل على نمط التاريخ والوقت القابل للترتيب. |
| [String](../../system/string/) [get_TimeSeparator](./get_timeseparator/)() const | يحصل على فاصل الوقت. |
| [String](../../system/string/) [get_UniversalSortableDateTimePattern](./get_universalsortabledatetimepattern/)() const | يحصل على نمط التاريخ والوقت القابل للترتيب العام. |
| [String](../../system/string/) [get_YearMonthPattern](./get_yearmonthpattern/)() const | يحصل على نمط السنة والشهر. |
| [String](../../system/string/) [GetAbbreviatedDayName](./getabbreviateddayname/)([DayOfWeek](../../system/dayofweek/)) const | يحصل على اسم اليوم المختصر للأسبوع. |
| [String](../../system/string/) [GetAbbreviatedEraName](./getabbreviatederaname/)(int) const | يحصل على اسم الحقبة المختصر. |
| [String](../../system/string/) [GetAbbreviatedMonthName](./getabbreviatedmonthname/)(int) const | يحصل على اسم الشهر المختصر. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetAllDateTimePatterns](./getalldatetimepatterns/)() const | يحصل على جميع الأنماط التي يمكن تنسيق قيم التاريخ والوقت بها. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetAllDateTimePatterns](./getalldatetimepatterns/)(char16_t) const | يحصل على جميع الأنماط التي يمكن تنسيق قيم التاريخ والوقت بها باستخدام سلسلة تنسيق محددة. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| [String](../../system/string/) [GetDayName](./getdayname/)([DayOfWeek](../../system/dayofweek/)) const | يحصل على اسم اليوم في الأسبوع. |
| int [GetEra](./getera/)(const [String](../../system/string/)\&) const | يحصل على الحقبة بالاسم. |
| [String](../../system/string/) [GetEraName](./geteraname/)(int) const | يحصل على اسم الحقبة. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | يحصل على المُنسق من النوع المحدد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | يحصل على المُنسق المرتبط بموفر التنسيق. |
| [String](../../system/string/) [GetLeapYearMonthName](./getleapyearmonthname/)(int) const | يحصل على اسم شهر السنة الكبيسة. |
| [String](../../system/string/) [GetMonthGenitiveName](./getmonthgenitivename/)(int) const | يحصل على اسم الشهر بصيغة المضاف إليه. |
| [String](../../system/string/) [GetMonthName](./getmonthname/)(int) const | يحصل على اسم الشهر. |
| [String](../../system/string/) [GetShortestDayName](./getshortestdayname/)([DayOfWeek](../../system/dayofweek/)) const | يحصل على أقصر اسم لليوم المحدد من الأسبوع. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق إذا كان الكائن يمثل مثيلًا للنوع الموصوف بـ targetType. مماثل لمشغّل C# 'is'. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويمكّن إنشاء نسخ من الفئات الفرعية. |
| [DateTimeFormatInfo](./)\& [operator=](./operator_equal/)(const [DateTimeFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويمكّن إنشاء نسخ من الفئات الفرعية. |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [ReadOnly](./readonly/)(const [DateTimeFormatInfoPtr](../datetimeformatinfoptr/)\&) | يحصل على نسخة للمُنسق للقراءة فقط. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالإشارة. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالإشارة. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن بالمرجع كائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد الإشارة المشتركة بالقيمة المحددة. |
| void [set_AbbreviatedDayNames](./set_abbreviateddaynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | يضبط أسماء الأيام المختصرة. |
| void [set_AbbreviatedMonthGenitiveNames](./set_abbreviatedmonthgenitivenames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | يضبط أسماء الشهور المختصرة بصيغة المضاف إليه. |
| void [set_AbbreviatedMonthNames](./set_abbreviatedmonthnames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | يضبط أسماء الشهور المختصرة. |
| void [set_AMDesignator](./set_amdesignator/)(const [String](../../system/string/)\&) | يضبط محدد AM. |
| void [set_Calendar](./set_calendar/)(const [SharedPtr](../../system/sharedptr/)\<[Calendar](../calendar/)\>\&) | يضبط التقويم المرتبط بالمُنسق. |
| void [set_CalendarWeekRule](./set_calendarweekrule/)([CalendarWeekRule](../calendarweekrule/)) | يضبط قاعدة أسبوع التقويم المرتبطة بالمُنسق. |
| void [set_DateSeparator](./set_dateseparator/)(const [String](../../system/string/)\&) | يضبط فاصل التاريخ. |
| void [set_DayNames](./set_daynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | يضبط أسماء الأيام. |
| void [set_FirstDayOfWeek](./set_firstdayofweek/)([DayOfWeek](../../system/dayofweek/)) | يضبط أول يوم في الأسبوع. |
| void [set_FullDateTimePattern](./set_fulldatetimepattern/)(const [String](../../system/string/)\&) | يضبط نمط التاريخ والوقت الكامل. |
| void [set_LongDatePattern](./set_longdatepattern/)(const [String](../../system/string/)\&) | يضبط نمط التاريخ الطويل. |
| void [set_LongTimePattern](./set_longtimepattern/)(const [String](../../system/string/)\&) | يضبط نمط الوقت الطويل. |
| void [set_MonthDayPattern](./set_monthdaypattern/)(const [String](../../system/string/)\&) | يضبط نمط يوم الشهر. |
| void [set_MonthGenitiveNames](./set_monthgenitivenames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | يضبط أسماء الشهور بصيغة المضاف إليه. |
| void [set_MonthNames](./set_monthnames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | يضبط أسماء الشهور. |
| void [set_PMDesignator](./set_pmdesignator/)(const [String](../../system/string/)\&) | يضبط محدد PM. |
| void [set_ShortDatePattern](./set_shortdatepattern/)(const [String](../../system/string/)\&) | يضبط نمط التاريخ المختصر. |
| void [set_ShortestDayNames](./set_shortestdaynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | يضبط أقصر أسماء أيام ممكنة. |
| void [set_ShortTimePattern](./set_shorttimepattern/)(const [String](../../system/string/)\&) | يضبط نمط الوقت المختصر. |
| void [set_TimeSeparator](./set_timeseparator/)(const [String](../../system/string/)\&) | يضبط فاصل الوقت. |
| void [set_YearMonthPattern](./set_yearmonthpattern/)(const [String](../../system/string/)\&) | يضبط نمط السنة والشهر. |
| void [SetAllDateTimePatterns](./setalldatetimepatterns/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, char16_t) | يضبط الأنماط للتنسيق المحدد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النمطي الـ n't كإشارة ضعيفة (بدلاً من المشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضعية ضعيفة. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل عبارة C# lock(). استدعِ مباشرةً أو استخدم كائن المراقبة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* فئة [Object](../../system/object/)
* فئة [IFormatProvider](../../system/iformatprovider/)
* فئة [ICloneable](../../system/icloneable/)
* نطاق [System::Globalization](../)
* مكتبة [Aspose.Slides](../../)