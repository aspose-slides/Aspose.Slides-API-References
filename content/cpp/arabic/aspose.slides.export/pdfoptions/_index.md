---
title: PdfOptions
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يوفر خيارات تتحكم في كيفية حفظ العرض التقديمي بتنسيق PDF.
type: docs
weight: 573
url: /ar/aspose.slides.export/pdfoptions/
---
## فئة PdfOptions

Provides options that control how a presentation is saved in Pdf format.

```cpp
class PdfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::IPdfOptions
```

## Methods

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تعتبر قيمتا NaN متساويتين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تعتبر قيمتا NaN متساويتين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للغرض الداخلي فقط. |
| [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() override | يتضمن مجموعة من العلامات التي تحدد أي أذونات وصول يجب منحها عند فتح المستند بصلاحيات المستخدم. راجع [PdfAccessPermissions](../pdfaccesspermissions/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() override | يرجع مصفوفة من الأسماء المعرفة من قبل المستخدم لعائلات الخطوط التي يجب على [Aspose.Slides](../../aspose.slides/) اعتبارها شائعة. اقرأ [System::String](../../system/string/)[]. |
| **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() override | يطبق اللون الشفاف المحدد على الصورة إذا كان **true**. |
| **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() override | يشير إلى ما إذا كان يجب اختيار أكثر ضغط فعّال (بدلاً من الضغط الافتراضي) لكل صورة تلقائيًا. إذا تم تعيينه إلى **bool**.true، سيتم اختيار الخوارزمية الأنسب للضغط لكل صورة في العرض، مما يؤدي إلى تقليل حجم ملف PDF الناتج. |
| [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() override | مستوى التوافق المطلوب للمستند PDF المولّد. اقرأ [PdfCompliance](../pdfcompliance/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | يرجع الخط المستخدم في حال عدم العثور على الخط المصدر. اقرأ [System::String](../../system/string/). |
| **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() override | صحيح لرسم إطار أسود حول كل شريحة. اقرأ **bool**. |
| **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() override | يحدد ما إذا كان يجب تضمين جميع أحرف الخط أو مجرد جزء مستخدم. اقرأ **bool**. |
| **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() override | يحدد ما إذا كان [Aspose.Slides](../../aspose.slides/) سيضمّن الخطوط الشائعة لنص ASCII (نطاق الرموز 33..127). [Fonts](../../aspose.slides/fonts/) للرموز التي تتجاوز 127 يتم تضمينها دائمًا. تشمل قائمة الخطوط الشائعة الخطوط الأساسية الـ14 لملف PDF وخطوطًا إضافية محددة من قبل المستخدم. اقرأ **bool**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | يرجع النمط البصري للتدرج. اقرأ [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() override | يحصل على لون الشفافية للصورة. |
| **bool** [get_IncludeOleData](./get_includeoledata/)() override | صحيح لتحويل جميع بيانات OLE من العرض إلى ملفات مضمّنة في ملف PDF الناتج. اقرأ **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | يوفر خيارات تتحكم في مظهر كائنات [Ink](../../aspose.slides.ink/) في المستند المُصدَّر. قراءة فقط [IInkOptions](../iinkoptions/) |
| **uint8_t** [get_JpegQuality](./get_jpegquality/)() override | يرجع قيمة تحدد جودة صور JPEG داخل مستند PDF. اقرأ **uint8_t**. |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | تعيين كلمة مرور المستخدم لحماية مستند PDF. اقرأ [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | يمثل كائن استدعاء رجعي لتحديثات حفظ التقدم كنسبة مئوية. راجع [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() override | يشير إلى ما إذا كان يجب تحويل النص إلى صورة نقطية وحفظه في PDF عندما لا يدعم الخط نمط الغامق. يمكن لهذا الأسلوب تحسين جودة النص في PDF الناتج لبعض الخطوط. اقرأ **bool**. |
| **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() override | صحيح لتحويل جميع ملفات الميتا المستخدمة في العرض إلى صور PNG. اقرأ **bool**. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | يحدد ما إذا كان المستند المولّد يجب أن يتضمن شرائح مخفية أم لا. القيمة الافتراضية هي **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | يحدد ما إذا كان يجب تخطي الروابط التشعبية التي تستدعي JavaScript عند حفظ العرض. اقرأ **bool**. القيمة الافتراضية هي **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | يحصل على الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض [ISlidesLayoutOptions](../islideslayoutoptions/). |
| **float** [get_SufficientResolution](./get_sufficientresolution/)() override | يرجع قيمة تحدد دقة الصور داخل مستند PDF. |
| [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() override | يحدد نوع الضغط المستخدم لجميع المحتويات النصية في المستند. اقرأ [PdfTextCompression](../pdftextcompression/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | يُعيد أو يحدد كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أم ستُ aborted. اقرأ [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد الإشارات المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تناظر طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يمكّن التجزئة للكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر نداء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل مثيلًا للنوع الموصوف بـ targetType. تناظر عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل تعليمة C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يمكّن استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
|  [PdfOptions](./pdfoptions/)() | منشئ افتراضي. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) override | يتضمن مجموعة من العلامات التي تحدد أي أذونات وصول يجب منحها عند فتح المستند بصلاحيات المستخدم. راجع [PdfAccessPermissions](../pdfaccesspermissions/). |
| void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) override | يضبط مصفوفة من الأسماء المعرفة من قبل المستخدم لعائلات الخطوط التي يجب على [Aspose.Slides](../../aspose.slides/) اعتبارها شائعة. اكتب [System::String](../../system/string/)[]. |
| void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) override | يطبق اللون الشفاف المحدد على الصورة إذا كان **true**. |
| void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) override | يشير إلى ما إذا كان يجب اختيار أكثر ضغط فعّال (بدلاً من الضغط الافتراضي) لكل صورة تلقائيًا. إذا تم تعيينه إلى **bool**.true، سيتم اختيار الخوارزمية الأنسب للضغط لكل صورة في العرض، مما يؤدي إلى تقليل حجم ملف PDF الناتج. |
| void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) override | مستوى التوافق المطلوب للمستند PDF المولّد. اكتب [PdfCompliance](../pdfcompliance/). |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | يضبط الخط المستخدم في حال عدم العثور على الخط المصدر. يكتب [System::String](../../system/string/). |
| void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) override | صحيح لرسم إطار أسود حول كل شريحة. اكتب **bool**. |
| void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) override | يحدد ما إذا كان يجب تضمين جميع أحرف الخط أو مجرد جزء مستخدم. اكتب **bool**. |
| void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) override | يحدد ما إذا كان [Aspose.Slides](../../aspose.slides/) سيضمّن الخطوط الشائعة لنص ASCII (نطاق الرموز 33..127). [Fonts](../../aspose.slides/fonts/) للرموز التي تتجاوز 127 يتم تضمينها دائمًا. تشمل قائمة الخطوط الشائعة الخطوط الأساسية الـ14 لملف PDF وخطوطًا إضافية محددة من قبل المستخدم. اكتب **bool**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | يضبط النمط البصري للتدرج. اكتب [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) override | يضبط لون الشفافية للصورة. |
| void [set_IncludeOleData](./set_includeoledata/)(**bool**) override | صحيح لتحويل جميع بيانات OLE من العرض إلى ملفات مضمّنة في ملف PDF الناتج. اكتب **bool**. |
| void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) override | يضبط قيمة تحدد جودة صور JPEG داخل مستند PDF. اكتب **uint8_t**. |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | تعيين كلمة مرور المستخدم لحماية مستند PDF. اكتب [System::String](../../system/string/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | يمثل كائن استدعاء رجعي لتحديثات حفظ التقدم كنسبة مئوية. راجع [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) override | يشير إلى ما إذا كان يجب تحويل النص إلى صورة نقطية وحفظه في PDF عندما لا يدعم الخط نمط الغامق. يمكن لهذا الأسلوب تحسين جودة النص في PDF الناتج لبعض الخطوط. اكتب **bool**. |
| void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) override | صحيح لتحويل جميع ملفات الميتا المستخدمة في العرض إلى صور PNG. اكتب **bool**. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | يحدد ما إذا كان المستند المولّد يجب أن يتضمن شرائح مخفية أم لا. القيمة الافتراضية هي **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | يحدد ما إذا كان يجب تخطي الروابط التشعبية التي تستدعي JavaScript عند حفظ العرض. اكتب **bool**. القيمة الافتراضية هي **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | يضبط الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض [ISlidesLayoutOptions](../islideslayoutoptions/). |
| void [set_SufficientResolution](./set_sufficientresolution/)(**float**) override | يضبط قيمة تحدد دقة الصور داخل مستند PDF. |
| void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) override | يحدد نوع الضغط المستخدم لجميع المحتويات النصية في المستند. اكتب [PdfTextCompression](../pdftextcompression/). |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | يُعيد أو يحدد كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أم ستُ aborted. اكتب [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعود بعداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تناظر طريقة C# [Object.ToString()](../../system/object/tostring/). يمكّن تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ قفل تعليمة C# lock() إلغاء القفل. استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## ملاحظات

المثال التالي يوضح كيفية تحويل PowerPoint إلى PDF مع خيارات مخصصة.
```cpp
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// ينشئ فئة PdfOptions
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// يحدد جودة Jpeg
pdfOptions->set_JpegQuality(90);
// يحدد سلوك ملفات الميتافايل
pdfOptions->set_SaveMetafilesAsPng(true);
// يحدد مستوى ضغط النص
pdfOptions->set_TextCompression(PdfTextCompression::Flate);
// يحدد معيار PDF
pdfOptions->set_Compliance(PdfCompliance::Pdf15);
// يحفظ العرض التقديمي كملف PDF
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
المثال التالي يوضح كيفية تحويل PowerPoint إلى PDF مع الشرائح المخفية.
```cpp
// ينشئ فئة Presentation التي تمثل ملف PowerPoint
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// ينشئ فئة PdfOptions
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// يضيف الشرائح المخفية
pdfOptions->set_ShowHiddenSlides(true);
// يحفظ العرض التقديمي كملف PDF
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
المثال التالي يوضح كيفية تحويل PowerPoint إلى PDF محمي بكلمة مرور.
```cpp
// ينشئ كائن Presentation الذي يمثل ملف PowerPoint
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();

// يحدد كلمة مرور PDF وأذونات الوصول
pdfOptions->set_Password(u"password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
// يحفظ العرض التقديمي كملف PDF
presentation->Save(u"PPTX-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
المثال التالي يوضح كيفية تحويل PowerPoint إلى PDF مع الملاحظات.
```cpp
// إنشاء كائن Presentation يمثل ملف عرض تقديمي
auto presentation = System::MakeObject<Presentation>(u"SelectedSlides.pptx");

auto auxPresentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auxPresentation->get_Slides()->InsertClone(0, slide);

// Setting Slide Type and Size
auxPresentation->get_SlideSize()->SetSize(612.F, 792.F, SlideSizeScaleType::EnsureFit);

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
pdfOptions->set_SlidesLayoutOptions(slidesLayoutOptions);
auxPresentation->Save(u"PDFnotes_out.pdf", SaveFormat::Pdf, pdfOptions);
```

## أنظر أيضًا

* الفئة [SaveOptions](../saveoptions/)
* الفئة [IPdfOptions](../ipdfoptions/)
* النطاق [Aspose::Slides::Export](../)
* المكتبة [Aspose.Slides](../../)