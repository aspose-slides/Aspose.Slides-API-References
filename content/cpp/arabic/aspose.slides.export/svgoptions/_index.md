---
title: SVGOptions
second_title: مرجع API Aspose.Slides للغة C++
description: يمثل خيار SVG.
type: docs
weight: 703
url: /ar/aspose.slides.export/svgoptions/
---
## SVGOptions فئة

Represents an SVG options.

```cpp
class SVGOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISVGOptions
```

## الطرق

| طريقة | وصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة عدد عائم بنمط C# حيث تُعتبر NaNان متساوية رغم أنه وفقاً لـ IEC 60559:1989 NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة عدد مزدوج بنمط C# حيث تُعتبر NaNان متساوية رغم أنه وفقاً لـ IEC 60559:1989 NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Default](./get_default/)() | يرجع الإعدادات الافتراضية. للقراءة فقط [SVGOptions](./). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | يرجع الخط المستخدم في حال عدم العثور على الخط الأصلي. يقرأ [System::String](../../system/string/). |
| **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() override | علامة منطقية تشير إلى ما إذا كانت الأجزاء المقصوصة تبقى كجزء من المستند. إذا كانت true ستُزال الأجزاء المقصوصة، وإذا كانت false سيتم تسلسلها في المستند (ما قد يؤدي إلى ملف أكبر). |
| **bool** [get_Disable3DText](./get_disable3dtext/)() override | يحدد ما إذا كان النص ثلاثي الأبعاد مُعطَّلًا في SVG. يقرأ **bool**. |
| **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() override | يحصل على قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. عند تعيينها إلى **true**، ستُعطل الأحرف المتصلة في النتيجة المعروضة. افتراضيًا، تُضبط هذه الخاصية على **false**. |
| **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() override | يعطل تقسيم التدرجات FromCornerX و FromCenter. يقرأ **bool**. |
| **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() override | لا يدعم SVG 1.1 القدرة على تعريف هوامش للعلامات. [Aspose.Slides](../../aspose.slides/) محرك كتابة SVG لديه حل لهذه المشكلة: يقوم بقص نهاية الخط مع السهم، وبالتالي لا يتداخل الخط مع العلامات. هذا الخيار يعطل هذا السلوك. يقرأ **bool**. |
| [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() override | يحدد طريقة معالجة الخطوط المحملة من الخارج. يقرأ [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | يرجع النمط البصري للتدرج. يقرأ [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | يوفر خيارات تتحكم في مظهر كائنات [Ink](../../aspose.slides.ink/) في المستند المُصدَّر. للقراءة فقط [IInkOptions](../iinkoptions/) |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | يحدد جودة ترميز JPEG. يقرأ **int32_t**. |
| **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() override | يرجع الحد الأدنى للدقة لتقريب ملف الميتا. يقرأ **int32_t**. |
| [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() override | يمثل مستوى ضغط الصور |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | يمثل كائن رد نداء لحفظ تحديثات التقدم كنسبة مئوية. انظر [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() override | يرجع ويضبط واجهة رد نداء تسمح للمستخدم بالتحكم في تحويل الشكل. يقرأ [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Simple](./get_simple/)() | يرجع الإعدادات لتوليد أصغر وأبسط ملف SVG. للقراءة فقط [SVGOptions](./). |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | يحدد ما إذا كان يجب تخطي الروابط الفائقة التي تحتوي على استدعاءات JavaScript عند حفظ العرض التقديمي. يقرأ **bool**. القيمة الافتراضية هي **false**. |
| **bool** [get_UseFrameRotation](./get_useframerotation/)() override | يحدد ما إذا كان سيتم إجراء الدوران المحدد للشكل أثناء العرض أم لا. يقرأ **bool**. القيمة الافتراضية هي true. |
| **bool** [get_UseFrameSize](./get_useframesize/)() override | يحدد ما إذا كان إطار النص سيُضمن في مساحة العرض أم لا. يقرأ **bool**. القيمة الافتراضية هي false. |
| **bool** [get_VectorizeText](./get_vectorizetext/)() override | يحدد ما إذا كان سيتم حفظ النص على الشريحة كرسومات. يقرأ **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | يرجع أو يضبط كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو ستُوقف. يقرأ [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_WYSIWYG](./get_wysiwyg/)() | يرجع الإعدادات لتوليد ملف SVG بأعلى دقة. للقراءة فقط [SVGOptions](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عدّاد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثلاً من النوع الموصوف بواسطة targetType. نظير لمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يتهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ أي شيء فعليًا، فقط يتهيئ كائنًا جديدًا ويمكّن بناء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يتهيئ كائنًا جديدًا ويمكّن بناء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن بالمرجع كائن نوع قيم مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | يضبط الخط المستخدم في حال عدم العثور على الخط الأصلي. يكتب [System::String](../../system/string/). |
| void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) override | علامة منطقية تشير إلى ما إذا كانت الأجزاء المقصوصة تبقى كجزء من المستند. إذا كانت true ستُزال الأجزاء المقصوصة، وإذا كانت false سيتم تسلسلها في المستند (ما قد يؤدي إلى ملف أكبر). |
| void [set_Disable3DText](./set_disable3dtext/)(**bool**) override | يحدد ما إذا كان النص ثلاثي الأبعاد مُعطَّلًا في SVG. يكتب **bool**. |
| void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) override | يضبط قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. عند تعيينها إلى **true**، ستُعطل الأحرف المتصلة في النتيجة المعروضة. افتراضيًا، تُضبط هذه الخاصية على **false**. |
| void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) override | يعطل تقسيم التدرجات FromCornerX و FromCenter. يكتب **bool**. |
| void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) override | SVG 1.1 لا يدعم القدرة على تعريف هوامش للعلامات. [Aspose.Slides](../../aspose.slides/) محرك كتابة SVG لديه حل لهذه المشكلة: يقوم بقص نهاية الخط مع السهم، وبالتالي لا يتداخل الخط مع العلامات. هذا الخيار يعطل هذا السلوك. يكتب **bool**. |
| void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) override | يحدد طريقة معالجة الخطوط المحملة من الخارج. يكتب [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | يضبط النمط البصري للتدرج. يكتب [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | يحدد جودة ترميز JPEG. يكتب **int32_t**. |
| void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) override | يضبط الحد الأدنى للدقة لتقريب ملف الميتا. يكتب **int32_t**. |
| void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) override | يمثل مستوى ضغط الصور |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | يمثل كائن رد نداء لحفظ تحديثات التقدم كنسبة مئوية. انظر [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) override | يرجع ويضبط واجهة رد نداء تسمح للمستخدم بالتحكم في تحويل الشكل. يكتب [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | يحدد ما إذا كان يجب تخطي الروابط الفائقة التي تحتوي على استدعاءات JavaScript عند حفظ العرض التقديمي. يكتب **bool**. القيمة الافتراضية هي **false**. |
| void [set_UseFrameRotation](./set_useframerotation/)(**bool**) override | يحدد ما إذا كان سيتم إجراء الدوران المحدد للشكل أثناء العرض أم لا. يكتب **bool**. القيمة الافتراضية هي true. |
| void [set_UseFrameSize](./set_useframesize/)(**bool**) override | يحدد ما إذا كان إطار النص سيُضمن في مساحة العرض أم لا. يكتب **bool**. القيمة الافتراضية هي false. |
| void [set_VectorizeText](./set_vectorizetext/)(**bool**) override | يحدد ما إذا كان سيتم حفظ النص على الشريحة كرسومات. يكتب **bool**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | يرجع أو يضبط كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو ستُوقف. يكتب [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يُعيّن الوسيط القالب الـ n مؤشرًا ضعيفًا (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويُرجع عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
|  [SVGOptions](./svgoptions/)() | يهيئ مثالًا جديدًا من الفئة [SVGOptions](./). |
|  [SVGOptions](./svgoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ILinkEmbedController](../ilinkembedcontroller/)\>) | يهيئ مثالًا جديدًا من الفئة [SVGOptions](./) مع تحديد كائن التحكم في تضمين الرابط. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يطبق بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ فك قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يُحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* فئة [SaveOptions](../saveoptions/)
* فئة [ISVGOptions](../isvgoptions/)
* نطاق [Aspose::Slides::Export](../)
* مكتبة [Aspose.Slides](../../)