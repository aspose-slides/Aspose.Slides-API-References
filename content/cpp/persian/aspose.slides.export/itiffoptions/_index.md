---
title: ITiffOptions
second_title: مرجع API Aspose.Slides برای C++
description: گزینه‌هایی را فراهم می‌کند که نحوه ذخیره‌سازی ارائه در قالب TIFF را کنترل می‌کند.
type: docs
weight: 495
url: /fa/aspose.slides.export/itiffoptions/
---
## ITiffOptions کلاس

Provides options that control how a presentation is saved in TIFF format.

```cpp
class ITiffOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## متدها

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [BlackWhiteConversionMode](../blackwhiteconversionmode/) [get_BwConversionMode](./get_bwconversionmode/)() | الگوریتم تبدیل تصویر رنگی به تصویر سیاه و سفید را مشخص می‌کند. این گزینه فقط زمانی اعمال می‌شود که [ITiffOptions::get_CompressionType()](./get_compressiontype/) روی [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) یا [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) تنظیم شده باشد. بخوانید [BlackWhiteConversionMode](../blackwhiteconversionmode/). مقدار پیش‌فرض [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/) است. |
| virtual [TiffCompressionTypes](../tiffcompressiontypes/) [get_CompressionType](./get_compressiontype/)() | نوع فشرده‌سازی را مشخص می‌کند. بخوانید [TiffCompressionTypes](../tiffcompressiontypes/). |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | فونتی را که در صورت عدم یافتن فونت منبع استفاده می‌شود برمی‌گرداند. می‌خواند [System::String](../../system/string/). |
| virtual **uint32_t** [get_DpiX](./get_dpix/)() | رزولوشن افقی را بر حسب نقطه در اینچ مشخص می‌کند. می‌خواند **uint32_t**. |
| virtual **uint32_t** [get_DpiY](./get_dpiy/)() | رزولوشن عمودی را بر حسب نقطه در اینچ مشخص می‌کند. می‌خواند **uint32_t**. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | سبک بصری گرادیان را برمی‌گرداند. بخوانید [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual [System::Drawing::Size](../../system.drawing/size/) [get_ImageSize](./get_imagesize/)() | اندازه تصویر TIFF تولید شده را مشخص می‌کند. مقدار پیش‌فرض 0x0 است که به این معنی است که اندازه‌های تصویر تولید شده بر پایه مقدار اندازه اسلاید ارائه محاسبه می‌شود. بخوانید [System::Drawing::Size](../../system.drawing/size/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | گزینه‌هایی را فراهم می‌کند که ظاهر اشیاء [Ink](../../aspose.slides.ink/) را در سند خروجی کنترل می‌کند. فقط-خواندنی [IInkOptions](../iinkoptions/) |
| virtual [ImagePixelFormat](../imagepixelformat/) [get_PixelFormat](./get_pixelformat/)() | قالب پیکسل برای تصاویر تولید شده را مشخص می‌کند. بخوانید [ImagePixelFormat](../imagepixelformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | یک شیء callback برای ذخیره‌سازی به‌روزرسانی‌های پیشرفت به درصد را نشان می‌دهد. مشاهده [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | مشخص می‌کند که آیا سند تولید شده باید اسلایدهای پنهان را شامل شود یا خیر. مقدار پیش‌فرض **false** است. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | مشخص می‌کند که آیا هنگام ذخیره ارائه، پیوندهای همگانی با فراخوانی‌های JavaScript صرف‌نظر شوند یا نه. می‌خواند **bool**. مقدار پیش‌فرض **false** است. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | حالت قرارگیری اسلایدها روی صفحه هنگام خروجی‌گیری یک ارائه را بر می‌گرداند [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | شیئی را بر می‌گرداند که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرایند بارگذاری ادامه پیدا کند یا متوقف شود. بخوانید [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را بر می‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/) است. امکان هش‌سازی اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/) است. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است یا نه. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | اجرا کننده قفل‌گذاری دستور C# lock() است. به‌طور مستقیم فراخوانی کنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) است. امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
| [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر پایه مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر پایه مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء از نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [set_BwConversionMode](./set_bwconversionmode/)([BlackWhiteConversionMode](../blackwhiteconversionmode/)) | الگوریتم تبدیل تصویر رنگی به تصویر سیاه و سفید را مشخص می‌کند. این گزینه فقط زمانی اعمال می‌شود که [ITiffOptions::get_CompressionType()](./get_compressiontype/) روی [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) یا [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) تنظیم شده باشد. بنویسید [BlackWhiteConversionMode](../blackwhiteconversionmode/). مقدار پیش‌فرض [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/) است. |
| virtual void [set_CompressionType](./set_compressiontype/)([TiffCompressionTypes](../tiffcompressiontypes/)) | نوع فشرده‌سازی را مشخص می‌کند. بنویسید [TiffCompressionTypes](../tiffcompressiontypes/). |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | فونتی را که در صورت عدم یافتن فونت منبع استفاده می‌شود تنظیم می‌کند. می‌نویسد [System::String](../../system/string/). |
| virtual void [set_DpiX](./set_dpix/)(**uint32_t**) | رزولوشن افقی را بر حسب نقطه در اینچ مشخص می‌کند. بنویسید **uint32_t**. |
| virtual void [set_DpiY](./set_dpiy/)(**uint32_t**) | رزولوشن عمودی را بر حسب نقطه در اینچ مشخص می‌کند. بنویسید **uint32_t**. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | سبک بصری گرادیان را تنظیم می‌کند. بنویسید [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_ImageSize](./set_imagesize/)([System::Drawing::Size](../../system.drawing/size/)) | اندازه تصویر TIFF تولید شده را مشخص می‌کند. مقدار پیش‌فرض 0x0 است که به این معنی است که اندازه‌های تصویر تولید شده بر پایه مقدار اندازه اسلاید ارائه محاسبه می‌شود. بنویسید [System::Drawing::Size](../../system.drawing/size/). |
| virtual void [set_PixelFormat](./set_pixelformat/)([ImagePixelFormat](../imagepixelformat/)) | قالب پیکسل برای تصاویر تولید شده را مشخص می‌کند. بنویسید [ImagePixelFormat](../imagepixelformat/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | یک شیء callback برای ذخیره‌سازی به‌روزرسانی‌های پیشرفت به درصد را نشان می‌دهد. مشاهده [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | مشخص می‌کند که آیا سند تولید شده باید اسلایدهای پنهان را شامل شود یا خیر. مقدار پیش‌فرض **false** است. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | مشخص می‌کند که آیا هنگام ذخیره ارائه، پیوندهای همگانی با فراخوانی‌های JavaScript صرف‌نظر شوند یا نه. بنویسید **bool**. مقدار پیش‌فرض **false** است. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | حالت قرارگیری اسلایدها روی صفحه هنگام خروجی‌گیری یک ارائه را تنظیم می‌کند [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | شیئی را تنظیم می‌کند که هشدارها را دریافت کرده و تصمیم می‌گیرد آیا فرایند بارگذاری ادامه پیدا کند یا متوقف شود. بنویسید [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان شماره n قالب را به یک اشاره‌گر ضعیف (به‌جای shared) تنظیم می‌کند. امکان تعویض اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/) است. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرا کننده بازکردن قفل دستور C# lock() است. به‌طور مستقیم فراخوانی کنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [ISaveOptions](../isaveoptions/)
* فضای‌نام [Aspose::Slides::Export](../)
* کتابخانه [Aspose.Slides](../../)