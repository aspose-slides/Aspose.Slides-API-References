---
title: Html5Options
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للغة C++
description: يمثل خيارات تصدير HTML5.
type: docs
weight: 79
url: /ar/aspose.slides.export/html5options/
---
## Html5Options فئة

يمثل خيارات تصدير HTML5.

```cpp
class Html5Options : public Aspose::Slides::Export::SaveOptions,
                     public Aspose::Slides::Export::IHtml5Options
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يقلد مقارنة النقطة العائمة بنمط C# حيث يتم اعتبار NaNين متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يقلد مقارنة النقطة العائمة بنمط C# حيث يتم اعتبار NaNين متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| **bool** [get_AnimateShapes](./get_animateshapes/)() override | يعيد خيار تحريك الأشكال. قراءة **bool**. |
| **bool** [get_AnimateTransitions](./get_animatetransitions/)() override | يعيد خيار تحريك الانتقالات. قراءة **bool**. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | يعيد الخط المستخدم في حالة عدم العثور على الخط المصدر. يقرأ [System::String](../../system/string/). |
| **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() override | يحصل على قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الحروف المتصلة. عند تعيينها إلى **true**, ستُعطَّل الحروف المتصلة في الناتج المعروض. بشكل افتراضي, تُضبط هذه الخاصية إلى **false**. |
| **bool** [get_EmbedImages](./get_embedimages/)() override | يعيد خيار تضمين الصور. قراءة **bool**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | يعيد النمط البصري للتدرج. يقرأ [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::String](../../system/string/) [get_OutputPath](./get_outputpath/)() override | يحدد أين يجب تخزين الموارد الخارجية. يقرأ [System::String](../../system/string/). |
| [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() override | يمثل مستوى ضغط الصور |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | يمثل كائنًا رجعيًا لحفظ تحديثات التقدم كنسبة مئوية. انظر [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | يحدد ما إذا كان سيتم تخطي الروابط التشعبية التي تحتوي على استدعاءات JavaScript عند حفظ العرض التقديمي. قراءة **bool**. القيمة الافتراضية هي **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | يحصل على الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../islideslayoutoptions/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | يعيد أو يعيّن كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو ستُوقف. يقرأ [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل عدّاد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). تمكّن تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
|  [Html5Options](./html5options/)() | منشئ افتراضي. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. تماثل عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل بيان C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). تمكّن استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجعية مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يُقلِّل عدّاد المرجع المشترك بالقيمة المحددة. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_AnimateShapes](./set_animateshapes/)(**bool**) override | يضبط خيار تحريك الأشكال. كتابة **bool**. |
| void [set_AnimateTransitions](./set_animatetransitions/)(**bool**) override | يضبط خيار تحريك الانتقالات. كتابة **bool**. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | يضبط الخط المستخدم في حالة عدم العثور على الخط المصدر. يكتب [System::String](../../system/string/). |
| void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) override | يضبط قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الحروف المتصلة. عند تعيينها إلى **true**, ستُعطَّل الحروف المتصلة في الناتج المعروض. بشكل افتراضي, تُضبط هذه الخاصية إلى **false**. |
| void [set_EmbedImages](./set_embedimages/)(**bool**) override | يضبط خيار تضمين الصور. كتابة **bool**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | يضبط النمط البصري للتدرج. كتابة [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_OutputPath](./set_outputpath/)([System::String](../../system/string/)) override | يحدد أين يجب تخزين الموارد الخارجية. كتابة [System::String](../../system/string/). |
| void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) override | يمثل مستوى ضغط الصور |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | يمثل كائنًا رجعيًا لحفظ تحديثات التقدم كنسبة مئوية. انظر [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | يحدد ما إذا كان سيتم تخطي الروابط التشعبية التي تحتوي على استدعاءات JavaScript عند حفظ العرض التقديمي. كتابة **bool**. القيمة الافتراضية هي **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | يضبط الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../islideslayoutoptions/). |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | يعيد أو يعيّن كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو ستُوقف. كتابة [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ضبط الوسيط النمطي الـ n كمؤشر ضعيف (بدلاً من المشترك). يسمح بتبديل المؤشرات في الحاويات إلى وضع الضعف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعدد المرَجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يُقلِّل ويعيد عدّاد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). تمكّن تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل بيان C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يُقلِّل عدّاد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## ملاحظات

مثال: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-shapes-and-transitions.html", SaveFormat::Html5, options);
```

## انظر أيضًا

* الفئة [SaveOptions](../saveoptions/)
* الفئة [IHtml5Options](../ihtml5options/)
* مساحة الأسماء [Aspose::Slides::Export](../)
* المكتبة [Aspose.Slides](../../)