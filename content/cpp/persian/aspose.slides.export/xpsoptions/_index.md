---
title: XpsOptions
second_title: مرجع API Aspose.Slides برای C++
description: گزینه‌هایی را فراهم می‌کند که نحوهٔ ذخیره‌سازی یک ارائه در قالب XPS را کنترل می‌کند.
type: docs
weight: 807
url: /fa/aspose.slides.export/xpsoptions/
---
## XpsOptions کلاس

Provides options that control how a presentation is saved in XPS format.

```cpp
class XpsOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::IXpsOptions
```

## متدها

| Method | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقداری را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | احاَیی مقایسه نقاط شناور به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | احاَیی مقایسه نقاط شناور به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای اهداف داخلی. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | قلم (فونت) مورد استفاده را در صورت عدم یافتن قلم منبع برمی‌گرداند. [System::String](../../system/string/) را می‌خواند. |
| **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() override | درست (True) برای کشیدن قاب سیاه دور هر اسلاید. **bool** را می‌خواند. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | سبک بصری گرادینت را برمی‌گرداند. [GradientStyle](../../aspose.slides/gradientstyle/) را می‌خواند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | شیء callback را برای به‌روزرسانی پیشرفت ذخیره‌سازی به درصد نشان می‌دهد. به [IProgressCallback](../../aspose.slides/iprogresscallback/) مراجعه کنید. |
| **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() override | درست (True) برای تبدیل تمام متافایل‌های استفاده‌شده در یک ارائه به تصاویر PNG. **bool** را می‌خواند. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | مشخص می‌کند آیا سند تولیدشده باید اسلایدهای پنهان را شامل شود یا خیر. مقدار پیش‌فرض **false** است. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | مشخص می‌کند آیا هنگام ذخیرهٔ ارائه، پیوندهای هیپرلینک با فراخوانی JavaScript رد شوند یا نه. **bool** را می‌خواند. مقدار پیش‌فرض **false** است. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | شیئی را برمی‌گرداند یا تنظیم می‌کند که هشدارها را دریافت کرده و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا لغو شود. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) را می‌خواند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل روش [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. امکان هش‌سازی اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C# است. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری با عبارت lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان تکثیر انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را می‌سازد. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور اختصاص. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع‌گونه شیء نوع مقداری با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | قلم را که در صورت عدم یافتن قلم منبع استفاده می‌شود تنظیم می‌کند. [System::String](../../system/string/) را می‌نویسد. |
| void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) override | درست (True) برای کشیدن قاب سیاه دور هر اسلاید. **bool** را می‌نویسد. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | سبک بصری گرادینت را تنظیم می‌کند. [GradientStyle](../../aspose.slides/gradientstyle/) را می‌نویسد. |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | شیء callback را برای به‌روزرسانی پیشرفت ذخیره‌سازی به درصد نشان می‌دهد. به [IProgressCallback](../../aspose.slides/iprogresscallback/) مراجعه کنید. |
| void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) override | درست (True) برای تبدیل تمام متافایل‌های استفاده‌شده در یک ارائه به تصاویر PNG. **bool** را می‌نویسد. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | مشخص می‌کند آیا سند تولیدشده باید اسلایدهای پنهان را شامل شود یا خیر. مقدار پیش‌فرض **false** است. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | مشخص می‌کند آیا هنگام ذخیرهٔ ارائه، پیوندهای هیپرلینک با فراخوانی JavaScript رد شوند یا نه. **bool** را می‌نویسد. مقدار پیش‌فرض **false** است. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | شیئی را برمی‌گرداند یا تنظیم می‌کند که هشدارها را دریافت کرده و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا لغو شود. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) را می‌نویسد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای اشتراک‌گذاری‌شده) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید مستقیم فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید مستقیم فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش [Object.ToString()](../../system/object/tostring/) در C# است. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای برداشتن قفل با عبارت lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیم فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیم فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
|  [XpsOptions](./xpsoptions/)() | سازندهٔ پیش‌فرض. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌سازد. |

## نکات

The following example shows how to converting presentations to XPS using default settings. 
```cpp
// یک شیء Presentation را ایجاد می‌کند که یک فایل ارائه را نمایان می‌سازد
auto pres = System::MakeObject<Presentation>(u"Convert_XPS.pptx");

// ذخیرهٔ ارائه به سند XPS
pres->Save(u"XPS_Output_Without_XPSOption_out.xps", SaveFormat::Xps);
```
 The following example shows how to converting presentations to XPS using custom settings. 
```cpp
// یک شیء Presentation را ایجاد می‌کند که یک فایل ارائه را نمایان می‌سازد
auto pres = System::MakeObject<Presentation>(u"Convert_XPS_Options.pptx");

// یک شیء از کلاس TiffOptions را ایجاد می‌کند
System::SharedPtr<XpsOptions> options = System::MakeObject<XpsOptions>();
// MetaFiles را به صورت PNG ذخیره می‌کند
options->set_SaveMetafilesAsPng(true);
// ارائه را به سند XPS ذخیره می‌کند
pres->Save(u"XPS_With_Options_out.xps", SaveFormat::Xps, options);
```

## موارد مرتبط

* کلاس [SaveOptions](../saveoptions/)
* کلاس [IXpsOptions](../ixpsoptions/)
* فضای نام [Aspose::Slides::Export](../)
* کتابخانه [Aspose.Slides](../../)