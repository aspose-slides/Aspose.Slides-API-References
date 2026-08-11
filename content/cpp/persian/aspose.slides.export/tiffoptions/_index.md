---
title: TiffOptions
second_title: Aspose.Slides برای C++ مرجع API
description: گزینه‌هایی را فراهم می‌کند که نحوهٔ ذخیرهٔ یک ارائه در قالب TIFF را کنترل می‌کند.
type: docs
weight: 768
url: /fa/aspose.slides.export/tiffoptions/
---
## TiffOptions کلاس

گزینه‌هایی را فراهم می‌کند که نحوهٔ ذخیره‌سازی یک ارائه در قالب TIFF را کنترل می‌کند.

```cpp
class TiffOptions : public Aspose::Slides::Export::SaveOptions,
                    public Aspose::Slides::Export::ITiffOptions
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معانی C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | شبیه‌سازی مقایسهٔ نقطهٔ شناور به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | شبیه‌سازی مقایسهٔ نقطهٔ شناور به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [BlackWhiteConversionMode](../blackwhiteconversionmode/) [get_BwConversionMode](./get_bwconversionmode/)() override | الگوریتم تبدیل تصویر رنگی به تصویر سیاه و سفید را مشخص می‌کند. این گزینه تنها در صورتی اعمال می‌شود که [ITiffOptions::get_CompressionType()](../itiffoptions/get_compressiontype/) برابر با [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) یا [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) باشد. خواندن [BlackWhiteConversionMode](../blackwhiteconversionmode/). مقدار پیش‌فرض [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/) است. |
| [TiffCompressionTypes](../tiffcompressiontypes/) [get_CompressionType](./get_compressiontype/)() override | نوع فشرده‌سازی را مشخص می‌کند. خواندن [TiffCompressionTypes](../tiffcompressiontypes/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | قلمی را که در صورت یافت نشدن قلم منبع استفاده می‌شود برمی‌گرداند. خواندن [System::String](../../system/string/). |
| **uint32_t** [get_DpiX](./get_dpix/)() override | رزولوشن افقی را به نقطه در اینچ مشخص می‌کند. خواندن **uint32_t**. |
| **uint32_t** [get_DpiY](./get_dpiy/)() override | رزولوشن عمودی را به نقطه در اینچ مشخص می‌کند. خواندن **uint32_t**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | سبک بصری گرادیان را برمی‌گرداند. خواندن [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::Drawing::Size](../../system.drawing/size/) [get_ImageSize](./get_imagesize/)() override | اندازهٔ تصویر TIFF تولید شده را مشخص می‌کند. مقدار پیش‌فرض 0x0 است که به این معنی است که اندازهٔ تصاویر تولید شده بر پایهٔ مقدار اندازهٔ اسلاید ارائه محاسبه خواهد شد. خواندن [System::Drawing::Size](../../system.drawing/size/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | گزینه‌هایی را فراهم می‌کند که ظاهر اشیاء [Ink](../../aspose.slides.ink/) در سند صادرشده را کنترل می‌کند. فقط-خواندنی [IInkOptions](../iinkoptions/) |
| [ImagePixelFormat](../imagepixelformat/) [get_PixelFormat](./get_pixelformat/)() override | قالب پیکسل برای تصاویر تولید شده را مشخص می‌کند. خواندن [ImagePixelFormat](../imagepixelformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | یک شیء بازگردانی را برای ذخیره‌سازی به‌روزرسانی‌های پیشرفت به درصد نشان می‌دهد. ببینید [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | مشخص می‌کند که آیا سند تولید شده باید اسلایدهای پنهان را شامل شود یا نه. مقدار پیش‌فرض **false** است. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | مشخص می‌کند که آیا هنگام ذخیرهٔ ارائه، پیوندهایهای حاوی فراخوانی‌های JavaScript رد شوند یا نه. خواندن **bool**. مقدار پیش‌فرض **false** است. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | حالت قرارگیری اسلایدها بر صفحه هنگام خروجی‌گیری یک ارائه را دریافت می‌کند [ISlidesLayoutOptions](../islideslayoutoptions/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | یک شیء که هشدارها را دریافت می‌کند و تصمیم می‌گیرد که آیا فرآیند بارگذاری ادامه یابد یا abort شود را برمی‌گرداند یا تنظیم می‌کند. خواندن [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تحلیلگر روش [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. امکان هش‌کردن اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. مشابه فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. مشابه عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری توسط بیان lock() در C# را پیاده‌سازی می‌کند. مستقیم فراخوانی شود یا از شیء نگهبانی [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تحلیلگر روش [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_BwConversionMode](./set_bwconversionmode/)([BlackWhiteConversionMode](../blackwhiteconversionmode/)) override | الگوریتم تبدیل تصویر رنگی به تصویر سیاه و سفید را مشخص می‌کند. این گزینه تنها در صورتی اعمال می‌شود که [ITiffOptions::get_CompressionType()](../itiffoptions/get_compressiontype/) برابر با [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) یا [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) باشد. نوشتن [BlackWhiteConversionMode](../blackwhiteconversionmode/). مقدار پیش‌فرض [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/) است. |
| void [set_CompressionType](./set_compressiontype/)([TiffCompressionTypes](../tiffcompressiontypes/)) override | نوع فشرده‌سازی را مشخص می‌کند. نوشتن [TiffCompressionTypes](../tiffcompressiontypes/). |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | قلمی که در صورت یافت نشدن قلم منبع استفاده می‌شود را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| void [set_DpiX](./set_dpix/)(**uint32_t**) override | رزولوشن افقی را به نقطه در اینچ مشخص می‌کند. نوشتن **uint32_t**. |
| void [set_DpiY](./set_dpiy/)(**uint32_t**) override | رزولوشن عمودی را به نقطه در اینچ مشخص می‌کند. نوشتن **uint32_t**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | سبک بصری گرادیان را تنظیم می‌کند. نوشتن [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ImageSize](./set_imagesize/)([System::Drawing::Size](../../system.drawing/size/)) override | اندازهٔ تصویر TIFF تولید شده را مشخص می‌کند. مقدار پیش‌فرض 0x0 است که به این معنی است که اندازهٔ تصاویر تولید شده بر پایهٔ مقدار اندازهٔ اسلاید ارائه محاسبه خواهد شد. نوشتن [System::Drawing::Size](../../system.drawing/size/). |
| void [set_PixelFormat](./set_pixelformat/)([ImagePixelFormat](../imagepixelformat/)) override | قالب پیکسل برای تصاویر تولید شده را مشخص می‌کند. نوشتن [ImagePixelFormat](../imagepixelformat/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | یک شیء بازگردانی را برای ذخیره‌سازی به‌روزرسانی‌های پیشرفت به درصد نشان می‌دهد. ببینید [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | مشخص می‌کند که آیا سند تولید شده باید اسلایدهای پنهان را شامل شود یا نه. مقدار پیش‌فرض **false** است. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | مشخص می‌کند که آیا هنگام ذخیرهٔ ارائه، پیوندهای حاوی فراخوانی‌های JavaScript رد شوند یا نه. نوشتن **bool**. مقدار پیش‌فرض **false** است. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | حالت قرارگیری اسلایدها بر صفحه هنگام خروجی‌گیری یک ارائه را تنظیم می‌کند [ISlidesLayoutOptions](../islideslayoutoptions/). |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | یک شیء که هشدارها را دریافت می‌کند و تصمیم می‌گیرد که آیا فرآیند بارگذاری ادامه یابد یا abort شود را برمی‌گرداند یا تنظیم می‌کند. نوشتن [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار جاری شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیم فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید مستقیم فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
|  [TiffOptions](./tiffoptions/)() | سازندهٔ پیش‌فرض. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تحلیلگر روش [Object.ToString()](../../system/object/tostring/) در C# است. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای بازکردن قفل توسط بیان lock() در C# را پیاده‌سازی می‌کند. مستقیم فراخوانی شود یا از شیء نگهبانی [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیم فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیم فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## توضیحات

مثال زیر نشان می‌دهد چگونه PowerPoint را با اندازه پیش‌فرض به TIFF تبدیل می‌کنیم.
```cpp
// یک شیء Presentation ایجاد می‌کند که نمایانگر یک فایل ارائه است
auto presentation = System::MakeObject<Presentation>(u"DemoFile.pptx");

