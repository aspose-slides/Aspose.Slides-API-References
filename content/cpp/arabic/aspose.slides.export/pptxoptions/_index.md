---
title: PptxOptions
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل خيارات حفظ عروض OpenXml (PPTX، PPSX، POTX، PPTM، PPSM، POTM).
type: docs
weight: 599
url: /ar/aspose.slides.export/pptxoptions/
---
## فئة PptxOptions

يمثل الخيارات لحفظ عروض OpenXml (PPTX، PPSX، POTX، PPTM، PPSM، POTM).

```cpp
class PptxOptions : public Aspose::Slides::Export::SaveOptions,
                    public Aspose::Slides::Export::IPptxOptions
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوكيات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقاط العائمة بنمط C# حيث يُعتبر كلا القيمتين NaN متساويتين رغم أن معيار IEC 60559:1989 ينص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقاط العائمة بنمط C# حيث يُعتبر كلا القيمتين NaN متساويتين رغم أن معيار IEC 60559:1989 ينص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [Aspose::Slides::Export::CompressionLevel](../compressionlevel/) [get_CompressionLevel](./get_compressionlevel/)() override | يحدد مستوى الضغط المستخدم عند حفظ مستند العرض التقديمي. القيمة الافتراضية هي [CompressionLevel::Level6](../compressionlevel/). |
| [Aspose::Slides::Export::Conformance](../conformance/) [get_Conformance](./get_conformance/)() override | يحدد فئة التوافق التي يتوافق معها مستند [Presentation](../../aspose.slides/presentation/). القيمة الافتراضية هي [Aspose::Slides::Export::Conformance::Ecma376_2006](../conformance/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | يعيد الخط المستخدم في حالة عدم العثور على الخط الأصلي. يقرأ [System::String](../../system/string/). |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | يعيد النمط البصري للتدرج. يقرأ [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | يمثل كائنًا للرد عند حفظ تقدم الحفظ كنسبة مئوية. انظر [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_RefreshThumbnail](./get_refreshthumbnail/)() override | يحدد ما إذا كان سيتم تحديث صورة العرض المصغرة. يقرأ **bool**. القيمة الافتراضية هي **true**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | يحدد ما إذا كان سيتم تخطي الروابط التشعبية ذات استدعاءات JavaScript عند حفظ العرض التقديمي. يقرأ **bool**. القيمة الافتراضية هي **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | يعيد أو يضبط كائنًا يستقبل التحذيرات ويحدد ما إذا كانت عملية التحميل ستستمر أم ستُوقف. يقرأ [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| [Aspose::Slides::Export::Zip64Mode](../zip64mode/) [get_Zip64Mode](./get_zip64mode/)() override | يحدد ما إذا كان تنسيق ZIP64 مستخدمًا لمستند [Presentation](../../aspose.slides/presentation/). القيمة الافتراضية هي [Zip64Mode::IfNecessary](../zip64mode/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نسخة مماثلة لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نسخة مماثلة لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نسخة مماثلة للمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة lock() في C#. استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نسخة مماثلة لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح نسخ الأنواع المخصصة. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [PptxOptions](./pptxoptions/)() | ينشئ نسخة جديدة من [PptxOptions](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_CompressionLevel](./set_compressionlevel/)([Aspose::Slides::Export::CompressionLevel](../compressionlevel/)) override | يحدد مستوى الضغط المستخدم عند حفظ مستند العرض التقديمي. القيمة الافتراضية هي [CompressionLevel::Level6](../compressionlevel/). |
| void [set_Conformance](./set_conformance/)([Aspose::Slides::Export::Conformance](../conformance/)) override | يحدد فئة التوافق التي يتوافق معها مستند [Presentation](../../aspose.slides/presentation/). القيمة الافتراضية هي [Aspose::Slides::Export::Conformance::Ecma376_2006](../conformance/). |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | يضبط الخط المستخدم في حالة عدم العثور على الخط الأصلي. يكتب [System::String](../../system/string/). |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | يضبط النمط البصري للتدرج. يكتب [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | يمثل كائن رد نداء لتحديثات حفظ التقدم بالنسبة المئوية. انظر [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_RefreshThumbnail](./set_refreshthumbnail/)(**bool**) override | يحدد ما إذا كان سيتم تحديث صورة العرض المصغرة. يكتب **bool**. القيمة الافتراضية هي **true**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | يحدد ما إذا كان سيتم تخطي الروابط التشعبية ذات استدعاءات JavaScript عند حفظ العرض التقديمي. يكتب **bool**. القيمة الافتراضية هي **false**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | يعيد أو يضبط كائنًا يستقبل التحذيرات ويحدد ما إذا كانت عملية التحميل ستستمر أم ستُوقف. يكتب [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| void [set_Zip64Mode](./set_zip64mode/)([Aspose::Slides::Export::Zip64Mode](../zip64mode/)) override | يحدد ما إذا كان تنسيق ZIP64 مستخدمًا لمستند [Presentation](../../aspose.slides/presentation/). القيمة الافتراضية هي [Zip64Mode::IfNecessary](../zip64mode/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n كإشارة ضعيفة (بدلاً من مشتركة). يتيح تحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعدد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نسخة مماثلة لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل عبارة lock() في C#. استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [SaveOptions](../saveoptions/)
* الفئة [IPptxOptions](../ipptxoptions/)
* النطاق [Aspose::Slides::Export](../)
* المكتبة [Aspose.Slides](../../)