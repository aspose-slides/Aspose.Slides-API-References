---
title: SwfOptions
second_title: مرجع API Aspose.Slides برای C++
description: گزینه‌هایی را فراهم می‌کند که نحوه ذخیره یک ارائه در قالب Swf را کنترل می‌کند.
type: docs
weight: 742
url: /fa/aspose.slides.export/swfoptions/
---
## SwfOptions کلاس

گزینه‌هایی را فراهم می‌کند که نحوه ذخیره یک ارائه در قالب Swf را کنترل می‌کند.

```cpp
class SwfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISwfOptions
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقداری را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو مقدار NaN برابر در نظر گرفته می‌شوند، اگرچه طبق استاندارد IEC 60559:1989 NaN برابر با هیچ مقداری نیست، حتی NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو مقدار NaN برابر در نظر گرفته می‌شوند، اگرچه طبق استاندارد IEC 60559:1989 NaN برابر با هیچ مقداری نیست، حتی NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای اهداف داخلی. |
| **bool** [get_Compressed](./get_compressed/)() override | مشخص می‌کند آیا سند SWF تولید شده باید فشرده شود یا خیر. مقدار پیش‌فرض **true** است. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | فونتی را که در صورت عدم یافتن فونت منبع استفاده می‌شود برمی‌گرداند. [System::String](../../system/string/) خوانده می‌شود. |
| **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() override | منوی زمینه را فعال یا غیرفعال می‌کند. مقدار پیش‌فرض true است. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | سبک بصری گرادیان را برمی‌گرداند. [GradientStyle](../../aspose.slides/gradientstyle/) خوانده می‌شود. |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | کیفیت تصاویر JPEG را مشخص می‌کند. مقدار پیش‌فرض 95 است. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() override | تصویری که به عنوان لوگو در گوشه بالا-راست نمایشگر نمایش داده می‌شود. تصویر باید تصویر PNG با ابعاد 32x64 پیکسل باشد، در غیر این صورت لوگو ممکن است به‌درستی نمایش داده نشود. |
| [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() override | آدرس کامل پیوند را برای یک لوگو برمی‌گرداند. تنها در صورتی مؤثر است که یک [set_LogoImageBytes()](./set_logoimagebytes/) مشخص شده باشد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | شیء callbackی را برای به‌روزرسانی پیشرفت ذخیره‌سازی به درصد نشان می‌دهد. [IProgressCallback](../../aspose.slides/iprogresscallback/) را ببینید. |
| **bool** [get_ShowBottomPane](./get_showbottompane/)() override | قاب پایین را نمایش یا مخفی می‌کند. می‌تواند در flashvars بازنویسی شود. مقدار پیش‌فرض true است. |
| **bool** [get_ShowFullScreen](./get_showfullscreen/)() override | دکمه تمام-صفحه را نمایش یا مخفی می‌کند. می‌تواند در flashvars بازنویسی شود. مقدار پیش‌فرض true است. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | مشخص می‌کند آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا خیر. مقدار پیش‌فرض **false** است. |
| **bool** [get_ShowLeftPane](./get_showleftpane/)() override | قاب چپ را نمایش یا مخفی می‌کند. می‌تواند در flashvars بازنویسی شود. مقدار پیش‌فرض true است. |
| **bool** [get_ShowPageBorder](./get_showpageborder/)() override | مشخص می‌کند آیا حاشیه اطراف صفحات نشان داده شود یا خیر. مقدار پیش‌فرض true است. |
| **bool** [get_ShowPageStepper](./get_showpagestepper/)() override | دستگیره صفحه را نمایش یا مخفی می‌کند. می‌تواند در flashvars بازنویسی شود. مقدار پیش‌فرض true است. |
| **bool** [get_ShowSearch](./get_showsearch/)() override | بخش جستجو را نمایش یا مخفی می‌کند. می‌تواند در flashvars بازنویسی شود. مقدار پیش‌فرض true است. |
| **bool** [get_ShowTopPane](./get_showtoppane/)() override | تمام قاب بالا را نمایش یا مخفی می‌کند. می‌تواند در flashvars بازنویسی شود. مقدار پیش‌فرض true است. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | مشخص می‌کند آیا هنگام ذخیره ارائه، پیوندهای حاوی فراخوانی‌های JavaScript نادیده گرفته شوند یا خیر. **bool** خوانده می‌شود. مقدار پیش‌فرض **false** است. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | حالت قرارگیری اسلایدها بر صفحه هنگام خروجی‌گیری ارائه [ISlidesLayoutOptions](../islideslayoutoptions/) را برمی‌گرداند. این ویژگی از اختصاص اشیاء از نوع [HandoutLayoutingOptions](../handoutlayoutingoptions/) پشتیبانی نمی‌کند. |
| **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() override | با قاب چپ باز شروع می‌شود. می‌تواند در flashvars بازنویسی شود. مقدار پیش‌فرض false است. |
| **bool** [get_ViewerIncluded](./get_viewerincluded/)() override | مشخص می‌کند آیا سند SWF تولید شده باید نمایشگر سند یکپارچه را شامل شود یا خیر. مقدار پیش‌فرض **true** است. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | یک شیء را که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود، برمی‌گرداند یا تنظیم می‌کند. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) خوانده می‌شود. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش کردن اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌گذاری با عبارت C# lock() را انجام می‌دهد. به‌صورت مستقیم فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده شود. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان شبیه‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌آورد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌آورد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مرجع-مقایسه شیء نوع مقداری با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_Compressed](./set_compressed/)(**bool**) override | مشخص می‌کند آیا سند SWF تولید شده باید فشرده شود یا خیر. مقدار پیش‌فرض **true** است. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | فونت مورد استفاده را در صورت عدم یافتن فونت منبع تنظیم می‌کند. [System::String](../../system/string/) نوشته می‌شود. |
| void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) override | منوی زمینه را فعال یا غیرفعال می‌کند. مقدار پیش‌فرض true است. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | سبک بصری گرادیان را تنظیم می‌کند. [GradientStyle](../../aspose.slides/gradientstyle/) نوشته می‌شود. |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | کیفیت تصاویر JPEG را مشخص می‌کند. مقدار پیش‌فرض 95 است. |
| void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | تصویری که به عنوان لوگو در گوشه بالا-راست نمایشگر نمایش داده می‌شود. تصویر باید تصویر PNG با ابعاد 32x64 پیکسل باشد، در غیر این صورت لوگو ممکن است به‌درستی نمایش داده نشود. |
| void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) override | آدرس کامل پیوند برای یک لوگو را تنظیم می‌کند. فقط در صورتی مؤثر است که یک [set_LogoImageBytes()](./set_logoimagebytes/) مشخص شده باشد. |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | شیء callbackی را برای به‌روزرسانی پیشرفت ذخیره‌سازی به درصد نشان می‌دهد. [IProgressCallback](../../aspose.slides/iprogresscallback/) را ببینید. |
| void [set_ShowBottomPane](./set_showbottompane/)(**bool**) override | قاب پایین را نمایش یا مخفی می‌کند. می‌تواند در flashvars بازنویسی شود. مقدار پیش‌فرض true است. |
| void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) override | دکمه تمام-صفحه را نمایش یا مخفی می‌کند. می‌تواند در flashvars بازنویسی شود. مقدار پیش‌فرض true است. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | مشخص می‌کند آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا خیر. مقدار پیش‌فرض **false** است. |
| void [set_ShowLeftPane](./set_showleftpane/)(**bool**) override | قاب چپ را نمایش یا مخفی می‌کند. می‌تواند در flashvars بازنویسی شود. مقدار پیش‌فرض true است. |
| void [set_ShowPageBorder](./set_showpageborder/)(**bool**) override | مشخص می‌کند آیا حاشیه اطراف صفحات نشان داده شود یا خیر. مقدار پیش‌فرض true است. |
| void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) override | دستگیره صفحه را نمایش یا مخفی می‌کند. می‌تواند در flashvars بازنویسی شود. مقدار پیش‌فرض true است. |
| void [set_ShowSearch](./set_showsearch/)(**bool**) override | بخش جستجو را نمایش یا مخفی می‌کند. می‌تواند در flashvars بازنویسی شود. مقدار پیش‌فرض true است. |
| void [set_ShowTopPane](./set_showtoppane/)(**bool**) override | تمام قاب بالا را نمایش یا مخفی می‌کند. می‌تواند در flashvars بازنویسی شود. مقدار پیش‌فرض true است. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | مشخص می‌کند آیا هنگام ذخیره ارائه، پیوندهای حاوی فراخوانی‌های JavaScript نادیده گرفته شوند یا خیر. **bool** نوشته می‌شود. مقدار پیش‌فرض **false** است. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | حالت قرارگیری اسلایدها بر صفحه هنگام خروجی‌گیری ارائه [ISlidesLayoutOptions](../islideslayoutoptions/) را تنظیم می‌کند. این ویژگی از اختصاص اشیاء از نوع [HandoutLayoutingOptions](../handoutlayoutingoptions/) پشتیبانی نمی‌کند. |
| void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) override | با قاب چپ باز شروع می‌شود. می‌تواند در flashvars بازنویسی شود. مقدار پیش‌فرض false است. |
| void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) override | مشخص می‌کند آیا سند SWF تولید شده باید نمایشگر سند یکپارچه را شامل شود یا خیر. مقدار پیش‌فرض **true** است. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | یک شیء را که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود، برمی‌گرداند یا تنظیم می‌کند. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) نوشته می‌شود. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در محفظه‌ها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
|  [SwfOptions](./swfoptions/)() | سازنده پیش‌فرض. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گشایی عبارت C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده شود. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌سازد. |

## ملاحظات

مثال زیر نشان می‌دهد چگونه PowerPoint به SWF Flash تبدیل شود.
```cpp
auto presentation = System::MakeObject<Presentation>(u"HelloWorld.pptx");
auto swfOptions = System::MakeObject<SwfOptions>();

swfOptions->set_ViewerIncluded(false);
auto notesOptions = swfOptions->get_NotesCommentsLayouting();
notesOptions->set_NotesPosition(NotesPositions::BottomFull);

// Saving presentation and notes pages
presentation->Save(u"SaveAsSwf_out.swf", SaveFormat::Swf, swfOptions);
swfOptions->set_ViewerIncluded(true);
presentation->Save(u"SaveNotes_out.swf", SaveFormat::Swf, swfOptions);
```

## همچنین ببینید

* کلاس [SaveOptions](../saveoptions/)
* کلاس [ISwfOptions](../iswfoptions/)
* فضای‌نام [Aspose::Slides::Export](../)
* کتابخانه [Aspose.Slides](../../)