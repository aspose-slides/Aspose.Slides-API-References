---
title: Bitmap
second_title: "مرجع API Aspose.Slides برای C++"
description: "یک تصویر بیت‌مپ GDI+ را نشان می‌دهد. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای assert می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای پاس دادن به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 1
url: /fa/system.drawing/bitmap/
---
## کلاس Bitmap

یک تصویر بیت‌مپ GDI+ را نشان می‌دهد. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای assert می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای پاس دادن به توابع به عنوان آرگومان استفاده کنید.

```cpp
class Bitmap : public System::Drawing::Image
```

## متدها

| متد | توضیح |
| --- | --- |
| **bool** [BeginPixelProcessing](./beginpixelprocessing/)(**bool**) | حالت پردازش پیکسل را فعال می‌کند. |
|  [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&) | یک شیء [Bitmap](./) جدید را از تصویر موجود مشخص‌شده می‌سازد. |
|  [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**) | یک شیء [Bitmap](./) جدید را از جریان مشخص‌شده می‌سازد. |
|  [Bitmap](./bitmap/)(const [String](../../system/string/)\&) | یک شیء [Bitmap](./) جدید را از فایل مشخص‌شده می‌سازد. |
|  [Bitmap](./bitmap/)(const [String](../../system/string/)\&, **bool**) | یک شیء [Bitmap](./) جدید را از فایل مشخص‌شده می‌سازد. |
|  [Bitmap](./bitmap/)(int, int, [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | یک شیء [Bitmap](./) جدید را می‌سازد که یک تصویر بیت‌مپ با عرض، ارتفاع، فرمت پیکسل و داده‌های پیکسل مشخص‌شده را نشان می‌دهد. |
|  [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Size](../size/)\&) | یک شیء [Bitmap](./) جدید را از تصویر موجود مشخص‌شده، مقیاس‌دار به اندازهٔ مشخص‌شده می‌سازد. |
|  [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int) | یک شیء [Bitmap](./) جدید را از تصویر موجود مشخص‌شده با عرض و ارتفاع مقیاس‌دار به مقادیر مشخص‌شده می‌سازد. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [Clone](./clone/)() override | یک کپی از شیء فعلی را ایجاد می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([Rectangle](../rectangle/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | یک شیء [Bitmap](./) ایجاد می‌کند که نمایانگر یک کپی از ناحیه‌ای از تصویر بیت‌مپ نمایانگر توسط شیء فعلی است. |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([RectangleF](../rectanglef/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | یک شیء [Bitmap](./) ایجاد می‌کند که نمایانگر یک کپی از ناحیه‌ای از تصویر بیت‌مپ نمایانگر توسط شیء فعلی است. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ComputeHash](./computehash/)() | مقدار هش SHA1 را محاسبه می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [ConvertToARGBImage](./converttoargbimage/)(const [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\>\&) | یک کپی از تصویر بیت‌مپ مشخص‌شده ایجاد می‌کند که فرمت پیکسل به Format32bppArgb تغییر یافته است. |
| void [Dispose](../image/dispose/)() override | تمام منابع به‌دست‌آمده توسط شیء فعلی را آزاد می‌کند. |
| **bool** [EndPixelProcessing](./endpixelprocessing/)(**bool**) | حالت پردازش پیکسل را غیرفعال می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ عددی شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ عددی شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای موارد داخلی. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromFile](../image/fromfile/)(const [String](../../system/string/)\&, **bool**) | یک شیء [Image](../image/) را از فایل مشخص‌شده ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [FromHbitmap](../image/fromhbitmap/)(IntPtr) | یک شیء [Bitmap](./) را از بیت‌مپ GDI مشخص‌شده می‌سازد. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromStream](../image/fromstream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**, **bool**) | یک شیء [Image](../image/) را از جریان مشخص‌شده ایجاد می‌کند. |
| virtual **int32_t** [get_Flags](../image/get_flags/)() const | یک ترکیب بیتی از مقادیر enum ImageFlags که ویژگی‌های تصویر را نشان می‌دهد، برمی‌گرداند. |
| [ArrayPtr](../../system/arrayptr/)\<[Guid](../../system/guid/)\> [get_FrameDimensionsList](../image/get_framedimensionslist/)() const | یک آرایه از GUIDها که ابعاد فریم‌های داخل تصویر نمایانگر توسط شیء فعلی را نشان می‌دهد، برمی‌گرداند. |
| int [get_Height](./get_height/)() const override | ارتفاع تصویر را بر حسب پیکسل برمی‌گرداند. |
| **float** [get_HorizontalResolution](../image/get_horizontalresolution/)() const | وضوح افقی تصویر نمایانگر توسط شیء فعلی را به پیکسل بر اینچ برمی‌گرداند. |
| [Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/) [get_Palette](./get_palette/)() const override | پالت رنگی که توسط تصویر نمایانگر توسط شیء فعلی استفاده می‌شود را برمی‌گرداند. |
| [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/) [get_PixelFormat](./get_pixelformat/)() const override | فرمت پیکسل تصویر نمایانگر توسط شیء فعلی را برمی‌گرداند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_PropertyIdList](../image/get_propertyidlist/)() const | شناسه‌های موارد ویژگی ذخیره‌شده در این تصویر را برمی‌گیرد. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Imaging::PropertyItem](../../system.drawing.imaging/propertyitem/)\>\> [get_PropertyItems](../image/get_propertyitems/)() const | تمام موارد ویژگی (قطعات متادیتا) ذخیره‌شده در این تصویر را برمی‌گیرد. |
| [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/) [get_RawFormat](./get_rawformat/)() const override | قالب فایل تصویر نمایانگر توسط شیء فعلی را برمی‌گرداند. |
| [Size](../size/) [get_Size](../image/get_size/)() const | یک شیء [Size](../size/) را برمی‌گرداند که عرض و ارتفاع تصویر را به پیکسل نشان می‌دهد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Tag](../image/get_tag/)() const | یک شیء که داده‌های اضافی درباره تصویر فراهم می‌کند را برمی‌گیرد. |
| **float** [get_VerticalResolution](../image/get_verticalresolution/)() const | وضوح عمودی تصویر نمایانگر توسط شیء فعلی را به پیکسل بر اینچ برمی‌گرداند. |
| int [get_Width](./get_width/)() const override | عرض تصویر را بر حسب پیکسل برمی‌گرداند. |
| [RectangleF](../rectanglef/) [GetBounds](../image/getbounds/)([GraphicsUnit](../graphicsunit/)\&) | حدود تصویر را به واحدهای اندازه‌گیری مشخص‌شده برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارندهٔ مرجع مرتبط با شیء را برمی‌گیرد. |
| int [GetFrameCount](../image/getframecount/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&) | تعداد فریم‌های بعدی بُعد فریم مشخص‌شده را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| IntPtr [GetHbitmap](./gethbitmap/)() | یک شیء بیت‌مپ GDI را از بیت‌مپ نمایانگر توسط شیء فعلی ایجاد می‌کند. |
| [Color](../color/) [GetPixel](./getpixel/)(int, int) | رنگ پیکسل مشخص‌شده را برمی‌گرداند. |
| static int [GetPixelFormatSize](../image/getpixelformatsize/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | تعداد بیت‌های مورد استفاده برای نشان دادن عمق رنگ در فرمت پیکسل مشخص‌شده را برمی‌گرداند. |
| const SkBitmap * [GetSkBitmap](./getskbitmap/)() const override | یک اشاره‌گر خام به شیء SkBitmap زیربنایی را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [GetThumbnailImage](../image/getthumbnailimage/)(int, int, [Image::GetThumbnailImageAbort](../image/getthumbnailimageabort/), IntPtr) | یک تصویر بندانگشتی برای این شیء [System::Drawing::Image](../image/) برمی‌گیرد. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گیرد. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| static **bool** [IsAlphaPixelFormat](../image/isalphapixelformat/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | تعیین می‌کند که آیا فرمت پیکسل مشخص‌شده شامل اطلاعات آلفا است. |
| **bool** [IsMultiImage](./ismultiimage/)() const override | اینکه قالب اصلی یک چندتصویر است را برمی‌گرداند. |
| void [Lock](../../system/object/lock/)() | قفل کردن عبارت lock() در C# را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | یک [Bitmap](./) را در حافظهٔ سیستم قفل می‌کند. |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/), const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | یک [Bitmap](./) را در حافظهٔ سیستم قفل می‌کند. |
| void [MakeTransparent](./maketransparent/)([Color](../color/)) | رنگ تمام پیکسل‌هایی که با رنگ مشخص‌شده دارند را به شفاف تغییر می‌دهد. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان شبیه‌سازی انواع سفارشی را فراهم می‌کند. |
| [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و ساخت کپی برای زیرکلاس‌ها را ممکن می‌سازد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و ساخت کپی برای زیرکلاس‌ها را ممکن می‌سازد. |
| void [PremultipleColors](./premultiplecolors/)() | رنگ‌های پیکسل‌های تصویر نمایانگر توسط شیء فعلی را پیش‌ضرب می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر حسب ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر حسب ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr از نظر ارجاع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [RotateFlip](./rotateflip/)([RotateFlipType](../rotatefliptype/)) override | تصویر را به چند برابر 90 درجه می‌چرخاند و وارون می‌کند. |
| void [Save](../image/save/)(const [String](../../system/string/)\&) | تصویر نمایانگر توسط شیء فعلی را به فایل مشخص‌شده در قالب PNG ذخیره می‌کند. |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | تصویر نمایانگر توسط شیء فعلی را به فایل مشخص‌شده در قالب مشخص‌شده ذخیره می‌کند. |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | تصویر نمایانگر توسط شیء فعلی را به جریان مشخص‌شده در قالب مشخص‌شده ذخیره می‌کند. |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | تصویر نمایانگر توسط شیء فعلی را به فایل مشخص‌شده با استفاده از رمزگذار و پارامترهای رمزگذار مشخص‌شده ذخیره می‌کند. |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | تصویر نمایانگر توسط شیء فعلی را به جریان مشخص‌شده با استفاده از رمزگذار و پارامترهای رمزگذار مشخص‌شده ذخیره می‌کند. |
| void [SaveAdd](../image/saveadd/)(const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | یک فریم به فایل یا جریان مشخص‌شده در فراخوانی قبلی متد [Save()](../image/save/) اضافه می‌کند. |
| void [SaveAdd](../image/saveadd/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | یک فریم به فایل یا جریان مشخص‌شده در فراخوانی قبلی متد [Save()](../image/save/) اضافه می‌کند. |
| int [SelectActiveFrame](../image/selectactiveframe/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&, int) | فریم مشخص‌شده را انتخاب می‌کند. |
| void [set_Palette](./set_palette/)([Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/)) override | پالت رنگی که توسط تصویر نمایانگر توسط شیء فعلی استفاده می‌شود را تنظیم می‌کند. |
| virtual void [set_Tag](../image/set_tag/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | یک شیء که داده‌های اضافی درباره تصویر فراهم می‌کند را تنظیم می‌کند. |
| void [SetPixel](./setpixel/)(int, int, [Color](../color/)) | رنگ پیکسل مشخص‌شده در تصویر بیت‌مپ نمایانگر توسط شیء فعلی را تنظیم می‌کند. |
| void [SetResolution](./setresolution/)(**float**, **float**) | وضوح تصویر را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان الگوئی n'th را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار جاری شمارندهٔ مرجع مشترک را برمی‌گیرد. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C# است. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل کردن عبارت lock() در C# را از حالت قفل باز می‌کند. مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| void [UnlockBits](./unlockbits/)(const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | بیت‌مپ مشخص‌شده را از حافظهٔ سیستم باز می‌کند. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [Image](../image/)
* فضای نام [System::Drawing](../)
* کتابخانه [Aspose.Slides](../../)