---
title: Bitmap
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "يمثل صورة bitmap من GDI+. يجب تخصيص كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم أبداً بإنشاء مثال من هذا النوع على المكدس أو باستخدام عامل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل أو عطل في التأكيد. احرص دائماً على تغليف هذه الفئة داخل مؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 1
url: /ar/system.drawing/bitmap/
---
## فئة Bitmap

يمثل صورة Bitmap من GDI+. يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم أبداً بإنشاء مثال من هذا النوع على مكدس أو باستخدام عامل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل أو عطل في التأكيد. احرص دائماً على وضع هذه الفئة داخل مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class Bitmap : public System::Drawing::Image
```
## الطرق

| الطريقة | الوصف |
| --- | --- |
| **bool** [BeginPixelProcessing](./beginpixelprocessing/)(**bool**) | يفعل وضع معالجة البكسلات. |
|  [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&) | يبني كائن [Bitmap](./) جديد من الصورة الموجودة المحددة. |
|  [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**) | يبني كائن [Bitmap](./) جديد من الدفق المحدد. |
|  [Bitmap](./bitmap/)(const [String](../../system/string/)\&) | يبني كائن [Bitmap](./) جديد من الملف المحدد. |
|  [Bitmap](./bitmap/)(const [String](../../system/string/)\&, **bool**) | يبني كائن [Bitmap](./) جديد من الملف المحدد. |
|  [Bitmap](./bitmap/)(int, int, [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | يبني كائن [Bitmap](./) جديد يمثل صورة bitmap بالعرض والارتفاع وتنسيق البكسل وبيانات البكسل المحددة. |
|  [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Size](../size/)\&) | يبني كائن [Bitmap](./) جديد من الصورة الموجودة المحددة، مُقاسًا إلى الحجم المحدد. |
|  [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int) | يبني كائن [Bitmap](./) جديد من الصورة الموجودة المحددة مع تعديل العرض والارتفاع إلى القيم المحددة. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [Clone](./clone/)() override | ينشئ نسخة من الكائن الحالي. |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([Rectangle](../rectangle/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | ينشئ كائن [Bitmap](./) يمثل نسخة من منطقة من صورة bitmap التي يمثلها الكائن الحالي. |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([RectangleF](../rectanglef/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | ينشئ كائن [Bitmap](./) يمثل نسخة من منطقة من صورة bitmap التي يمثلها الكائن الحالي. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ComputeHash](./computehash/)() | يحسب قيمة تجزئة SHA1. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [ConvertToARGBImage](./converttoargbimage/)(const [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\>\&) | ينشئ نسخة من صورة bitmap المحددة مع تغيير تنسيق البكسل إلى Format32bppArgb. |
| void [Dispose](../image/dispose/)() override | يطلق جميع الموارد التي حصل عليها الكائن الحالي. |
| **bool** [EndPixelProcessing](./endpixelprocessing/)(**bool**) | يعطل وضع معالجة البكسلات. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُ considered NaN-ان اثنان متساويتين بالرغم من أن IEC 60559:1989 توضح أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُ considered NaN-ان اثنان متساويتين بالرغم من أن IEC 60559:1989 توضح أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromFile](../image/fromfile/)(const [String](../../system/string/)\&, **bool**) | ينشئ كائن [Image](../image/) من الملف المحدد. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [FromHbitmap](../image/fromhbitmap/)(IntPtr) | يبني كائن [Bitmap](./) من bitmap GDI المحدد. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromStream](../image/fromstream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**, **bool**) | ينشئ كائن [Image](../image/) من الدفق المحدد. |
| virtual **int32_t** [get_Flags](../image/get_flags/)() const | يعيد تركيبة بتية من قيم تعداد ImageFlags التي تمثل خصائص الصورة. |
| [ArrayPtr](../../system/arrayptr/)\<[Guid](../../system/guid/)\> [get_FrameDimensionsList](../image/get_framedimensionslist/)() const | يعيد مصفوفة من GUIDs التي تمثل أبعاد الإطارات داخل الصورة التي يمثلها الكائن الحالي. |
| int [get_Height](./get_height/)() const override | يعيد ارتفاع الصورة بالبكسل. |
| **float** [get_HorizontalResolution](../image/get_horizontalresolution/)() const | يعيد الدقة الأفقية للصورة التي يمثلها الكائن الحالي بوحدة بكسل لكل بوصة. |
| [Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/) [get_Palette](./get_palette/)() const override | يعيد لوحة ألوان الصورة التي يمثلها الكائن الحالي. |
| [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/) [get_PixelFormat](./get_pixelformat/)() const override | يعيد تنسيق البكسل للصورة التي يمثلها الكائن الحالي. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_PropertyIdList](../image/get_propertyidlist/)() const | يحصل على معرفات عناصر الخصائص المخزنة في هذه الصورة. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Imaging::PropertyItem](../../system.drawing.imaging/propertyitem/)\>\> [get_PropertyItems](../image/get_propertyitems/)() const | يحصل على جميع عناصر الخصائص (قطع البيانات التعريفية) المخزنة في هذه الصورة. |
| [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/) [get_RawFormat](./get_rawformat/)() const override | يعيد تنسيق الملف للصورة التي يمثلها الكائن الحالي. |
| [Size](../size/) [get_Size](../image/get_size/)() const | يعيد كائن [Size](../size/) يمثل عرض وارتفاع الصورة بالبكسل. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Tag](../image/get_tag/)() const | يحصل على كائن يوفر بيانات إضافية حول الصورة. |
| **float** [get_VerticalResolution](../image/get_verticalresolution/)() const | يعيد الدقة العمودية للصورة التي يمثلها الكائن الحالي بوحدة بكسل لكل بوصة. |
| int [get_Width](./get_width/)() const override | يعيد عرض الصورة بالبكسل. |
| [RectangleF](../rectanglef/) [GetBounds](../image/getbounds/)([GraphicsUnit](../graphicsunit/)\&) | يعيد حدود الصورة بوحدات القياس المحددة. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل عداد المراجع المرتبط بالكائن. |
| int [GetFrameCount](../image/getframecount/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&) | يعيد عدد الإطارات في البُعد الإطاري المحدد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يمكن تجزئة الكائنات المخصصة. |
| IntPtr [GetHbitmap](./gethbitmap/)() | ينشئ كائن bitmap GDI من bitmap الذي يمثله الكائن الحالي. |
| [Color](../color/) [GetPixel](./getpixel/)(int, int) | يعيد لون البكسل المحدد. |
| static int [GetPixelFormatSize](../image/getpixelformatsize/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | يعيد عدد البتات المستخدمة لتمثيل عمق اللون في تنسيق البكسل المحدد. |
| const SkBitmap * [GetSkBitmap](./getskbitmap/)() const override | يعيد مؤشرًا خامًا إلى كائن SkBitmap الأساسي. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [GetThumbnailImage](../image/getthumbnailimage/)(int, int, [Image::GetThumbnailImageAbort](../image/getthumbnailimageabort/), IntPtr) | يحصل على صورة مصغرة لهذا الكائن [System::Drawing::Image](../image/). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير نداء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| static **bool** [IsAlphaPixelFormat](../image/isalphapixelformat/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | يحدد ما إذا كان تنسيق البكسل المحدد يحتوي على معلومات ألفا. |
| **bool** [IsMultiImage](./ismultiimage/)() const override | يعيد ما إذا كان التنسيق الأصلي متعدد الصور. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل تعبير C# lock(). استدعٍ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | يقفل [Bitmap](./) في ذاكرة النظام. |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/), const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | يقفل [Bitmap](./) في ذاكرة النظام. |
| void [MakeTransparent](./maketransparent/)([Color](../color/)) | يغيّر لون جميع البكسلات ذات اللون المحدد إلى شفاف. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيء جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، فقط يهيء كائنًا جديدًا ويتيح إنشاء نسخ من الفئات المشتقة. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيء كائنًا جديدًا ويتيح إنشاء نسخ من الفئات المشتقة. |
| void [PremultipleColors](./premultiplecolors/)() | يُضرب ألوان بكسلات الصورة التي يمثلها الكائن الحالي مسبقًا. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد المرجع المشترك بالقيمة المحددة. |
| void [RotateFlip](./rotateflip/)([RotateFlipType](../rotatefliptype/)) override | يدور الصورة إلى مضاعف 90 درجة ويقلبها. |
| void [Save](../image/save/)(const [String](../../system/string/)\&) | يحفظ الصورة التي يمثلها الكائن الحالي إلى الملف المحدد بصيغة PNG. |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | يحفظ الصورة التي يمثلها الكائن الحالي إلى الملف المحدد بالصيغ المحددة. |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | يحفظ الصورة التي يمثلها الكائن الحالي إلى الدفق المحدد بالصيغ المحددة. |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | يحفظ الصورة التي يمثلها الكائن الحالي إلى الملف المحدد باستخدام المشفر المحدد ومعلمات المشفر. |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | يحفظ الصورة التي يمثلها الكائن الحالي إلى الدفق المحدد باستخدام المشفر المحدد ومعلمات المشفر. |
| void [SaveAdd](../image/saveadd/)(const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | يضيف إطارًا إلى الملف أو الدفق المحدد في استدعاء سابق لطريقة [Save()](../image/save/). |
| void [SaveAdd](../image/saveadd/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | يضيف إطارًا إلى الملف أو الدفق المحدد في استدعاء سابق لطريقة [Save()](../image/save/). |
| int [SelectActiveFrame](../image/selectactiveframe/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&, int) | يختار الإطار المحدد. |
| void [set_Palette](./set_palette/)([Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/)) override | يضبط لوحة ألوان الصورة التي يمثلها الكائن الحالي. |
| virtual void [set_Tag](../image/set_tag/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | يضبط كائنًا يوفر بيانات إضافية حول الصورة. |
| void [SetPixel](./setpixel/)(int, int, [Color](../color/)) | يضبط لون البكسل المحدد في صورة bitmap التي يمثلها الكائن الحالي. |
| void [SetResolution](./setresolution/)(**float**, **float**) | يضبط دقة الصورة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي الـ n كمرجع ضعيف (بدلاً من مشترك). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدد العدادات المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص عداد المرجع المشترك ويعيده. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل تعبير C# lock(). استدعٍ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| void [UnlockBits](./unlockbits/)(const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | يفك القفل عن bitmap المحدد من ذاكرة النظام. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدد العدادات الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## انظر أيضاً

* الفئة [Image](../image/)
* المساحة الاسمية [System::Drawing](../)
* المكتبة [Aspose.Slides](../../)