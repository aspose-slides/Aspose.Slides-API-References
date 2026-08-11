---
title: IHtml5Options
second_title: Aspose.Slides لـ C++ مرجع API
description: يمثل خيارات تصدير HTML5.
type: docs
weight: 170
url: /ar/aspose.slides.export/ihtml5options/
---
## IHtml5Options فئة

يمثل خيارات تصدير HTML5.

```cpp
class IHtml5Options : public virtual Aspose::Slides::Export::ISaveOptions
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام معايير C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع المرجع على نمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع القيمة على نمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث يُعتبر NaNانان متساويين على الرغم من أن IEC 60559:1989 تنص على أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث يُعتبر NaNانان متساويين على الرغم من أن IEC 60559:1989 تنص على أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| virtual **bool** [get_AnimateShapes](./get_animateshapes/)() | يعيد خيار تحريك الأشكال. قراءة **bool**. |
| virtual **bool** [get_AnimateTransitions](./get_animatetransitions/)() | يعيد خيار تحريك الانتقالات. قراءة **bool**. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | يعيد الخط المستخدم في حالة عدم العثور على الخط المصدر. يقرأ [System::String](../../system/string/). |
| virtual **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() | يحصل على قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. عند تعيينها إلى **true**, ستُعطل الأحرف المتصلة في الناتج المعروض. بشكل افتراضي، تُضبط هذه الخاصية إلى **false**. |
| virtual **bool** [get_EmbedImages](./get_embedimages/)() | يعيد خيار تضمين الصور. قراءة **bool**. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | يعيد النمط البصري للتدرج. يقرأ [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual [System::String](../../system/string/) [get_OutputPath](./get_outputpath/)() | يحدد أين يجب تخزين الموارد الخارجية. يقرأ [System::String](../../system/string/). |
| virtual [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() | يمثل مستوى ضغط الصور. قراءة [PicturesCompression](../picturescompression/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | يمثل كائن رد نداء لحفظ تحديثات التقدم كنسبة مئوية. انظر [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | يحدد ما إذا كان يجب تخطي الروابط التشعبية التي تحتوي على استدعاءات JavaScript عند حفظ العرض التقديمي. قراءة **bool**. القيمة الافتراضية هي **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | يحصل على الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | يعيد كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو سيتم إلغاؤها. يقرأ [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تناظر طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل مثيلًا لنوع موصوف بـ targetType. تناظر لمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح نسخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يُقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_AnimateShapes](./set_animateshapes/)(**bool**) | يضبط خيار تحريك الأشكال. كتابة **bool**. |
| virtual void [set_AnimateTransitions](./set_animatetransitions/)(**bool**) | يضبط خيار تحريك الانتقالات. كتابة **bool**. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | يضبط الخط المستخدم في حالة عدم العثور على الخط المصدر. يكتب [System::String](../../system/string/). |
| virtual void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. عند تعيينها إلى **true**, ستُعطل الأحرف المتصلة في الناتج المعروض. بشكل افتراضي، تُضبط هذه الخاصية إلى **false**. |
| virtual void [set_EmbedImages](./set_embedimages/)(**bool**) | يضبط خيار تضمين الصور. كتابة **bool**. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | يضبط النمط البصري للتدرج. كتابة [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_OutputPath](./set_outputpath/)([System::String](../../system/string/)) | يحدد أين يجب تخزين الموارد الخارجية. كتابة [System::String](../../system/string/). |
| virtual void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) | يمثل مستوى ضغط الصور. كتابة [PicturesCompression](../picturescompression/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | يمثل كائن رد نداء لحفظ تحديثات التقدم كنسبة مئوية. انظر [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | يحدد ما إذا كان يجب تخطي الروابط التشعبية التي تحتوي على استدعاءات JavaScript عند حفظ العرض التقديمي. كتابة **bool**. القيمة الافتراضية هي **false**. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | يضبط الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | يضبط كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو سيتم إلغاؤها. كتابة [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط القالب رقم n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استعمل مؤشرات ذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويُعيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استعمل مؤشرات ذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تناظر طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصَّصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل عبارة C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا يجب استدعاؤه مباشرة؛ استعمل مؤشرات ذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد الإشارة الضعيفة. لا يجب استدعاؤه مباشرة؛ استعمل مؤشرات ذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرِّر جميع بنى البيانات الداخلية. |

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

* الفئة [ISaveOptions](../isaveoptions/)
* مساحة الاسم [Aspose::Slides::Export](../)
* المكتبة [Aspose.Slides](../../)