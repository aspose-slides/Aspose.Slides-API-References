---
title: CompareInfo
second_title: مرجع API الخاص بـ Aspose.Slides للـ C++
description: "يجري مقارنة سلاسل حساسة للثقافة. يجب إنشاء كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم أبداً بإنشاء مثيل من هذا النوع على المكدس أو باستخدام عامل new، لأن ذلك سيتسبب في أخطاء وقت التشغيل أو أعطال التأكيد. دائمًا قم بلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 40
url: /ar/system.globalization/compareinfo/
---
## CompareInfo فئة

يُجري مقارنة سلاسل حساسة للثقافة. يجب إنشاء كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم أبداً بإنشاء مثيل من هذا النوع على المكدس أو باستخدام عامل new، لأن ذلك سيتسبب في أخطاء وقت التشغيل أو أعطال التأكيد. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class CompareInfo : public virtual System::Object
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | يقارن السلاسل. غير مُنفّذ. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | يقارن السلاسل. يتم دعم وضعَي Ordinal وOrdinalIgnoreCase فقط. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, int, const [String](../../system/string/)\&, int, int) const | يقارن جزءًا من سلسلة مع جزء من سلسلة أخرى. غير مُنفّذ. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | يقارن الجزء النهائي من سلسلة مع الجزء النهائي من سلسلة أخرى باستخدام طرق مقارنة السلاسل. غير مُنفّذ. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, const [String](../../system/string/)\&, int) const | يقارن الجزء النهائي من سلسلة مع الجزء النهائي من سلسلة أخرى. غير مُنفّذ. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, int, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | يقارن جزءًا من سلسلة مع جزء من سلسلة أخرى باستخدام طرق مقارنة السلاسل. غير مُنفّذ. |
|  [CompareInfo](./compareinfo/)(const [CompareInfo](./)\&) | معلومات RTTI. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | محاكاة مقارنة نقطية بنمط C# حيث تُعتَبر NaNين متساويتين على الرغم من أن IEC 60559:1989 تُعرّف أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | محاكاة مقارنة نقطية بنمط C# حيث تُعتَبر NaNين متساويتين على الرغم من أن IEC 60559:1989 تُعرّف أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| int [get_LCID](./get_lcid/)() const | يحصل على LCID للثقافة المرتبطة بالمقارن. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() const | يحصل على اسم الثقافة المرتبطة بالمقارن. |
| [SortVersionPtr](../sortversionptr/) [get_Version](./get_version/)() const | يحصل على معلومات عن إصدار الترتيب. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(int, const [SharedPtr](../../system/sharedptr/)\<[Reflection::Assembly](../../system.reflection/assembly/)\>\&) | يحصل على [CompareInfo](./) المرتبط بالثقافة المحددة ويستخدم طرق مقارنة السلاسل في التجميع المحدد. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Reflection::Assembly](../../system.reflection/assembly/)\>\&) | يحصل على [CompareInfo](./) المرتبط بالثقافة المحددة ويستخدم طرق مقارنة السلاسل في التجميع المحدد. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(int) | يحصل على [CompareInfo](./) المرتبط بالثقافة المحددة. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(const [String](../../system/string/)\&) | يحصل على [CompareInfo](./) المرتبط بالثقافة المحددة. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عدّاد المرجع المرتبطة بالكائن. |
| virtual int [GetHashCode](./gethashcode/)(const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | يحصل على رمز التجزئة للسلسلة بناءً على خيارات المقارنة المحددة. |
| int [GetHashCode](./gethashcode/)() const override | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصّصة. |
| virtual [SortKeyPtr](../sortkeyptr/) [GetSortKey](./getsortkey/)(const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | يحصل على كائن [SortKey](../sortkey/) للسلسلة المحددة باستخدام خيارات المقارنة المحددة. |
| virtual [SortKeyPtr](../sortkeyptr/) [GetSortKey](./getsortkey/)(const [String](../../system/string/)\&) const | يحصل على كائن [SortKey](../sortkey/) للسلسلة المحددة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) const | يبحث عن سلسلة فرعية. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | يبحث عن سلسلة فرعية. يتم دعم وضع Ordinal فقط. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | يبحث عن سلسلة فرعية. يتم دعم وضع Ordinal فقط. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, int, [CompareOptions](../compareoptions/)) const | يبحث عن الحرف المحدد. يتم دعم وضع Ordinal فقط. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int) const | يبحث عن سلسلة فرعية. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t) const | يبحث عن الحرف المحدد. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | يبحث عن سلسلة فرعية. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, [CompareOptions](../compareoptions/)) const | يبحث عن الحرف المحدد. يتم دعم وضع Ordinal فقط. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, int) const | يبحث عن الحرف المحدد. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int) const | يبحث عن الحرف المحدد. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | يبحث عن سلسلة فرعية. يتم دعم وضع Ordinal فقط. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, [CompareOptions](../compareoptions/)) const | يبحث عن الحرف المحدد. يتم دعم وضع Ordinal فقط. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. تماثل عامل C# 'is'. |
| virtual **bool** [IsPrefix](./isprefix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | يتحقق مما إذا كانت السلسلة المحددة تبدأ بالبادئة المحددة باستخدام خيارات المقارنة المحددة. |
| virtual **bool** [IsPrefix](./isprefix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | يتحقق مما إذا كانت السلسلة المحددة تبدأ بالبادئة المحددة. |
| static **bool** [IsSortable](./issortable/)(char16_t) | يتحقق مما إذا كان الحرف المحدد قابلًا للترتيب. |
| static **bool** [IsSortable](./issortable/)(const [String](../../system/string/)\&) | يتحقق مما إذا كانت السلسلة المحددة قابلة للترتيب. |
| virtual **bool** [IsSuffix](./issuffix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | يتحقق مما إذا كانت السلسلة المحددة تنتهي باللاحقة المحددة باستخدام خيارات المقارنة المحددة. |
| virtual **bool** [IsSuffix](./issuffix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | يتحقق مما إذا كانت السلسلة المحددة تنتهي باللاحقة المحددة. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | يبحث عن آخر حدوث للسلسلة الفرعية المحددة. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | يبحث عن آخر حدوث للسلسلة الفرعية المحددة باستخدام خيارات المقارنة المحددة. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, int, [CompareOptions](../compareoptions/)) const | يبحث عن آخر حدوث للحرف المحدد باستخدام خيارات المقارنة المحددة. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) const | يبحث عن آخر حدوث للسلسلة المحددة. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | يبحث عن آخر حدوث للسلسلة المحددة باستخدام خيارات المقارنة المحددة. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, [CompareOptions](../compareoptions/)) const | يبحث عن آخر حدوث للحرف المحدد باستخدام خيارات المقارنة المحددة. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int) const | يبحث عن آخر حدوث للسلسلة المحددة. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int) const | يبحث عن آخر حدوث للحرف المحدد. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | يبحث عن آخر حدوث للسلسلة المحددة باستخدام خيارات المقارنة المحددة. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, [CompareOptions](../compareoptions/)) const | يبحث عن آخر حدوث للحرف المحدد باستخدام خيارات المقارنة المحددة. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t) const | يبحث عن آخر حدوث للحرف المحدد. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, int) const | يبحث عن آخر حدوث للحرف المحدد. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصّصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات المشتقة. |
| [CompareInfo](./)\& [operator=](./operator_equal/)(const [CompareInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات المشتقة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط معامل القالب nth إلى مؤشر ضعيف (بدلاً من المشترك). يتيح تحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عدّاد المرجع المشترك ويعيد قيمته. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| [String](../../system/string/) [ToString](./tostring/)() const override | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصّصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [Object](../../system/object/)
* النطاق [System::Globalization](../)
* المكتبة [Aspose.Slides](../../)