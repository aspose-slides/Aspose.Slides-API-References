---
title: RenderingOptions
second_title: مرجع API Aspose.Slides للغة C++
description: يوفر خيارات تتحكم في طريقة عرض العرض التقديمي/الشريحة.
type: docs
weight: 638
url: /ar/aspose.slides.export/renderingoptions/
---
## RenderingOptions فئة


يوفر خيارات تتحكم في كيفية عرض العرض التقديمي/الشريحة.

```cpp
class RenderingOptions : public Aspose::Slides::Export::SaveOptions,
                         public Aspose::Slides::Export::IRenderingOptions
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة نقطة عائمة على نمط C# حيث يتم اعتبار NaNين متساويين رغم أنه وفقًا للمواصفات IEC 60559:1989 لا يعتبر NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة نقطة عائمة على نمط C# حيث يتم اعتبار NaNين متساويين رغم أنه وفقًا للمواصفات IEC 60559:1989 لا يعتبر NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | يعيد الخط المستخدم في حال عدم العثور على الخط المصدر. يقرأ [System::String](../../system/string/). |
| **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() override | يحصل على قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الحروف المتصلة. عند تعيينها إلى **true**, سيتم تعطيل الحروف المتصلة في المخرجات المعروضة. بشكل افتراضي، تُضبط هذه الخاصية إلى **false**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | يعيد النمط البصري للتدرج. يقرأ [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | يوفر خيارات تتحكم في مظهر كائنات [Ink](../../aspose.slides.ink/) في المستند المصدّر. للقراءة فقط [IInkOptions](../iinkoptions/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | يمثل كائن استدعاء للعودة لحفظ تحديثات التقدّم كنسبة مئوية. انظر [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | يحدد ما إذا كان يجب تخطي الروابط التشعبية التي تحتوي على استدعاءات JavaScript عند حفظ العرض التقديمي. يقرأ **bool**. القيمة الافتراضية هي **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | يحصل على الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../islideslayoutoptions/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | يعيد أو يضع كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو ستُجهض. يقرأ [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الذي يصفه targetType. تماثل عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يُنفّذ إقفال بيان C# lock(). استدعِه مباشرة أو استخدم [LockContext](../../system/lockcontext/) كائن الحراسة. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعلاً، فقط يهيئ كائنًا جديدًا ويتيح إنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعلاً، فقط يهيئ كائنًا جديدًا ويتيح إنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع (nullptr). |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
|  [RenderingOptions](./renderingoptions/)() | منشئ افتراضي. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | يضبط الخط المستخدم في حال عدم العثور على الخط المصدر. يكتب [System::String](../../system/string/). |
| void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) override | يضبط قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الحروف المتصلة. عند تعيينها إلى **true**, سيتم تعطيل الحروف المتصلة في المخرجات المعروضة. بشكل افتراضي، تُضبط هذه الخاصية إلى **false**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | يضبط النمط البصري للتدرج. يكتب [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | يمثل كائن استدعاء للعودة لحفظ تحديثات التقدّم كنسبة مئوية. انظر [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | يحدد ما إذا كان يجب تخطي الروابط التشعبية التي تحتوي على استدعاءات JavaScript عند حفظ العرض التقديمي. يكتب **bool**. القيمة الافتراضية هي **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | يضبط الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../islideslayoutoptions/). |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | يعيد أو يضع كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو ستُجهض. يكتب [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النمطي الفاصل كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء إقفال بيان C# lock(). استدعِه مباشرة أو استخدم [LockContext](../../system/lockcontext/) كائن الحراسة. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |
## ملاحظات



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IRenderingOptions> renderingOpts = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
renderingOpts->set_SlidesLayoutOptions(slidesLayoutOptions);

System::SharedPtr<ISlide> slide = pres->get_Slide(0);

slide->GetImage(renderingOpts)->Save(u"pres-Original.png", ImageFormat::Png);

renderingOpts->set_DefaultRegularFont(u"Arial Black");
slide->GetImage(renderingOpts)->Save(u"pres-ArialBlackDefault.png", ImageFormat::Png);

renderingOpts->set_DefaultRegularFont(u"Arial Narrow");
slide->GetImage(renderingOpts)->Save(u"pres-ArialNarrowDefault.png", ImageFormat::Png);
```




## انظر أيضًا

* فئة [SaveOptions](../saveoptions/)
* فئة [IRenderingOptions](../irenderingoptions/)
* مساحة الاسم [Aspose::Slides::Export](../)
* مكتبة [Aspose.Slides](../../)