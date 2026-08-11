---
title: ITiffOptions
second_title: Aspose.Slides لمرجع API C++
description: يوفر خيارات تتحكم في كيفية حفظ عرض تقديمي بصيغة TIFF.
type: docs
weight: 495
url: /ar/aspose.slides.export/itiffoptions/
---
## ITiffOptions فئة

يوفر خيارات تتحكم في كيفية حفظ عرض تقديمي بصيغة TIFF.

```cpp
class ITiffOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## الأساليب

| طريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة أعداد ذات نقطة عائمة بأسلوب C# حيث يُعتبر NaNانان متساويين على الرغم من أن معيار IEC 60559:1989 يوضح أن NaN غير متساوٍ مع أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة أعداد ذات نقطة عائمة بأسلوب C# حيث يُعتبر NaNانان متساويين على الرغم من أن معيار IEC 60559:1989 يوضح أن NaN غير متساوٍ مع أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| virtual [BlackWhiteConversionMode](../blackwhiteconversionmode/) [get_BwConversionMode](./get_bwconversionmode/)() | يحدد الخوارزمية لتحويل صورة ملونة إلى صورة أبيض وأسود. سيتم تطبيق هذا الخيار فقط إذا تم تعيين [ITiffOptions::get_CompressionType()](./get_compressiontype/) إلى [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) أو [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/). قراءة [BlackWhiteConversionMode](../blackwhiteconversionmode/). القيمة الافتراضية هي [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/). |
| virtual [TiffCompressionTypes](../tiffcompressiontypes/) [get_CompressionType](./get_compressiontype/)() | يحدد نوع الضغط. قراءة [TiffCompressionTypes](../tiffcompressiontypes/). |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | يُعيد الخط المستخدم في حال عدم العثور على الخط الأصلي. قراءة [System::String](../../system/string/). |
| virtual **uint32_t** [get_DpiX](./get_dpix/)() | يحدد الدقة الأفقية بوحدة النقاط في البوصة. قراءة **uint32_t**. |
| virtual **uint32_t** [get_DpiY](./get_dpiy/)() | يحدد الدقة الرأسية بوحدة النقاط في البوصة. قراءة **uint32_t**. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | يُعيد النمط البصري للتدرج. قراءة [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual [System::Drawing::Size](../../system.drawing/size/) [get_ImageSize](./get_imagesize/)() | يحدد حجم صورة TIFF المُنشأة. القيمة الافتراضية هي 0x0، مما يعني أن أحجام الصور المُنشأة ستحسب بناءً على قيمة حجم شريحة العرض التقديمي. قراءة [System::Drawing::Size](../../system.drawing/size/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | يوفر خيارات تتحكم في مظهر كائنات [Ink](../../aspose.slides.ink/) في المستند المُصدّر. قراءة فقط [IInkOptions](../iinkoptions/) |
| virtual [ImagePixelFormat](../imagepixelformat/) [get_PixelFormat](./get_pixelformat/)() | يحدد تنسيق البكسل للصور المُنشأة. قراءة [ImagePixelFormat](../imagepixelformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | يمثل كائن استدعاء للعودة لتحديثات حفظ التقدم بالنسبة المئوية. انظر [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | يحدد ما إذا كان المستند المُنشأ يجب أن يتضمن شرائح مخفية أم لا. القيمة الافتراضية هي **false**. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | يحدد ما إذا كان يجب تخطي الروابط التشعبية التي تحتوي على استدعاءات JavaScript عند حفظ العرض التقديمي. قراءة **bool**. القيمة الافتراضية هي **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | يحصل على الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | يُعيد كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أم ستُلغى. قراءة [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجعية المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح إنشاء تجزئة للكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. نظير مشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ كل بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجعية مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجعية المشتركة بالقيمة المحددة. |
| virtual void [set_BwConversionMode](./set_bwconversionmode/)([BlackWhiteConversionMode](../blackwhiteconversionmode/)) | يحدد الخوارزمية لتحويل صورة ملونة إلى صورة أبيض وأسود. سيتم تطبيق هذا الخيار فقط إذا تم تعيين [ITiffOptions::get_CompressionType()](./get_compressiontype/) إلى [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) أو [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/). كتابة [BlackWhiteConversionMode](../blackwhiteconversionmode/). القيمة الافتراضية هي [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/). |
| virtual void [set_CompressionType](./set_compressiontype/)([TiffCompressionTypes](../tiffcompressiontypes/)) | يحدد نوع الضغط. كتابة [TiffCompressionTypes](../tiffcompressiontypes/). |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | يضبط الخط المستخدم في حال عدم العثور على الخط الأصلي. كتابة [System::String](../../system/string/). |
| virtual void [set_DpiX](./set_dpix/)(**uint32_t**) | يحدد الدقة الأفقية بوحدة النقاط في البوصة. كتابة **uint32_t**. |
| virtual void [set_DpiY](./set_dpiy/)(**uint32_t**) | يحدد الدقة الرأسية بوحدة النقاط في البوصة. كتابة **uint32_t**. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | يضبط النمط البصري للتدرج. كتابة [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_ImageSize](./set_imagesize/)([System::Drawing::Size](../../system.drawing/size/)) | يحدد حجم صورة TIFF المُنشأة. القيمة الافتراضية هي 0x0، مما يعني أن أحجام الصور المُنشأة ستحسب بناءً على قيمة حجم شريحة العرض التقديمي. كتابة [System::Drawing::Size](../../system.drawing/size/). |
| virtual void [set_PixelFormat](./set_pixelformat/)([ImagePixelFormat](../imagepixelformat/)) | يحدد تنسيق البكسل للصور المُنشأة. كتابة [ImagePixelFormat](../imagepixelformat/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | يمثل كائن استدعاء للعودة لتحديثات حفظ التقدم بالنسبة المئوية. انظر [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | يحدد ما إذا كان المستند المُنشأ يجب أن يتضمن شرائح مخفية أم لا. القيمة الافتراضية هي **false**. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | يحدد ما إذا كان يجب تخطي الروابط التشعبية ذات استدعاءات JavaScript عند حفظ العرض التقديمي. كتابة **bool**. القيمة الافتراضية هي **false**. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | يضبط الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | يضبط كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أم ستُلغى. كتابة [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n't كإشارة ضعيفة (بدلاً من المشاركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع الضعف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجعية المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجعية المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويُعيد عداد المرجعية المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجعية الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجعية الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* فئة [ISaveOptions](../isaveoptions/)
* مساحة الأسماء [Aspose::Slides::Export](../)
* مكتبة [Aspose.Slides](../../)