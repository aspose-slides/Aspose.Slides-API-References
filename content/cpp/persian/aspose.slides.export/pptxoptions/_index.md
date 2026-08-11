---
title: PptxOptions
second_title: مرجع API Aspose.Slides برای C++
description: گزینه‌هایی را برای ذخیره‌سازی ارائه‌های OpenXml (PPTX، PPSX، POTX، PPTM، PPSM، POTM) نشان می‌دهد.
type: docs
weight: 599
url: /fa/aspose.slides.export/pptxoptions/
---
## PptxOptions کلاس

گزینه‌هایی را برای ذخیره‌سازی ارائه‌های OpenXml (PPTX، PPSX، POTX، PPTM، PPSM، POTM) نشان می‌دهد.

```cpp
class PptxOptions : public Aspose::Slides::Export::SaveOptions,
                    public Aspose::Slides::Export::IPptxOptions
```

## متدها

| Method | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [Aspose::Slides::Export::CompressionLevel](../compressionlevel/) [get_CompressionLevel](./get_compressionlevel/)() override | سطح فشرده‌سازی مورد استفاده هنگام ذخیره‌سازی سند ارائه را تعیین می‌کند. مقدار پیش‌فرض [CompressionLevel::Level6](../compressionlevel/) است. |
| [Aspose::Slides::Export::Conformance](../conformance/) [get_Conformance](./get_conformance/)() override | کلاس سازگاری که سند [Presentation](../../aspose.slides/presentation/) به آن متعهد است را تعیین می‌کند. مقدار پیش‌فرض [Aspose::Slides::Export::Conformance::Ecma376_2006](../conformance/) است. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | فونتی که در صورت نبود فونت منبع استفاده می‌شود را برمی‌گرداند. [System::String](../../system/string/) را می‌خواند. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | سبک بصری گرادینت را برمی‌گرداند. [GradientStyle](../../aspose.slides/gradientstyle/) را می‌خواند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | یک شیء بازگشت فراخوان برای به‌روزرسانی پیشرفت ذخیره‌سازی به درصد را نشان می‌دهد. ببینید [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_RefreshThumbnail](./get_refreshthumbnail/)() override | تعیین می‌کند آیا تصویر بندانگشتی ارائه تازه‌سازی شود یا نه. **bool** را می‌خواند. مقدار پیش‌فرض **true** است. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | تعیین می‌کند آیا هنگام ذخیره‌سازی ارائه، پیوندهای ابرمتنی با فراخوانی‌های JavaScript رد شوند یا نه. **bool** را می‌خواند. مقدار پیش‌فرض **false** است. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | شیئی را که هشدارها را دریافت می‌کند و تصمیم می‌گیرد فرآیند بارگذاری ادامه یابد یا لغو شود، برمی‌گرداند یا تنظیم می‌کند. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) را می‌خواند. |
| [Aspose::Slides::Export::Zip64Mode](../zip64mode/) [get_Zip64Mode](./get_zip64mode/)() override | تعیین می‌کند آیا قالب ZIP64 برای سند [Presentation](../../aspose.slides/presentation/) استفاده شود یا نه. مقدار پیش‌فرض [Zip64Mode::IfNecessary](../zip64mode/) است. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری بیانیه C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان تکثیر انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را می‌سازد. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت نسخهٔ کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت نسخهٔ کپی از زیرکلاس‌ها را فراهم می‌کند. |
|  [PptxOptions](./pptxoptions/)() | یک نمونه جدید از [PptxOptions](./) ایجاد می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع‌گونه شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_CompressionLevel](./set_compressionlevel/)([Aspose::Slides::Export::CompressionLevel](../compressionlevel/)) override | سطح فشرده‌سازی مورد استفاده هنگام ذخیره‌سازی سند ارائه را تعیین می‌کند. مقدار پیش‌فرض [CompressionLevel::Level6](../compressionlevel/) است. |
| void [set_Conformance](./set_conformance/)([Aspose::Slides::Export::Conformance](../conformance/)) override | کلاس سازگاری که سند [Presentation](../../aspose.slides/presentation/) به آن متعهد است را تعیین می‌کند. مقدار پیش‌فرض [Aspose::Slides::Export::Conformance::Ecma376_2006](../conformance/) است. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | فونت مورد استفاده در صورت عدم یافتن فونت منبع را تنظیم می‌کند. [System::String](../../system/string/) را می‌نویسد. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | سبک بصری گرادینت را تنظیم می‌کند. [GradientStyle](../../aspose.slides/gradientstyle/) را می‌نویسد. |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | یک شیء بازگشت فراخوان برای به‌روزرسانی پیشرفت ذخیره‌سازی به درصد را نشان می‌دهد. ببینید [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_RefreshThumbnail](./set_refreshthumbnail/)(**bool**) override | تعیین می‌کند آیا تصویر بندانگشتی ارائه تازه‌سازی شود یا نه. **bool** را می‌نویسد. مقدار پیش‌فرض **true** است. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | تعیین می‌کند آیا هنگام ذخیره‌سازی ارائه، پیوندهای ابرمتنی با فراخوانی‌های JavaScript رد شوند یا نه. **bool** را می‌نویسد. مقدار پیش‌فرض **false** است. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | شیئی را که هشدارها را دریافت می‌کند و تصمیم می‌گیرد فرآیند بارگذاری ادامه یابد یا لغو شود، برمی‌گرداند یا تنظیم می‌کند. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) را می‌نویسد. |
| void [set_Zip64Mode](./set_zip64mode/)([Aspose::Slides::Export::Zip64Mode](../zip64mode/)) override | تعیین می‌کند آیا قالب ZIP64 برای سند [Presentation](../../aspose.slides/presentation/) استفاده شود یا نه. مقدار پیش‌فرض [Zip64Mode::IfNecessary](../zip64mode/) است. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به جای اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع اشتراکی را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع اشتراکی را افزایش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ در عوض از smart pointers یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع اشتراکی را کاهش می‌دهد و برمی‌گرداند. نباید به‌صورت مستقیم صدا زده شود؛ در عوض از smart pointers یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری بیانیه C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ در عوض از smart pointers یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ در عوض از smart pointers یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## مراجع

* کلاس [SaveOptions](../saveoptions/)
* کلاس [IPptxOptions](../ipptxoptions/)
* فضای نام [Aspose::Slides::Export](../)
* کتابخانه [Aspose.Slides](../../)