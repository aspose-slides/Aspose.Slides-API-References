---
title: ISwfOptions
second_title: Aspose.Slides برای مرجع API زبان C++
description: گزینه‌هایی را فراهم می‌کند که نحوهٔ ذخیره‌سازی یک ارائه در قالب SWF را کنترل می‌کنند.
type: docs
weight: 469
url: /fa/aspose.slides.export/iswfoptions/
---
## ISwfOptions کلاس

گزینه‌هایی را فراهم می‌کند که نحوهٔ ذخیرهٔ یک ارائه در قالب SWF را کنترل می‌کنند.

```cpp
class ISwfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## متدها

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ عددی ممیز شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ عددی ممیز شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual **bool** [get_Compressed](./get_compressed/)() | مشخص می‌کند آیا سند SWF تولید شده باید فشرده شود یا خیر. پیش‌فرض **true** است. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | فونتی را برمی‌گرداند که در صورت یافت نشدن فونت منبع استفاده می‌شود. [System::String](../../system/string/) را می‌خواند. |
| virtual **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() | منوی زمینه را فعال/غیرفعال می‌کند. پیش‌فرض true است. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | شیوهٔ بصری گرادیانت را برمی‌گرداند. [GradientStyle](../../aspose.slides/gradientstyle/) را می‌خواند. |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | کیفیت تصاویر JPEG را مشخص می‌کند.\n\n پیش‌فرض 95 است. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() | تصویری که به‌عنوان لوگو در گوشهٔ بالا-راست مشاهده‌گر نمایش داده می‌شود.\n\n تصویر باید به‌صورت PNG با ابعاد 32×64 پیکسل باشد، در غیر این‌صورت ممکن است لوگو به‌درستی نمایش داده نشود. |
| virtual [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() | آدرس کامل پیوند لوگو را دریافت می‌کند. فقط در صورتی اثر دارد که [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/) مشخص شده باشد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | یک شی بازخوانی برای ذخیرهٔ به‌روزرسانی‌های پیشرفت به‌صورت درصد را نشان می‌دهد. به [IProgressCallback](../../aspose.slides/iprogresscallback/) مراجعه کنید. |
| virtual **bool** [get_ShowBottomPane](./get_showbottompane/)() | نمایش/پنهان‌سازی قاب پایین. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است. |
| virtual **bool** [get_ShowFullScreen](./get_showfullscreen/)() | نمایش/پنهان‌سازی دکمهٔ تمام‌صفحه. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است. |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | مشخص می‌کند آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا خیر. پیش‌فرض **false** است. |
| virtual **bool** [get_ShowLeftPane](./get_showleftpane/)() | نمایش/پنهان‌سازی قاب چپ. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است. |
| virtual **bool** [get_ShowPageBorder](./get_showpageborder/)() | مشخص می‌کند آیا مرزی دور صفحات نمایش داده شود یا خیر. پیش‌فرض true است. |
| virtual **bool** [get_ShowPageStepper](./get_showpagestepper/)() | نمایش/پنهان‌سازی گام‌زن صفحه. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است. |
| virtual **bool** [get_ShowSearch](./get_showsearch/)() | نمایش/پنهان‌سازی بخش جستجو. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است. |
| virtual **bool** [get_ShowTopPane](./get_showtoppane/)() | نمایش/پنهان‌سازی تمام قاب بالا. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | مشخص می‌کند آیا هنگام ذخیرهٔ ارائه، پیوندهای دارای فراخوانی‌های جاوااسکریپت رد شوند یا خیر. **bool** را بنویسید. مقدار پیش‌فرض **false** است. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | حالت قرارگیری اسلایدها بر روی صفحه هنگام استخراج یک ارائه [ISlidesLayoutOptions](../islideslayoutoptions/) را دریافت می‌کند. این ویژگی از تخصیص اشیاء از نوع **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** پشتیبانی نمی‌کند. |
| virtual **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() | با باز کردن قاب چپ شروع می‌شود. می‌تواند در flashvars بازنویسی شود. پیش‌فرض false است. |
| virtual **bool** [get_ViewerIncluded](./get_viewerincluded/)() | مشخص می‌کند آیا سند SWF تولید شده باید نمایشگر سند یکپارچه را شامل شود یا خیر. پیش‌فرض **true** است. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | شیئی را برمی‌گرداند که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرایند بارگذاری ادامه یابد یا لغو شود. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) را می‌خواند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ ارجاع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. هش‌سازی اشیاء سفارشی را فعال می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C# است. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C# است. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ نسخه‌برداری. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت نسخه‌برداری برای کلاس‌های مشتق را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت نسخه‌برداری برای کلاس‌های مشتق را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر حسب ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر حسب ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ ارجاعی شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ ارجاع مشترک را به مقدار مشخص کاهش می‌دهد. |
| virtual void [set_Compressed](./set_compressed/)(**bool**) | مشخص می‌کند آیا سند SWF تولید شده باید فشرده شود یا خیر. پیش‌فرض **true** است. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | فونتی را تنظیم می‌کند که در صورت یافت نشدن فونت منبع استفاده شود. [System::String](../../system/string/) را می‌نویسد. |
| virtual void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) | منوی زمینه را فعال/غیرفعال می‌کند. پیش‌فرض true است. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | شیوهٔ بصری گرادیانت را تنظیم می‌کند. [GradientStyle](../../aspose.slides/gradientstyle/) را می‌نویسد. |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | کیفیت تصاویر JPEG را مشخص می‌کند.\n\n پیش‌فرض 95 است. |
| virtual void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | تصویری که به‌عنوان لوگو در گوشهٔ بالا-راست مشاهده‌گر نمایش داده می‌شود.\n\n تصویر باید به‌صورت PNG با ابعاد 32×64 پیکسل باشد، در غیر این‌صورت ممکن است لوگو به‌درستی نمایش داده نشود. |
| virtual void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) | آدرس کامل پیوند لوگو را تنظیم می‌کند. فقط در صورتی مؤثر است که [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/) مشخص شده باشد. |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | یک شی بازخوانی برای ذخیرهٔ به‌روزرسانی‌های پیشرفت به‌صورت درصد را نشان می‌دهد. به [IProgressCallback](../../aspose.slides/iprogresscallback/) مراجعه کنید. |
| virtual void [set_ShowBottomPane](./set_showbottompane/)(**bool**) | نمایش/پنهان‌سازی قاب پایین. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است. |
| virtual void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) | نمایش/پنهان‌سازی دکمهٔ تمام‌صفحه. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است. |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | مشخص می‌کند آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا خیر. پیش‌فرض **false** است. |
| virtual void [set_ShowLeftPane](./set_showleftpane/)(**bool**) | نمایش/پنهان‌سازی قاب چپ. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است. |
| virtual void [set_ShowPageBorder](./set_showpageborder/)(**bool**) | مشخص می‌کند آیا مرزی دور صفحات نمایش داده شود یا خیر. پیش‌فرض true است. |
| virtual void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) | نمایش/پنهان‌سازی گام‌زن صفحه. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است. |
| virtual void [set_ShowSearch](./set_showsearch/)(**bool**) | نمایش/پنهان‌سازی بخش جستجو. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است. |
| virtual void [set_ShowTopPane](./set_showtoppane/)(**bool**) | نمایش/پنهان‌سازی تمام قاب بالا. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | مشخص می‌کند آیا هنگام ذخیرهٔ ارائه، پیوندهای دارای فراخوانی‌های جاوااسکریپت رد شوند یا خیر. **bool** را بنویسید. مقدار پیش‌فرض **false** است. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | حالت قرارگیری اسلایدها بر روی صفحه هنگام استخراج یک ارائه [ISlidesLayoutOptions](../islideslayoutoptions/) را تنظیم می‌کند. این ویژگی از تخصیص اشیاء از نوع **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** پشتیبانی نمی‌کند. |
| virtual void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) | با باز کردن قاب چپ شروع می‌شود. می‌تواند در flashvars بازنویسی شود. پیش‌فرض false است. |
| virtual void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) | مشخص می‌کند آیا سند SWF تولید شده باید نمایشگر سند یکپارچه را شامل شود یا خیر. پیش‌فرض **true** است. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | شیئی را تنظیم می‌کند که هشدارها را دریافت کند و تصمیم بگیرد آیا فرایند بارگذاری ادامه یابد یا لغو شود. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) را می‌نویسد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C# است. تبدیل اشیاء سفارشی به رشته را فعال می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری معکوس بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |
## موارد مرتبط

* کلاس [ISaveOptions](../isaveoptions/)
* فضای‌نام [Aspose::Slides::Export](../)
* کتابخانه [Aspose.Slides](../../)