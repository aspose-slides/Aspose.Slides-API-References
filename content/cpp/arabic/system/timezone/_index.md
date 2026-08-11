---
title: TimeZone
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يمثل نطاقًا زمنيًا. يجب تخصيص كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم أبدًا بإنشاء مثيل من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيتسبب ذلك في أخطاء وقت التشغيل و/أو أخطاء التأكد. دائمًا قم بلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤامل لتمريره إلى الدوال كمعامل."
type: docs
weight: 1327
url: /ar/system/timezone/
---
## TimeZone الفئة

يمثل نطاقًا زمنيًا. يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../makeobject/) فقط. لا تقم أبدًا بإنشاء مثال من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيتسبب ذلك في أخطاء وقت التشغيل و/أو أخطاء التأكيد. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class TimeZone : public System::Object
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوي لأي قيمة، بما فيها NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوي لأي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| static [TimeZonePtr](../timezoneptr/) [get_CurrentTimeZone](./get_currenttimezone/)() | يعيد كائنًا جديدًا من الفئة [TimeZone](./) الذي يمثل النطاق الزمني الحالي. |
| virtual [String](../string/) [get_DaylightName](./get_daylightname/)() const | يعيد اسمًا للتوقيت الصيفي للنطاق الزمني الممثل بالكائن الحالي. |
| virtual [String](../string/) [get_StandardName](./get_standardname/)() const | يعيد اسمًا للتوقيت القياسي للنطاق الزمني الممثل بالكائن الحالي. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | يحصل على بنية عداد الإشارة المرتبطة بالكائن. |
| virtual [Globalization::DaylightTimePtr](../../system.globalization/daylighttimeptr/) [GetDaylightChanges](./getdaylightchanges/)(**int32_t**) | يعيد فترة التوقيت الصيفي لسنة معينة. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | تناظر طريقة C# [Object.GetHashCode()](../object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر نداء C# [System.Object.GetType()](../object/gettype/). |
| virtual [TimeSpan](../timespan/) [GetUtcOffset](./getutcoffset/)([DateTime](../datetime/)) | يعيد فرق التوقيت UTC للوقت المحلي المحدد. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثلاً للنوع الموصوف بـ targetType. تناظر عامل C# 'is'. |
| virtual **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)([DateTime](../datetime/)) | يحدد ما إذا كانت قيمة التاريخ والوقت التي يمثلها الكائن [DateTime](../datetime/) المحدد تقع ضمن نطاق التوقيت الصيفي للنطاق الزمني الذي يمثله الكائن [TimeZone](./) الحالي. |
| void [Lock](../object/lock/)() | يُطبق قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../object/object/)() | ينشئ الكائن. يتهيّئ جميع بنى البيانات الداخلية. |
|  [Object](../object/object/)([Object](../object/) const\&) | منشئ النسخة. لا ينسخ أي شيء في الواقع، فقط يتهيّئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية عبر النسخ. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | معامل الإسناد. لا ينسخ أي شيء في الواقع، فقط يتهيّئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية عبر النسخ. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | يقارن بالمرجعية كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصيص [Object::ReferenceEquals](../object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | يقلل عداد الإشارة المشتركة بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النمطي الـ n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشتركة. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | يزيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ينقص ويعيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | تناظر طريقة C# [Object.ToString()](../object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | يُطبق بنية C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | يُطبق فك قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ينقص عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضاً

* الفئة [Object](../object/)
* المجال [System](../)
* المكتبة [Aspose.Slides](../../)