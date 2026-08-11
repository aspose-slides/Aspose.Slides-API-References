---
title: IHtmlOptions
second_title: Aspose.Slides للـ C++ مرجع API
description: يمثل خيارات تصدير HTML.
type: docs
weight: 222
url: /ar/aspose.slides.export/ihtmloptions/
---
## فئة IHtmlOptions

يمثِّل خيارات تصدير HTML.

```cpp
class IHtmlOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يقوم بمحاكاة مقارنة النقطة العائمة بنمط C# حيث تُعتبر قيمة NaNين متساوية على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يقوم بمحاكاة مقارنة النقطة العائمة بنمط C# حيث تُعتبر قيمة NaNين متساوية على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | يُرجع الخط المستخدم في حالة عدم العثور على الخط المصدر. يقرأ [System::String](../../system/string/). |
| virtual **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() | علامة منطقية تشير إلى ما إذا كانت الأجزاء المقصوصة تبقى جزءًا من المستند. إذا كانت true تُحذف الأجزاء المقصوصة، وإذا كانت false تُسلسل في المستند (ما قد يؤدي إلى ملف أكبر) قراءة **bool**. |
| virtual **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() | يحصل على قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. عندما تُعيّن إلى **true**، تُعطَّل الأحرف المتصلة في الناتج المعروض. بشكل افتراضي، تُعيّن الخاصية إلى **false**. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | يُرجع النمط البصري للتدرج. يقرأ [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHtmlFormatter](../ihtmlformatter/)\> [get_HtmlFormatter](./get_htmlformatter/)() | يُرجع قالب HTML. يقرأ [IHtmlFormatter](../ihtmlformatter/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | يوفر خيارات تتحكم في مظهر كائنات [Ink](../../aspose.slides.ink/) في المستند المُصدّر. للقراءة فقط [IInkOptions](../iinkoptions/) |
| virtual **uint8_t** [get_JpegQuality](./get_jpegquality/)() | يُرجع قيمة تحدد جودة صور JPEG داخل مستند PDF. قراءة **uint8_t**. |
| virtual [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() | يمثل مستوى ضغط الصور. قراءة [PicturesCompression](../picturescompression/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | يمثل كائن استدعاء عكسي لحفظ تحديثات التقدم بالنسبة المئوية. انظر [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | يحدد ما إذا كان المستند المُنشأ يجب أن يتضمن الشرائح المخفية أم لا. القيمة الافتراضية **false**. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | يحدد ما إذا كان يجب تخطي الروابط التشعبية ذات استدعاءات JavaScript عند حفظ العرض. قراءة **bool**. القيمة الافتراضية **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlideImageFormat](../islideimageformat/)\> [get_SlideImageFormat](./get_slideimageformat/)() | يُرجع خيارات تنسيق صورة الشريحة. قراءة [ISlideImageFormat](../islideimageformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | يحصل على الوضع الذي تُوضَع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual **bool** [get_SvgResponsiveLayout](./get_svgresponsivelayout/)() | True لاستبعاد سمات العرض والارتفاع من حاوية SVG - سيجعل التخطيط استجابيًا. False بخلاف ذلك. قراءة **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | يُرجع كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو تُجهض. قراءة [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثيلًا للنوع الموصوف بواسطة targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويمكّن نسخ بناء الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويمكّن نسخ بناء الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | يضبط الخط المستخدم في حالة عدم العثور على الخط المصدر. يكتب [System::String](../../system/string/). |
| virtual void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) | علامة منطقية تشير إلى ما إذا كانت الأجزاء المقصوصة تبقى جزءًا من المستند. إذا كانت true تُحذف الأجزاء المقصوصة، وإذا كانت false تُسلسل في المستند (ما قد يؤدي إلى ملف أكبر) كتابة **bool**. |
| virtual void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. عندما تُعيّن إلى **true**، تُعطَّل الأحرف المتصلة في الناتج المعروض. بشكل افتراضي، تُعيّن الخاصية إلى **false**. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | يضبط النمط البصري للتدرج. كتابة [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_HtmlFormatter](./set_htmlformatter/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlFormatter](../ihtmlformatter/)\>) | يضبط قالب HTML. كتابة [IHtmlFormatter](../ihtmlformatter/). |
| virtual void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) | يضبط قيمة تحدد جودة صور JPEG داخل مستند PDF. كتابة **uint8_t**. |
| virtual void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) | يمثل مستوى ضغط الصور. كتابة [PicturesCompression](../picturescompression/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | يمثل كائن استدعاء عكسي لحفظ تحديثات التقدم بالنسبة المئوية. انظر [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | يحدد ما إذا كان المستند المُنشأ يجب أن يتضمن الشرائح المخفية أم لا. القيمة الافتراضية **false**. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | يحدد ما إذا كان يجب تخطي الروابط التشعبية ذات استدعاءات JavaScript عند حفظ العرض. كتابة **bool**. القيمة الافتراضية **false**. |
| virtual void [set_SlideImageFormat](./set_slideimageformat/)([System::SharedPtr](../../system/sharedptr/)\<[ISlideImageFormat](../islideimageformat/)\>) | يضبط خيارات تنسيق صورة الشريحة. كتابة [ISlideImageFormat](../islideimageformat/). |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | يضبط الوضع الذي تُوضَع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual void [set_SvgResponsiveLayout](./set_svgresponsivelayout/)(**bool**) | True لاستبعاد سمات العرض والارتفاع من حاوية SVG - سيجعل التخطيط استجابيًا. False بخلاف ذلك. كتابة **bool**. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | يضبط كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو تُجهض. كتابة [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النوني للقالب ليكون مؤشرًا ضعيفًا (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عداد المرجع المشترك ويُعيده. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## راجع أيضًا

* الفئة [ISaveOptions](../isaveoptions/)
* مساحة الاسم [Aspose::Slides::Export](../)
* المكتبة [Aspose.Slides](../../)