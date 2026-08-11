---
title: Regex
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "تعبير نمطي يتبع صيغة مشابهة لـ C#. يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيسبب أخطاء تشغيلية و/أو أعطال تأكيد. دائمًا قم بلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 92
url: /ar/system.text.regularexpressions/regex/
---
## فئة Regex

تعبير نمطي يتبع صيغة مشابهة لـ C#. يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيسبب أخطاء تشغيلية و/أو أعطال تأكيد. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class Regex : public System::Object
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوك C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يُحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُنظر إلى NaNين على أنهما متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يُحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُنظر إلى NaNين على أنهما متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static [String](../../system/string/) [Escape](./escape/)(const [String](../../system/string/)\&) | يهرب الأحرف الخاصة لاستخدام السلسلة كجزء من النمط. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [TimeSpan](../../system/timespan/) [get_MatchTimeout](./get_matchtimeout/)() | يحصل على مهلة التطابق. |
| [RegexOptions](../regexoptions/) [get_Options](./get_options/)() | يحصل على خيارات التعبير النمطي. |
| **bool** [get_RightToLeft](./get_righttoleft/)() | يفحص ما إذا كان التطابق يتم في وضع من اليمين إلى اليسار. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد الإشارة المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. تماثل عامل C# 'is'. |
| **bool** [IsMatch](./ismatch/)(const [String](../../system/string/)\&, int) | يطابق التعبير النمطي مع السلسلة. |
| static **bool** [IsMatch](./ismatch/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/), int) | يفحص ما إذا كانت السلسلة تطابق النمط. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل تعبير C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| [MatchPtr](../matchptr/) [Match](./match/)(const [String](../../system/string/)\&) | يطابق التعبير النمطي مع السلسلة. |
| [MatchPtr](../matchptr/) [Match](./match/)(const [String](../../system/string/)\&, int, int) | يطابق التعبير النمطي مع السلسلة. |
| static [MatchPtr](../matchptr/) [Match](./match/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/), int, int) | يطابق السلسلة والنمط. |
| [MatchCollectionPtr](../matchcollectionptr/) [Matches](./matches/)(const [String](../../system/string/)\&, int) | يحصل على جميع التطابقات للتعبير النمطي في السلسلة المعطاة عبر مطابقة متكررة. |
| static [MatchCollectionPtr](../matchcollectionptr/) [Matches](./matches/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/), int, int) | يحصل على جميع التطابقات بين السلسلة والنمط. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | يُنشئ كائنًا. يهيئ جميع البُنى الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخة. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويتيح إنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويتيح إنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
|  [Regex](./regex/)() | يبني تعبير نمطي فارغ. |
|  [Regex](./regex/)(const [String](../../system/string/)\&) | منشئ. |
|  [Regex](./regex/)(const [String](../../system/string/)\&, [RegexOptions](../regexoptions/)) | منشئ. |
|  [Regex](./regex/)(const [String](../../system/string/)\&, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/)) | منشئ. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد المرجعية المشتركة بالقيمة المحددة. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | يستبدل جميع تطابقات التعبير النمطي في السلسلة بسلسلة الاستبدال. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const char_t *) | يستبدل جميع تطابقات التعبير النمطي في السلسلة بسلسلة الاستبدال. |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const char_t *, const char_t *) | يستبدل جميع تطابقات التعبير النمطي في السلسلة بسلسلة الاستبدال. |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const char_t *) | يستبدل جميع تطابقات التعبير النمطي في السلسلة بسلسلة الاستبدال. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [MatchEvaluator](../matchevaluator/)\&) | يستبدل جميع التطابقات في السلسلة بسلاسل استبدال مُولدة بواسطة المُندوب. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [MatchEvaluator](../matchevaluator/)\&, int) | يستبدل جميع التطابقات في السلسلة بسلاسل استبدال مُولدة بواسطة المُندوب. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [MatchEvaluator](../matchevaluator/)\&, int, int) | يستبدل جميع التطابقات في السلسلة بسلاسل استبدال مُولدة بواسطة المُندوب. |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [MatchEvaluator](../matchevaluator/)\&, [RegexOptions](../regexoptions/)) | يستبدل جميع التطابقات في السلسلة بسلاسل استبدال مُولدة بواسطة المُندوب (دالة ثابتة). |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, [RegexOptions](../regexoptions/)) | يستبدل جميع تطابقات التعبير النمطي في السلسلة بسلسلة الاستبدال. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int) | يستبدل السلاسل الفرعية في السلسلة. غير مُطبق. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) | يستبدل السلاسل الفرعية في السلسلة. غير مُطبق. |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | يستبدل تطابقات التعبير النمطي. |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [MatchEvaluator](../matchevaluator/)\&) | يستبدل تطابقات التعبير النمطي. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي رقم n كمؤشر ضعيف (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجعية المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجعية المشتركة. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجعية المشتركة. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [Split](./split/)(const [String](../../system/string/)\&) | يقسم السلسلة حسب تطابقات التعبير النمطي. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [Split](./split/)(const [String](../../system/string/)\&, int) | يقسم السلسلة حسب تطابقات التعبير النمطي. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [Split](./split/)(const [String](../../system/string/)\&, int, int) | يقسم السلسلة المدخلة إلى عدد محدد أقصى من المرات إلى مصفوفة من السلاسل الفرعية، عند المواقع المحددة بواسطة تعبير نمطي محدد في مُنشئ [Regex](./). يبدأ البحث عن نمط التعبير النمطي من موضع حرف محدد في السلسلة المدخلة. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [Split](./split/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/)) | يقسم السلسلة عبر التعبير النمطي. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [Split](./split/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/)) | يقسم السلسلة عبر التعبير النمطي. |
| [String](../../system/string/) [ToString](./tostring/)() const override | يحول التعبير النمطي إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| static [String](../../system/string/) [Unescape](./unescape/)(const [String](../../system/string/)\&) | يلغى هروب الأحرف الخاصة في السلسلة المستخدمة كجزء من النمط. |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل تعبير C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجعية الضعيفة. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجعية الضعيفة. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع البُنى الداخلية. |

## الحقول

| الحقل | الوصف |
| --- | --- |
| static [InfiniteMatchTimeout](./infinitematchtimeout/) | قيمة مهلة خاصة لتعطيل انقطاع المطابقة بسبب المهلة. |

## انظر أيضًا

* الفئة [Object](../../system/object/)
* النطاق [System::Text::RegularExpressions](../)
* المكتبة [Aspose.Slides](../../)