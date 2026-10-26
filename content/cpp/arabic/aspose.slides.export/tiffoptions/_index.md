---
title: TiffOptions
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يوفر خيارات تتحكم في كيفية حفظ العرض التقديمي بتنسيق TIFF.
type: docs
weight: 768
url: /ar/aspose.slides.export/tiffoptions/
---
## فئة TiffOptions

يوفر خيارات تتحكم في كيفية حفظ العرض التقديمي بتنسيق TIFF.

```cpp
class TiffOptions : public Aspose::Slides::Export::SaveOptions,
                    public Aspose::Slides::Export::ITiffOptions
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaN-انان متساويتين رغم أن IEC 60559:1989 تنص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaN-انان متساويتين رغم أن IEC 60559:1989 تنص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [BlackWhiteConversionMode](../blackwhiteconversionmode/) [get_BwConversionMode](./get_bwconversionmode/)() override | يحدد الخوارزمية لتحويل صورة ملونة إلى صورة أبيض وأسود. سيُطبق هذا الخيار فقط إذا كان [ITiffOptions::get_CompressionType()](../itiffoptions/get_compressiontype/) مُعينًا إلى [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) أو [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) قراءة [BlackWhiteConversionMode](../blackwhiteconversionmode/). القيمة الافتراضية هي [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/). |
| [TiffCompressionTypes](../tiffcompressiontypes/) [get_CompressionType](./get_compressiontype/)() override | يحدد نوع الضغط. قراءة [TiffCompressionTypes](../tiffcompressiontypes/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | يرجع الخط المستخدم في حالة عدم العثور على الخط المصدر. قراءة [System::String](../../system/string/). |
| **uint32_t** [get_DpiX](./get_dpix/)() override | يحدد الدقة الأفقية بالنقطة في البوصة. قراءة **uint32_t**. |
| **uint32_t** [get_DpiY](./get_dpiy/)() override | يحدد الدقة العمودية بالنقطة في البوصة. قراءة **uint32_t**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | يرجع النمط البصري للتدرج. قراءة [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::Drawing::Size](../../system.drawing/size/) [get_ImageSize](./get_imagesize/)() override | يحدد حجم صورة TIFF المُولَّدة. القيمة الافتراضية هي 0x0، مما يعني أن أحجام الصور المُولَّدة سُتحسب بناءً على قيمة حجم شريحة العرض التقديمي. قراءة [System::Drawing::Size](../../system.drawing/size/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | يوفر خيارات تتحكم في مظهر كائنات [Ink](../../aspose.slides.ink/) في المستند المُصدَّر. قراءة-فقط [IInkOptions](../iinkoptions/) |
| [ImagePixelFormat](../imagepixelformat/) [get_PixelFormat](./get_pixelformat/)() override | يحدد تنسيق البكسل للصور المُولَّدة. قراءة [ImagePixelFormat](../imagepixelformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | يمثل كائن رد نداء لتحديثات حفظ النسبة المئوية. انظر [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | يحدد ما إذا كان المستند المُولَّد يجب أن يتضمن الشرائح المخفية أم لا. القيمة الافتراضية هي **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | يحدد ما إذا كان يجب تخطي الروابط التشعبية ذات استدعاءات JavaScript عند حفظ العرض التقديمي. قراءة **bool**. القيمة الافتراضية هي **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | يحصل على الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير العرض التقديمي [ISlidesLayoutOptions](../islideslayoutoptions/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | يرجع أو يضبط كائن يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو ستُوقف. قراءة [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصَّصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل نداء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. تماثل عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ بيان القفل C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصَّصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | مُنشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويمكّن بناء نسخ الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويمكّن بناء نسخ الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بواسطة المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بواسطة المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_BwConversionMode](./set_bwconversionmode/)([BlackWhiteConversionMode](../blackwhiteconversionmode/)) override | يحدد الخوارزمية لتحويل صورة ملونة إلى صورة أبيض وأسود. سيُطبق هذا الخيار فقط إذا كان [ITiffOptions::get_CompressionType()](../itiffoptions/get_compressiontype/) مُعينًا إلى [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) أو [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) كتابة [BlackWhiteConversionMode](../blackwhiteconversionmode/). القيمة الافتراضية هي [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/). |
| void [set_CompressionType](./set_compressiontype/)([TiffCompressionTypes](../tiffcompressiontypes/)) override | يحدد نوع الضغط. كتابة [TiffCompressionTypes](../tiffcompressiontypes/). |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | يضبط الخط المستخدم في حالة عدم العثور على الخط المصدر. كتابة [System::String](../../system/string/). |
| void [set_DpiX](./set_dpix/)(**uint32_t**) override | يحدد الدقة الأفقية بالنقطة في البوصة. كتابة **uint32_t**. |
| void [set_DpiY](./set_dpiy/)(**uint32_t**) override | يحدد الدقة العمودية بالنقطة في البوصة. كتابة **uint32_t**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | يضبط النمط البصري للتدرج. كتابة [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ImageSize](./set_imagesize/)([System::Drawing::Size](../../system.drawing/size/)) override | يحدد حجم صورة TIFF المُولَّدة. القيمة الافتراضية هي 0x0، مما يعني أن أحجام الصور المُولَّدة سُتحسب بناءً على قيمة حجم شريحة العرض التقديمي. كتابة [System::Drawing::Size](../../system.drawing/size/). |
| void [set_PixelFormat](./set_pixelformat/)([ImagePixelFormat](../imagepixelformat/)) override | يحدد تنسيق البكسل للصور المُولَّدة. كتابة [ImagePixelFormat](../imagepixelformat/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | يمثل كائن رد نداء لتحديثات حفظ النسبة المئوية. انظر [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | يحدد ما إذا كان المستند المُولَّد يجب أن يتضمن الشرائح المخفية أم لا. القيمة الافتراضية هي **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | يحدد ما إذا كان يجب تخطي الروابط التشعبية ذات استدعاءات JavaScript عند حفظ العرض التقديمي. كتابة **bool**. القيمة الافتراضية هي **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | يضبط الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير العرض التقديمي [ISlidesLayoutOptions](../islideslayoutoptions/). |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | يرجع أو يضبط كائن يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو ستُوقف. كتابة [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n إلى مؤشر ضعيف (بدلاً من المشترك). يتيح تحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عداد المرجع المشترك ويُعيده. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
|  [TiffOptions](./tiffoptions/)() | مُنشئ افتراضي. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصَّصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ فك القفل C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## ملاحظات

يوضح المثال التالي كيفية تحويل PowerPoint إلى TIFF بالحجم الافتراضي.  
```cpp
// إنشاء كائن Presentation يمثل ملف عرض تقديمي
auto presentation = System::MakeObject<Presentation>(u"DemoFile.pptx");