// ذخیرهٔ ارائه به سند TIFF
presentation->Save(u"Tiffoutput_out.tiff", SaveFormat::Tiff);
```
مثال زیر نشان می‌دهد چگونه PowerPoint را با اندازهٔ سفارشی به TIFF تبدیل می‌کنیم.
```cpp
// یک شیء Presentation ایجاد می‌کند که نمایانگر یک فایل ارائه است
auto pres = System::MakeObject<Presentation>(u"Convert_Tiff_Custom.pptx");

// شیء کلاس TiffOptions را ایجاد می‌کند
System::SharedPtr<TiffOptions> opts = System::MakeObject<TiffOptions>();
// تنظیم نوع فشرده‌سازی
opts->set_CompressionType(TiffCompressionTypes::Default);

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
opts->set_SlidesLayoutOptions(slidesLayoutOptions);

// انواع فشرده‌سازی
// Default - طرح فشرده‌سازی پیش‌فرض (LZW) را مشخص می‌کند.
// None - عدم فشرده‌سازی را مشخص می‌کند.
// CCITT3
// CCITT4
// LZW
// RLE
// عمق بستگی به نوع فشرده‌سازی دارد و نمی‌توان به‌صورت دستی تنظیم شد.
// واحد وضوح همیشه برابر "2" (نقطه در اینچ) است
// تنظیم DPI تصویر
opts->set_DpiX(200);
opts->set_DpiY(100);
// تنظیم اندازه تصویر
opts->set_ImageSize(System::Drawing::Size(1728, 1078));
// ذخیرهٔ ارائه به TIFF با اندازه تصویر مشخص‌شده
pres->Save(u"TiffWithCustomSize_out.tiff", SaveFormat::Tiff, opts);
```
مثال زیر نشان می‌دهد چگونه PowerPoint را با قالب پیکسل تصویر سفارشی به TIFF تبدیل می‌کنیم.
```cpp
// یک شیء Presentation ایجاد می‌کند که نمایانگر یک فایل ارائه است
auto presentation = System::MakeObject<Presentation>(u"DemoFile.pptx");

System::SharedPtr<TiffOptions> options = System::MakeObject<TiffOptions>();
options->set_PixelFormat(ImagePixelFormat::Format8bppIndexed);

// ارائه را با اندازه تصویر مشخص به TIFF ذخیره می‌کند
presentation->Save(u"Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat::Tiff, options);
```

## مراجع

* کلاس [SaveOptions](../saveoptions/)
* کلاس [ITiffOptions](../itiffoptions/)
* فضای‌نام [Aspose::Slides::Export](../)
* کتابخانه [Aspose.Slides](../../)