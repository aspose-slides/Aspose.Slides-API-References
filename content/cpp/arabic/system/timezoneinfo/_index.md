---
title: TimeZoneInfo
second_title: Aspose.Slides للـ C++ مرجع API
description: "يمثل معلومات تصف منطقة زمنية معينة. يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيتسبب ذلك في أخطاء وقت تشغيل أو أخطاء تأكيد. دائمًا غلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 1340
url: /ar/system/timezoneinfo/
---
## فئة TimeZoneInfo

يمثل معلومات تصف منطقة زمنية معينة. يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../makeobject/). لا تقم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيتسبب ذلك في أخطاء وقت تشغيل أو أخطاء تأكيد. دائمًا قم بتغليف هذه الفئة في مؤشر [System::SmartPtr](../smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class TimeZoneInfo : public System::IEquatable<TimeZoneInfoPtr>
```

## Methods

| Method | Description |
| --- | --- |
| static void [ClearCachedData](./clearcacheddata/)() | مسح بيانات المنطقة الزمنية المخزَّنة مؤقتًا. |
| static [DateTime](../datetime/) [ConvertTime](./converttime/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&, const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | [Convert](../convert/) الوقت من منطقة زمنية إلى أخرى. |
| static [DateTimeOffset](../datetimeoffset/) [ConvertTime](./converttime/)(const [DateTimeOffset](../datetimeoffset/)\&, const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | [Convert](../convert/) الوقت إلى الوقت في منطقة زمنية محددة. |
| static [DateTime](../datetime/) [ConvertTime](./converttime/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | [Convert](../convert/) الوقت إلى الوقت في منطقة زمنية محددة. |
| static [DateTime](../datetime/) [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)([DateTime](../datetime/), const [String](../string/)\&) | [Convert](../convert/) الوقت إلى الوقت في منطقة زمنية محددة. |
| static [DateTimeOffset](../datetimeoffset/) [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)(const [DateTimeOffset](../datetimeoffset/)\&, const [String](../string/)\&) | [Convert](../convert/) الوقت إلى الوقت في منطقة زمنية محددة. |
| static [DateTime](../datetime/) [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)([DateTime](../datetime/), const [String](../string/)\&, const [String](../string/)\&) | [Convert](../convert/) الوقت إلى الوقت في منطقة زمنية محددة. |
| static [DateTime](../datetime/) [ConvertTimeFromUtc](./converttimefromutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | يحوَّل الوقت بالتوقيت العالمي UTC إلى الوقت في منطقة زمنية محددة. |
| static [DateTime](../datetime/) [ConvertTimeToUtc](./converttimetoutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | يحوَّل الوقت إلى توقيت UTC. |
| static [DateTime](../datetime/) [ConvertTimeToUtc](./converttimetoutc/)([DateTime](../datetime/)) | يحوَّل الوقت إلى توقيت UTC. |
| static [DateTime](../datetime/) [ConvertTimeToUtcNoThrow](./converttimetoutcnothrow/)([DateTime](../datetime/)) | يحوَّل الوقت إلى توقيت UTC. للاستخدام الداخلي. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [CreateCustomTimeZone](./createcustomtimezone/)(const [String](../string/)\&, [TimeSpan](../timespan/), const [String](../string/)\&, const [String](../string/)\&, const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[AdjustmentRulePtr](./adjustmentruleptr/)\>\&, **bool**) | ينشئ منطقة زمنية مخصصة. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [CreateCustomTimeZone](./createcustomtimezone/)(const [String](../string/)\&, [TimeSpan](../timespan/), const [String](../string/)\&, const [String](../string/)\&, const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[AdjustmentRulePtr](./adjustmentruleptr/)\>\&) | ينشئ منطقة زمنية مخصصة. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [CreateCustomTimeZone](./createcustomtimezone/)(const [String](../string/)\&, [TimeSpan](../timespan/), const [String](../string/)\&, const [String](../string/)\&) | ينشئ منطقة زمنية مخصصة. |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override |  |
| **bool** [Equals](./equals/)([TimeZoneInfoPtr](../timezoneinfoptr/)) override | يحدِّد ما إذا كان الكائنان الحالي والمحدد متساويين. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [FindSystemTimeZoneById](./findsystemtimezonebyid/)(const [String](../string/)\&) | يحصل على المنطقة الزمنية ذات المعرف المحدد. |
| [TimeSpan](../timespan/) [get_BaseUtcOffset](./get_baseutcoffset/)() const | يعيد مثيلًا من [TimeSpan](../timespan/) يمثل فاصلًا زمنيًا بين التوقيت القياسي للمنطقة الزمنية الحالية وتوقيت UTC. |
| [String](../string/) [get_DaylightName](./get_daylightname/)() const | يحصل على اسم التوقيت الصيفي للمنطقة الزمنية الحالية. |
| [String](../string/) [get_DisplayName](./get_displayname/)() const | يحصل على اسم المنطقة الزمنية الحالية. |
| [String](../string/) [get_Id](./get_id/)() const | يعيد المعرف الخاص بالمنطقة الزمنية التي يمثلها الكائن الحالي. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [get_Local](./get_local/)() | يعيد مثيلًا من [TimeZoneInfo](./) يمثل منطقة زمنية محلية. |
| [String](../string/) [get_StandardName](./get_standardname/)() const | يحصل على اسم التوقيت القياسي للمنطقة الزمنية الحالية. |
| **bool** [get_SupportsDaylightSavingTime](./get_supportsdaylightsavingtime/)() const | يحصل على علم يشير إلى ما إذا كانت المنطقة الزمنية لها قواعد التوقيت الصيفي. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [get_Utc](./get_utc/)() | يعيد مثيلًا من [TimeZoneInfo](./) يمثل منطقة زمنية UTC. |
| [ArrayPtr](../arrayptr/)\<[AdjustmentRulePtr](./adjustmentruleptr/)\> [GetAdjustmentRules](./getadjustmentrules/)() const | يعيد مصفوفة تتكون من كائنات **AdjustmentRule** التي تمثل قواعد الضبط المطبقة على كائن [TimeZoneInfo](./) الحالي. |
| [ArrayPtr](../arrayptr/)\<[TimeSpan](../timespan/)\> [GetAmbiguousTimeOffsets](./getambiguoustimeoffsets/)([DateTime](../datetime/)) const | يحصل على تواريخ وأوقات UTC التي يمكن ربط تاريخ ووقت محددين بها. |
| [ArrayPtr](../arrayptr/)\<[TimeSpan](../timespan/)\> [GetAmbiguousTimeOffsets](./getambiguoustimeoffsets/)(const [DateTimeOffset](../datetimeoffset/)\&) const | يحصل على تواريخ وأوقات UTC التي يمكن ربط تاريخ ووقت محددين بها. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| int [GetHashCode](./gethashcode/)() const override | تناظر طريقة C# [Object.GetHashCode()](../object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| static [SharedPtr](../sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<[TimeZoneInfoPtr](../timezoneinfoptr/)\>\> [GetSystemTimeZones](./getsystemtimezones/)() | يحصل على مجموعة مرتبة من جميع المناطق الزمنية المتوفرة على النظام المحلي. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر استدعاء C# [System.Object.GetType()](../object/gettype/). |
| [TimeSpan](../timespan/) [GetUtcOffset](./getutcoffset/)([DateTime](../datetime/)) const | يحسب الفرق بين الوقت في هذه المنطقة الزمنية ومنطقة UTC لتاريخ ووقت محددين. |
| [TimeSpan](../timespan/) [GetUtcOffset](./getutcoffset/)(const [DateTimeOffset](../datetimeoffset/)\&) const | يحسب الفرق بين الوقت في هذه المنطقة الزمنية ومنطقة UTC لتاريخ ووقت محددين. |
| static [TimeSpan](../timespan/) [GetUtcOffsetFromUtc](./getutcoffsetfromutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | دالة مساعدة داخلية تُعيد إزاحة UTC لتاريخ-وقت UTC في منطقة زمنية محددة. للاستخدام الداخلي. |
| static [TimeSpan](../timespan/) [GetUtcOffsetFromUtc](./getutcoffsetfromutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&, **bool**\&, **bool**\&) | دالة مساعدة داخلية تُعيد إزاحة UTC لتاريخ-وقت UTC في منطقة زمنية محددة. للاستخدام الداخلي. |
| [TimeSpan](../timespan/) [GetUtcOffsetNoThrow](./getutcoffsetnothrow/)([DateTime](../datetime/)) const | يحسب الفرق بين الوقت في هذه المنطقة الزمنية ومنطقة UTC لتاريخ ووقت محددين. للاستخدام الداخلي. |
| **bool** [HasSameRules](./hassamerules/)(const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) const | يتحقق مما إذا كانت المنطقة الزمنية الحالية وأخرى لها نفس قواعد الضبط. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلًا لنوع موصوف بـ targetType. تناظر معامل C# 'is'. |
| **bool** [IsAmbiguousTime](./isambiguoustime/)([DateTime](../datetime/)) const | يتحقق مما إذا كان التاريخ والوقت المحددان غامضين ويمكن ربطهما بالعديد من أوقات UTC. |
| **bool** [IsAmbiguousTime](./isambiguoustime/)(const [DateTimeOffset](../datetimeoffset/)\&) const | يتحقق مما إذا كان التاريخ والوقت المحددان غامضين ويمكن ربطهما بالعديد من أوقات UTC. |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)([DateTime](../datetime/)) const | يتحقق مما إذا كان التاريخ والوقت المحددان يقعان ضمن نطاق التوقيت الصيفي. |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)(const [DateTimeOffset](../datetimeoffset/)\&) const | يتحقق مما إذا كان التاريخ والوقت المحددان يقعان ضمن نطاق التوقيت الصيفي. |
| **bool** [IsDaylightSavingTimeNoThrow](./isdaylightsavingtimenothrow/)([DateTime](../datetime/)) const | يتحقق مما إذا كان التاريخ والوقت المحددان يقعان ضمن نطاق التوقيت الصيفي. |
| **bool** [IsInvalidTime](./isinvalidtime/)([DateTime](../datetime/)) const | يتحقق مما إذا كان التاريخ والوقت المحددان غير صالحين. |
| void [Lock](../object/lock/)() | يُنفّذ قفل بيان C# lock(). يُستدعى مباشرة أو يُستخدم كائن الحراسة [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../object/object/)([Object](../object/) const\&) | منشئ النسخة. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويتيح نسخ إنشاء الفئات المشتقة. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويتيح نسخ إنشاء الفئات المشتقة. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي مع nullptr بالمرجع. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصيص [Object::ReferenceEquals](../object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | يُقلِّل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | يضبط معامل القالب الـ n'th كإشارة ضعيفة (بدلاً من المشتركة). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| [String](../string/) [ToString](./tostring/)() const override | تناظر طريقة C# [Object.ToString()](../object/tostring/). يتيح تحويل الكائنات المخصصة إلى نص. |
| static [DateTime](../datetime/) [TransitionTimeToDateTime](./transitiontimetodatetime/)(**int32_t**, const **TransitionTime**\&) | دالة مساعدة تحوِّل سنة و**TransitionTime** إلى [DateTime](../datetime/). |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | يُنفّذ بناء C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | يُنفّذ فك قفل بيان C# lock(). يُستدعى مباشرة أو يُستخدم كائن الحراسة [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [AdjustmentRulePtr](./adjustmentruleptr/) | اسم مستعار لمؤشر مشترك إلى مثيل من فئة **AdjustmentRule**. |

## See Also

* الفئة [IEquatable](../iequatable/)
* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)