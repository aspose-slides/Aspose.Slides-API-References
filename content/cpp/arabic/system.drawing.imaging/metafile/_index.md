---
title: Metafile
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يمثل ملفًا رسوميًا. يجب تخصيص كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيؤدي إلى أخطاء وقت تشغيل أو/و أخطاء تأكيد. دائمًا احطِ هذه الفئة بمؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كوسيطة."
type: docs
weight: 144
url: /ar/system.drawing.imaging/metafile/
---
## فئة Metafile


يمثل ملفًا رسوميًا. يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيؤدي إلى أخطاء وقت تشغيل و/أو أخطاء تأكيد. دائمًا احْطِ هذه الفئة بمؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيطة.

```cpp
class Metafile : public System::Drawing::Image
```

## الأساليب

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Image](../../system.drawing/image/)\> [Clone](./clone/)() override | يرجع نسخة من الكائن الحالي. |
| void [Dispose](../../system.drawing/image/dispose/)() override | يفرج جميع الموارد التي حصل عليها الكائن الحالي. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين رغم أن IEC 60559:1989 تنص على أن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين رغم أن IEC 60559:1989 تنص على أن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../../system.drawing/image/)\> [FromFile](../../system.drawing/image/fromfile/)(const [String](../../system/string/)\&, **bool**) | ينشئ كائن [Image](../../system.drawing/image/) من الملف المحدد. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](../../system.drawing/bitmap/)\> [FromHbitmap](../../system.drawing/image/fromhbitmap/)(IntPtr) | يبني كائن [Bitmap](../../system.drawing/bitmap/) من صورة GDI bitmap المحددة. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../../system.drawing/image/)\> [FromStream](../../system.drawing/image/fromstream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**, **bool**) | ينشئ كائن [Image](../../system.drawing/image/) من التدفق المحدد. |
| virtual **int32_t** [get_Flags](../../system.drawing/image/get_flags/)() const | يرجع مجموعة بتية من قيم تعداد ImageFlags التي تمثل خصائص الصورة. |
| [ArrayPtr](../../system/arrayptr/)\<[Guid](../../system/guid/)\> [get_FrameDimensionsList](../../system.drawing/image/get_framedimensionslist/)() const | يرجع مصفوفة من GUIDs التي تمثل أبعاد الإطارات داخل الصورة التي يمثلها الكائن الحالي. |
| int [get_Height](./get_height/)() const override | يرجع ارتفاعات الصورة بالبكسل. |
| **float** [get_HorizontalResolution](../../system.drawing/image/get_horizontalresolution/)() const | يرجع الدقة الأفقية للصورة التي يمثلها الكائن الحالي بوحدات بكسل لكل بوصة. |
| virtual [Imaging::ColorPalettePtr](../colorpaletteptr/) [get_Palette](../../system.drawing/image/get_palette/)() const | يرجع لوحة الألوان المستخدمة في الصورة التي يمثلها الكائن الحالي. |
| [Imaging::PixelFormat](../pixelformat/) [get_PixelFormat](./get_pixelformat/)() const override | يرجع قيمة تشير إلى تنسيق البكسل. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_PropertyIdList](../../system.drawing/image/get_propertyidlist/)() const | يحصل على معرفات عناصر الخصائص المخزنة في هذه الصورة. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Imaging::PropertyItem](../propertyitem/)\>\> [get_PropertyItems](../../system.drawing/image/get_propertyitems/)() const | يحصل على جميع عناصر الخصائص (قطع من البيانات الوصفية) المخزنة في هذه الصورة. |
| [Imaging::ImageFormatPtr](../imageformatptr/) [get_RawFormat](./get_rawformat/)() const override | يرجع قيمة تشير إلى تنسيق الصورة. |
| [Size](../../system.drawing/size/) [get_Size](../../system.drawing/image/get_size/)() const | يرجع كائن [Size](../../system.drawing/size/) يمثل عرض وارتفاع الصورة بالبكسل. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Tag](../../system.drawing/image/get_tag/)() const | يحصل على كائن يوفر بيانات إضافية حول الصورة. |
| **float** [get_VerticalResolution](../../system.drawing/image/get_verticalresolution/)() const | يرجع الدقة العمودية للصورة التي يمثلها الكائن الحالي بوحدات بكسل لكل بوصة. |
| int [get_Width](./get_width/)() const override | يرجع عرض الصورة بالبكسل. |
| [RectangleF](../../system.drawing/rectanglef/) [GetBounds](../../system.drawing/image/getbounds/)([GraphicsUnit](../../system.drawing/graphicsunit/)\&) | يرجع حدود الصورة بوحدات القياس المحددة. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجعات المرتبط بالكائن. |
| int [GetFrameCount](../../system.drawing/image/getframecount/)(const [Imaging::FrameDimensionPtr](../framedimensionptr/)\&) | يرجع عدد الإطارات للبعد الإطاري المحدد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| IntPtr [GetHenhmetafile](./gethenhmetafile/)() | غير مُنفَّذ. |
| [SharedPtr](../../system/sharedptr/)\<[MetafileHeader](../metafileheader/)\> [GetMetafileHeader](./getmetafileheader/)() | يرجع ترويسة مرتبطة بالكائن الحالي. |
| static int [GetPixelFormatSize](../../system.drawing/image/getpixelformatsize/)([Imaging::PixelFormat](../pixelformat/)) | يرجع عدد البتات المستخدمة لتمثيل عمق اللون في تنسيق البكسل المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../../system.drawing/image/)\> [GetThumbnailImage](../../system.drawing/image/getthumbnailimage/)(int, int, [Image::GetThumbnailImageAbort](../../system.drawing/image/getthumbnailimageabort/), IntPtr) | يحصل على صورة مصغرة لهذا الكائن [System::Drawing::Image](../../system.drawing/image/). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| static **bool** [IsAlphaPixelFormat](../../system.drawing/image/isalphapixelformat/)([Imaging::PixelFormat](../pixelformat/)) | يحدد ما إذا كان تنسيق البكسل المحدد يحتوي على معلومات ألفا. |
| virtual **bool** [IsMultiImage](../../system.drawing/image/ismultiimage/)() const | يرجع ما إذا كان التنسيق الأصلي متعدد الصور. |
| void [Lock](../../system/object/lock/)() | ينفذ عملية القفل لتصريح C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Metafile](./metafile/)(const [System::String](../../system/string/)\&) | غير مُنفَّذ. |
|  [Metafile](./metafile/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&) | غير مُنفَّذ. |
|  [Metafile](./metafile/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, IntPtr, [EmfType](../emftype/)) | غير مُنفَّذ. |
|  [Metafile](./metafile/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, IntPtr) | غير مُنفَّذ. |
|  [Metafile](./metafile/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, IntPtr, [Rectangle](../../system.drawing/rectangle/), [MetafileFrameUnit](../metafileframeunit/), [EmfType](../emftype/)) | غير مُنفَّذ. |
|  [Metafile](./metafile/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, IntPtr, [RectangleF](../../system.drawing/rectanglef/), [MetafileFrameUnit](../metafileframeunit/), [EmfType](../emftype/)) | غير مُنفَّذ. |
|  [Metafile](./metafile/)(IntPtr, [EmfType](../emftype/)) | غير مُنفَّذ. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويمكّن من إنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويمكّن من إنشاء نسخ من الفئات الفرعية. |
| void [PlayRecord](./playrecord/)([EmfPlusRecordType](../emfplusrecordtype/), **int32_t**, **int32_t**, [System::ByteArrayPtr](../../system/bytearrayptr/)) | غير مُنفَّذ. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجعية مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يخفض عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [RotateFlip](../../system.drawing/image/rotateflip/)([RotateFlipType](../../system.drawing/rotatefliptype/)) | يدور الصورة بزاوية مضاعفة للـ 90 درجة ويقلبها. |
| void [Save](../../system.drawing/image/save/)(const [String](../../system/string/)\&) | يحفظ الصورة التي يمثلها الكائن الحالي إلى الملف المحدد بتنسيق PNG. |
| void [Save](../../system.drawing/image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageFormatPtr](../imageformatptr/)\&) | يحفظ الصورة التي يمثلها الكائن الحالي إلى الملف المحدد بالتنسيق المحدد. |
| void [Save](../../system.drawing/image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageFormatPtr](../imageformatptr/)\&) | يحفظ الصورة التي يمثلها الكائن الحالي إلى التدفق المحدد بالتنسيق المحدد. |
| void [Save](../../system.drawing/image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageCodecInfoPtr](../imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../encoderparametersptr/)\&) | يحفظ الصورة التي يمثلها الكائن الحالي إلى الملف المحدد باستخدام المُرمّز المحدد ومعاملات المُرمّز. |
| void [Save](../../system.drawing/image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageCodecInfoPtr](../imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../encoderparametersptr/)\&) | يحفظ الصورة التي يمثلها الكائن الحالي إلى التدفق المحدد باستخدام المُرمّز المحدد ومعاملات المُرمّز. |
| void [SaveAdd](../../system.drawing/image/saveadd/)(const [Imaging::EncoderParametersPtr](../encoderparametersptr/)\&) | يضيف إطارًا إلى الملف أو التدفق المحدد في استدعاء سابق لطريقة [Save()](../../system.drawing/image/save/). |
| void [SaveAdd](../../system.drawing/image/saveadd/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../../system.drawing/image/)\>\&, const [Imaging::EncoderParametersPtr](../encoderparametersptr/)\&) | يضيف إطارًا إلى الملف أو التدفق المحدد في استدعاء سابق لطريقة [Save()](../../system.drawing/image/save/). |
| int [SelectActiveFrame](../../system.drawing/image/selectactiveframe/)(const [Imaging::FrameDimensionPtr](../framedimensionptr/)\&, int) | يختار الإطار المحدد. |
| virtual void [set_Palette](../../system.drawing/image/set_palette/)([Imaging::ColorPalettePtr](../colorpaletteptr/)) | يضبط لوحة الألوان المستخدمة في الصورة التي يمثلها الكائن الحالي. |
| virtual void [set_Tag](../../system.drawing/image/set_tag/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | يضبط كائنًا يوفر بيانات إضافية حول الصورة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n بوضع مؤشر ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك القفل لتصريح C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Metafile](./~metafile/)() | المدمر. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* الفئة [Image](../../system.drawing/image/)
* النطاق [System::Drawing::Imaging](../)
* المكتبة [Aspose.Slides](../../)