// حفظ العرض التقديمي إلى مستند TIFF
presentation->Save(u"Tiffoutput_out.tiff", SaveFormat::Tiff);
``` المثال التالي يظهر كيفية تحويل PowerPoint إلى TIFF بحجم مخصص.  
```cpp
// إنشاء كائن Presentation يمثل ملف عرض تقديمي
auto pres = System::MakeObject<Presentation>(u"Convert_Tiff_Custom.pptx");

// إنشاء كائن من فئة TiffOptions
System::SharedPtr<TiffOptions> opts = System::MakeObject<TiffOptions>();
// تعيين نوع الضغط
opts->set_CompressionType(TiffCompressionTypes::Default);

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
opts->set_SlidesLayoutOptions(slidesLayoutOptions);

// أنواع الضغط
// Default - يحدد مخطط الضغط الافتراضي (LZW).
// None - يحدد عدم وجود ضغط.
// CCITT3
// CCITT4
// LZW
// RLE
// العمق يعتمد على نوع الضغط ولا يمكن تحديده يدويًا.
// وحدة الدقة دائمًا تساوي "2" (نقطة في البوصة)
// تعيين DPI للصورة
opts->set_DpiX(200);
opts->set_DpiY(100);
// تعيين حجم الصورة
opts->set_ImageSize(System::Drawing::Size(1728, 1078));
// حفظ العرض التقديمي إلى TIFF بالحجم المحدد للصورة
pres->Save(u"TiffWithCustomSize_out.tiff", SaveFormat::Tiff, opts);
``` المثال التالي يظهر كيفية تحويل PowerPoint إلى TIFF بتنسيق بكسل صورة مخصص.  
```cpp
// إنشاء كائن Presentation يمثل ملف عرض تقديمي
auto presentation = System::MakeObject<Presentation>(u"DemoFile.pptx");

System::SharedPtr<TiffOptions> options = System::MakeObject<TiffOptions>();
options->set_PixelFormat(ImagePixelFormat::Format8bppIndexed);

// حفظ العرض التقديمي إلى TIFF بالحجم المحدد للصورة
presentation->Save(u"Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat::Tiff, options);
```

## انظر أيضًا

* الفئة [SaveOptions](../saveoptions/)
* الفئة [ITiffOptions](../itiffoptions/)
* مساحة الاسم [Aspose::Slides::Export](../)
* المكتبة [Aspose.Slides](../../)