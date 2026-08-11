---
title: Metafile
second_title: مرجع API Aspose.Slides برای C++
description: "یک فایل گرافیکی متافایل را نشان می‌دهد. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() اختصاص داده شوند. هرگز نمونه‌ای از این نوع را در پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/ یا خطاهای صحت‌سنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 144
url: /fa/system.drawing.imaging/metafile/
---
## Metafile کلاس

Represents a graphic metafile. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Metafile : public System::Drawing::Image
```

## متدها

| متد | توضیح |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Image](../../system.drawing/image/)\> [Clone](./clone/)() override | یک نسخه کپی از شیء جاری را برمی‌گرداند. |
| void [Dispose](../../system.drawing/image/dispose/)() override | تمام منابع به‌دست آمده توسط شیء جاری را آزاد می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معانی C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را تقلید می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را تقلید می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../../system.drawing/image/)\> [FromFile](../../system.drawing/image/fromfile/)(const [String](../../system/string/)\&, **bool**) | یک شیء [Image](../../system.drawing/image/) را از فایل مشخص شده ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](../../system.drawing/bitmap/)\> [FromHbitmap](../../system.drawing/image/fromhbitmap/)(IntPtr) | یک شیء [Bitmap](../../system.drawing/bitmap/) را از بیت‌مپ GDI مشخص شده می‌سازد. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../../system.drawing/image/)\> [FromStream](../../system.drawing/image/fromstream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**, **bool**) | یک شیء [Image](../../system.drawing/image/) را از جریان مشخص شده ایجاد می‌کند. |
| virtual **int32_t** [get_Flags](../../system.drawing/image/get_flags/)() const | یک ترکیب بیتی از مقادیر enum ImageFlags را برمی‌گرداند که ویژگی‌های تصویر را نشان می‌دهد. |
| [ArrayPtr](../../system/arrayptr/)\<[Guid](../../system/guid/)\> [get_FrameDimensionsList](../../system.drawing/image/get_framedimensionslist/)() const | یک آرایه از GUIDها را برمی‌گرداند که ابعاد فریم‌های داخل تصویری که شیء جاری نمایندگی می‌کند را نشان می‌دهند. |
| int [get_Height](./get_height/)() const override | ارتفاع‌های تصویر را به پیکسل برمی‌گرداند. |
| **float** [get_HorizontalResolution](../../system.drawing/image/get_horizontalresolution/)() const | وضوح افقی تصویر نمایانده‌شده توسط شیء جاری را به پیکسل در اینچ برمی‌گرداند. |
| virtual [Imaging::ColorPalettePtr](../colorpaletteptr/) [get_Palette](../../system.drawing/image/get_palette/)() const | پالت رنگی که توسط تصویر نمایانده‌شده توسط شیء جاری استفاده می‌شود را برمی‌گرداند. |
| [Imaging::PixelFormat](../pixelformat/) [get_PixelFormat](./get_pixelformat/)() const override | مقداری که فرمت پیکسل را نشان می‌دهد را برمی‌گرداند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_PropertyIdList](../../system.drawing/image/get_propertyidlist/)() const | شناسه‌های موارد ویژگی ذخیره‌شده در این تصویر را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Imaging::PropertyItem](../propertyitem/)\>\> [get_PropertyItems](../../system.drawing/image/get_propertyitems/)() const | تمام موارد ویژگی (قطعات فراداده) ذخیره‌شده در این تصویر را دریافت می‌کند. |
| [Imaging::ImageFormatPtr](../imageformatptr/) [get_RawFormat](./get_rawformat/)() const override | مقداری که فرمت تصویر را نشان می‌دهد را برمی‌گرداند. |
| [Size](../../system.drawing/size/) [get_Size](../../system.drawing/image/get_size/)() const | یک شیء [Size](../../system.drawing/size/) را برمی‌گرداند که عرض و ارتفاع تصویر را به پیکسل نشان می‌دهد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Tag](../../system.drawing/image/get_tag/)() const | یک شیء دریافت می‌کند که داده‌های اضافی درباره تصویر ارائه می‌دهد. |
| **float** [get_VerticalResolution](../../system.drawing/image/get_verticalresolution/)() const | وضوح عمودی تصویر نمایانده‌شده توسط شیء جاری را به پیکسل در اینچ برمی‌گرداند. |
| int [get_Width](./get_width/)() const override | عرض تصویر را به پیکسل برمی‌گرداند. |
| [RectangleF](../../system.drawing/rectanglef/) [GetBounds](../../system.drawing/image/getbounds/)([GraphicsUnit](../../system.drawing/graphicsunit/)\&) | مرزهای تصویر را در واحدهای اندازه‌گیری مشخص‌شده برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده ارجاع مرتبط با شیء را دریافت می‌کند. |
| int [GetFrameCount](../../system.drawing/image/getframecount/)(const [Imaging::FrameDimensionPtr](../framedimensionptr/)\&) | تعداد فریم‌های بُعد فریم مشخص‌شده را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌سازی اشیاء سفارشی را فراهم می‌کند. |
| IntPtr [GetHenhmetafile](./gethenhmetafile/)() | پیاده‌سازی نشده. |
| [SharedPtr](../../system/sharedptr/)\<[MetafileHeader](../metafileheader/)\> [GetMetafileHeader](./getmetafileheader/)() | یک سرصفحه مرتبط با شیء جاری را برمی‌گرداند. |
| static int [GetPixelFormatSize](../../system.drawing/image/getpixelformatsize/)([Imaging::PixelFormat](../pixelformat/)) | تعداد بیت‌های استفاده‌شده برای نمایش عمق رنگ در فرمت پیکسل مشخص‌شده را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../../system.drawing/image/)\> [GetThumbnailImage](../../system.drawing/image/getthumbnailimage/)(int, int, [Image::GetThumbnailImageAbort](../../system.drawing/image/getthumbnailimageabort/), IntPtr) | یک تصویر بندانگشتی برای این شیء [System::Drawing::Image](../../system.drawing/image/) دریافت می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' C#. |
| static **bool** [IsAlphaPixelFormat](../../system.drawing/image/isalphapixelformat/)([Imaging::PixelFormat](../pixelformat/)) | تعیین می‌کند آیا فرمت پیکسل مشخص‌شده شامل اطلاعات آلفا است. |
| virtual **bool** [IsMultiImage](../../system.drawing/image/ismultiimage/)() const | باز می‌گرداند که آیا فرمت اصلی یک چند تصویر است یا خیر. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با بیان C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Metafile](./metafile/)(const [System::String](../../system/string/)\&) | پیاده‌سازی نشده. |
|  [Metafile](./metafile/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&) | پیاده‌سازی نشده. |
|  [Metafile](./metafile/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, IntPtr, [EmfType](../emftype/)) | پیاده‌سازی نشده. |
|  [Metafile](./metafile/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, IntPtr) | پیاده‌سازی نشده. |
|  [Metafile](./metafile/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, IntPtr, [Rectangle](../../system.drawing/rectangle/), [MetafileFrameUnit](../metafileframeunit/), [EmfType](../emftype/)) | پیاده‌سازی نشده. |
|  [Metafile](./metafile/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, IntPtr, [RectangleF](../../system.drawing/rectanglef/), [MetafileFrameUnit](../metafileframeunit/), [EmfType](../emftype/)) | پیاده‌سازی نشده. |
|  [Metafile](./metafile/)(IntPtr, [EmfType](../emftype/)) | پیاده‌سازی نشده. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را می‌دهد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را می‌دهد. |
| void [PlayRecord](./playrecord/)([EmfPlusRecordType](../emfplusrecordtype/), **int32_t**, **int32_t**, [System::ByteArrayPtr](../../system/bytearrayptr/)) | پیاده‌سازی نشده. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقابله ارجاعی شیء نوع مقداری با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ ارجاع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [RotateFlip](../../system.drawing/image/rotateflip/)([RotateFlipType](../../system.drawing/rotatefliptype/)) | تصویر را به مضربی از 90 درجه چرخانده و وارونه می‌کند. |
| void [Save](../../system.drawing/image/save/)(const [String](../../system/string/)\&) | تصویر نمایانده‌شده توسط شیء جاری را به فایل مشخص‌شده با فرمت PNG ذخیره می‌کند. |
| void [Save](../../system.drawing/image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageFormatPtr](../imageformatptr/)\&) | تصویر نمایانده‌شده توسط شیء جاری را به فایل مشخص‌شده در فرمت تعیین‌شده ذخیره می‌کند. |
| void [Save](../../system.drawing/image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageFormatPtr](../imageformatptr/)\&) | تصویر نمایانده‌شده توسط شیء جاری را به جریان مشخص‌شده در فرمت مشخص‌شده ذخیره می‌کند. |
| void [Save](../../system.drawing/image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageCodecInfoPtr](../imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../encoderparametersptr/)\&) | تصویر نمایانده‌شده توسط شیء جاری را به فایل مشخص‌شده با استفاده از رمزگذار و پارامترهای رمزگذار تعیین‌شده ذخیره می‌کند. |
| void [Save](../../system.drawing/image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageCodecInfoPtr](../imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../encoderparametersptr/)\&) | تصویر نمایانده‌شده توسط شیء جاری را به جریان مشخص‌شده با استفاده از رمزگذار و پارامترهای رمزگذار تعیین‌شده ذخیره می‌کند. |
| void [SaveAdd](../../system.drawing/image/saveadd/)(const [Imaging::EncoderParametersPtr](../encoderparametersptr/)\&) | یک فریم به فایل یا جریان مشخص‌شده در فراخوانی قبلی متد [Save()](../../system.drawing/image/save/) اضافه می‌کند. |
| void [SaveAdd](../../system.drawing/image/saveadd/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../../system.drawing/image/)\>\&, const [Imaging::EncoderParametersPtr](../encoderparametersptr/)\&) | یک فریم به فایل یا جریان مشخص‌شده در فراخوانی قبلی متد [Save()](../../system.drawing/image/save/) اضافه می‌کند. |
| int [SelectActiveFrame](../../system.drawing/image/selectactiveframe/)(const [Imaging::FrameDimensionPtr](../framedimensionptr/)\&, int) | فریم مشخص‌شده را انتخاب می‌کند. |
| virtual void [set_Palette](../../system.drawing/image/set_palette/)([Imaging::ColorPalettePtr](../colorpaletteptr/)) | پالت رنگی که توسط تصویر نمایانده‌شده توسط شیء جاری استفاده می‌شود را تنظیم می‌کند. |
| virtual void [set_Tag](../../system.drawing/image/set_tag/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | شیئی تنظیم می‌کند که داده‌های اضافی درباره تصویر فراهم می‌آورد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | تعداد شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده شود. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | تعداد شمارندهٔ ارجاع مشترک را کاهش داده و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده شود. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساخت typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری با بیان C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | تعداد شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده شود. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | تعداد شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده شود. |
| virtual  [~Metafile](./~metafile/)() | تخریب‌کننده. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [Image](../../system.drawing/image/)
* فضای نام [System::Drawing::Imaging](../)
* کتابخانه [Aspose.Slides](../../)