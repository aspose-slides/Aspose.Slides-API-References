---
title: IPdfOptions
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يوفر خيارات تتحكم في كيفية حفظ العرض التقديمي بصيغة Pdf.
type: docs
weight: 274
url: /ar/aspose.slides.export/ipdfoptions/
---
## IPdfOptions فئة

يوفر خيارات تتحكم في كيفية حفظ العرض التقديمي بصيغة Pdf.

```cpp
class IPdfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## الطرق

| طريقة | وصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | محاكاة مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNين متساويين بالرغم من أن معيار IEC 60559:1989 ينص على أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | محاكاة مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNين متساويين بالرغم من أن معيار IEC 60559:1989 ينص على أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() | يتضمن مجموعة من العلامات التي تحدد أي أذونات وصول ينبغي منحها عند فتح المستند بوصول المستخدم. انظر [PdfAccessPermissions](../pdfaccesspermissions/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() | يعيد مصفوفة من أسماء عائلات الخطوط المعرفة من قبل المستخدم والتي يجب على [Aspose.Slides](../../aspose.slides/) اعتبارها شائعة. اقرأ [System::String](../../system/string/)[]. |
| virtual **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() | يطبق اللون الشفاف المحدد على صورة إذا كان **true**. |
| virtual **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() | يشير ما إذا كان يجب اختيار ضغط أكثر فاعلية (بدلاً من الافتراضي) لكل صورة تلقائيًا. إذا تم تعيينه إلى **bool**.true، سيُختار الخوارزمية الأنسب لكل صورة في العرض التقديمي، ما يؤدي إلى حجم أصغر لمستند PDF الناتج. |
| virtual [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() | المستوى المطلوب للامتثال لمستند PDF المُولد. اقرأ [PdfCompliance](../pdfcompliance/). |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | يعيد الخط المستخدم في حال عدم العثور على الخط المصدر. اقرأ [System::String](../../system/string/). |
| virtual **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() | صحيح لرسم إطار أسود حول كل شريحة. اقرأ **bool**. |
| virtual **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() | يحدد ما إذا يجب تضمين جميع حروف الخط أو مجموعة فرعية فقط. اقرأ **bool**. |
| virtual **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() | صحيح لتضمين خطوط true type للأحرف ASCII من 32 إلى 127. [Fonts](../../aspose.slides/fonts/) للأكواد التي تزيد عن 127 يتم تضمينها دائمًا. اقرأ **bool**. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | يعيد نمط التدرج البصري. اقرأ [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() | يحصل على لون الصورة الشفاف. |
| virtual **bool** [get_IncludeOleData](./get_includeoledata/)() | صحيح لتحويل جميع بيانات OLE من العرض التقديمي إلى ملفات مضمَّنة في PDF الناتج. اقرأ **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | يوفر خيارات تتحكم في مظهر كائنات [Ink](../../aspose.slides.ink/) في المستند المُصدّر. للقراءة فقط [IInkOptions](../iinkoptions/) |
| virtual **uint8_t** [get_JpegQuality](./get_jpegquality/)() | يعيد قيمة تحدد جودة صور JPEG داخل مستند PDF. اقرأ **uint8_t**. |
| virtual [System::String](../../system/string/) [get_Password](./get_password/)() | إعداد كلمة مرور المستخدم لحماية مستند PDF. اقرأ [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | يمثل كائن استدعاء للرجوع لتحديثات حفظ التقدم بالنسبة المئوية. انظر [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() | يشير ما إذا يجب تحويل النص إلى نقطية وحفظه كصورة في PDF عندما لا يدعم الخط نمط بولد. يمكن لهذا النهج تحسين جودة النص في PDF الناتج لبعض الخطوط. اقرأ **bool**. |
| virtual **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() | صحيح لتحويل جميع ملفات الميتا المستخدمة في العرض إلى صور PNG. اقرأ **bool**. |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | يحدد ما إذا كان المستند المُولد يجب أن يتضمن شرائح مخفية أم لا. القيمة الافتراضية هي **false**. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | يحدد ما إذا يجب تخطي الروابط مع استدعاءات JavaScript عند حفظ العرض. اقرأ **bool**. القيمة الافتراضية هي **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | يحصل على الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual **float** [get_SufficientResolution](./get_sufficientresolution/)() | يعيد قيمة تحدد دقة الصور داخل مستند PDF. |
| virtual [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() | يحدد نوع الضغط الذي سيُستخدم لجميع المحتويات النصية في المستند. اقرأ [PdfTextCompression](../pdftextcompression/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | يعيد كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أم ستُوقف. اقرأ [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يسمح بتجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يسمح بنسخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) | يتضمن مجموعة من العلامات التي تحدد أي أذونات وصول يجب منحها عند فتح المستند بوصول المستخدم. انظر [PdfAccessPermissions](../pdfaccesspermissions/). |
| virtual void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) | يضبط مصفوفة من أسماء عائلات الخطوط المعرفة من قبل المستخدم التي يجب على [Aspose.Slides](../../aspose.slides/) اعتبارها شائعة. اكتب [System::String](../../system/string/)[]. |
| virtual void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) | يطبق اللون الشفاف المحدد على صورة إذا كان **true**. |
| virtual void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) | يشير ما إذا كان يجب اختيار ضغط أكثر فاعلية (بدلاً من الافتراضي) لكل صورة تلقائيًا. إذا تم تعيينه إلى **bool**.true، سيُختار الخوارزمية الأنسب لكل صورة في العرض التقديمي، ما يؤدي إلى حجم أصغر لمستند PDF الناتج. |
| virtual void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) | المستوى المطلوب للامتثال لمستند PDF المُولد. اكتب [PdfCompliance](../pdfcompliance/). |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | يضبط الخط المستخدم في حالة عدم العثور على الخط المصدر. يكتب [System::String](../../system/string/). |
| virtual void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) | صحيح لرسم إطار أسود حول كل شريحة. اكتب **bool**. |
| virtual void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) | يحدد ما إذا يجب تضمين جميع حروف الخط أو مجموعة فرعية فقط. اكتب **bool**. |
| virtual void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) | صحيح لتضمين خطوط true type للأحرف ASCII من 32 إلى 127. [Fonts](../../aspose.slides/fonts/) للأكواد التي تزيد عن 127 يتم تضمينها دائمًا. اكتب **bool**. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | يضبط النمط البصري للتدرج. اكتب [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) | يضبط لون الصورة الشفاف. |
| virtual void [set_IncludeOleData](./set_includeoledata/)(**bool**) | صحيح لتحويل جميع بيانات OLE من العرض إلى ملفات مضمَّنة في PDF الناتج. اكتب **bool**. |
| virtual void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) | يضبط قيمة تحدد جودة صور JPEG داخل مستند PDF. اكتب **uint8_t**. |
| virtual void [set_Password](./set_password/)([System::String](../../system/string/)) | إعداد كلمة مرور المستخدم لحماية مستند PDF. اكتب [System::String](../../system/string/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | يمثل كائن استدعاء للرجوع لتحديثات حفظ التقدم بالنسبة المئوية. انظر [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) | يشير ما إذا يجب تحويل النص إلى نقطية وحفظه كصورة في PDF عندما لا يدعم الخط نمط بولد. يمكن لهذا النهج تحسين جودة النص في PDF الناتج لبعض الخطوط. اكتب **bool**. |
| virtual void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) | صحيح لتحويل جميع ملفات الميتا المستخدمة في العرض إلى صور PNG. اكتب **bool**. |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | يحدد ما إذا كان المستند المُولد يجب أن يتضمن شرائح مخفية أم لا. القيمة الافتراضية هي **false**. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | يحدد ما إذا يجب تخطي الروابط التي تحتوي على استدعاءات JavaScript عند حفظ العرض. اكتب **bool**. القيمة الافتراضية هي **false**. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | يضبط الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual void [set_SufficientResolution](./set_sufficientresolution/)(**float**) | يضبط قيمة تحدد دقة الصور داخل مستند PDF. |
| virtual void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) | يحدد نوع الضغط الذي سيُستخدم لجميع المحتويات النصية في المستند. اكتب [PdfTextCompression](../pdftextcompression/). |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | يضبط كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أم ستُوقف. اكتب [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط معامل القالب الـ n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتبديل الإشارات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يسمح بتحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ تعبير C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## انظر أيضاً

* فئة [ISaveOptions](../isaveoptions/)
* نطاق الاسم [Aspose::Slides::Export](../)
* مكتبة [Aspose.Slides](../../)