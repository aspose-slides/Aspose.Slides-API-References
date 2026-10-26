---
title: MarkdownSaveOptions
second_title: مرجع API Aspose.Slides برای C++
description: گزینه‌هایی را که کنترل می‌کنند ارائه چگونه به markdown ذخیره شود، نشان می‌دهد.
type: docs
weight: 547
url: /fa/aspose.slides.export/markdownsaveoptions/
---
## کلاس MarkdownSaveOptions

نمایانگر گزینه‌هایی است که کنترل می‌کند چگونه ارائه باید به markdown ذخیره شود.

```cpp
class MarkdownSaveOptions : public Aspose::Slides::Export::SaveOptions
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از قواعد [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [System::String](../../system/string/) [get_BasePath](./get_basepath/)() const | مسیر پایه‌ای را که سند همراه با منابع در آن ذخیره خواهد شد مشخص می‌کند. مقدار پیش‌فرض، پوشهٔ جاری برنامه است. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | فونتی را که در صورت عدم یافتن فونت منبع استفاده می‌شود، باز می‌گرداند. [System::String](../../system/string/) را می‌خواند. |
| [MarkdownExportType](../markdownexporttype/) [get_ExportType](./get_exporttype/)() const | مشخصات markdown برای تبدیل ارائه را تعیین می‌کند. مقدار پیش‌فرض **TextOnly** است. |
| [Aspose::Slides::Export::Flavor](../flavor/) [get_Flavor](./get_flavor/)() const | مشخصات markdown برای تبدیل ارائه را تعیین می‌کند. مقدار پیش‌فرض **Multi-markdown** است. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | سبک بصری گرادیان را باز می‌گرداند. [GradientStyle](../../aspose.slides/gradientstyle/) را بخوانید. |
| [Aspose::Slides::Export::HandleRepeatedSpaces](../handlerepeatedspaces/) [get_HandleRepeatedSpaces](./get_handlerepeatedspaces/)() const | نحوهٔ برخورد با کاراکترهای فضای معمولی تکراری هنگام صادرات به Markdown را مشخص می‌کند. |
| [System::String](../../system/string/) [get_ImagesSaveFolderName](./get_imagessavefoldername/)() const | نام پوشه‌ای را که تصاویر در آن ذخیره می‌شوند مشخص می‌کند. مقدار پیش‌فرض **[Images](../../aspose.slides/images/)** است. |
| [Aspose::Slides::Export::NewLineType](../newlinetype/) [get_NewLineType](./get_newlinetype/)() const | مشخص می‌کند سند تولید شده باید خطوط جدید \r(Macintosh) یا \n(Unix) یا \r\n(Windows) داشته باشد. مقدار پیش‌فرض **Unix** است. |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | یک شیء callback برای به‌روزرسانی پیشرفت ذخیره‌سازی به درصد را نشان می‌دهد. به [IProgressCallback](../../aspose.slides/iprogresscallback/) مراجعه کنید. |
| **bool** [get_RemoveEmptyLines](./get_removeemptylines/)() const | اگر به **true** تنظیم شود، خطوط خالی یا فقط حاوی فاصله را از خروجی نهایی Markdown حذف می‌کند. مقدار پیش‌فرض **false** است. |
| **bool** [get_ShowComments](./get_showcomments/)() const | مشخص می‌کند آیا سند تولید شده نظرات را نشان دهد یا نه. مقدار پیش‌فرض **false** است. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() const | مشخص می‌کند آیا سند تولید شده اسلایدهای مخفی را شامل شود یا نه. مقدار پیش‌فرض **false** است. |
| **bool** [get_ShowSlideNumber](./get_showslidenumber/)() const | مشخص می‌کند آیا سند تولید شده شماره هر اسلاید را نشان دهد یا نه. مقدار پیش‌فرض **false** است. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | مشخص می‌کند آیا هنگام ذخیره ارائه پیوندهای دارای فراخوانی JavaScript نادیده گرفته شوند یا نه. **bool** را بخوانید. مقدار پیش‌فرض **false** است. |
| [System::String](../../system/string/) [get_SlideNumberFormat](./get_slidenumberformat/)() | رشته قالبی که برای سرصفحهٔ شماره اسلایدها در خروجی Markdown استفاده می‌شود را دریافت می‌کند. قالب باید مکان‌دار \"{0}\" را شامل باشد که هنگام صادرات با اندیس اسلاید جایگزین می‌شود. مثال: \"# Slide {0}\" به \"# Slide 1\", \"# Slide 2\" و … تبدیل می‌شود. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | یک شیء را که هشدارها را دریافت می‌کند و تصمیم می‌گیرد فرآیند بارگذاری ادامه یابد یا قطع شود، باز می‌گرداند یا تنظیم می‌کند. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) را بخوانید. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. امکان هش‌گذاری اشیاء سفارشی را فعال می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C# است. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با عبارت lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهدارنده [LockContext](../../system/lockcontext/) استفاده کنید. |
|  [MarkdownSaveOptions](./markdownsaveoptions/)() | سازنده. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان کلون کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت نسخهٔ کپی در زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت نسخهٔ کپی در زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر پایهٔ مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر پایهٔ مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقدار شیء از نوع مقدار را با nullptr مقایسه مرجعی می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ مرجع اشتراک‌گذاری شده را به مقدار مشخص شده کاهش می‌دهد. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_BasePath](./set_basepath/)([System::String](../../system/string/)) | مسیر پایه‌ای را که سند همراه با منابع در آن ذخیره خواهد شد مشخص می‌کند. مقدار پیش‌فرض، پوشهٔ جاری برنامه است. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | فونتی را که در صورت عدم یافتن فونت منبع استفاده می‌شود تنظیم می‌کند. [System::String](../../system/string/) را می‌نویسد. |
| void [set_ExportType](./set_exporttype/)([MarkdownExportType](../markdownexporttype/)) | مشخصات markdown برای تبدیل ارائه را تعیین می‌کند. مقدار پیش‌فرض **TextOnly** است. |
| void [set_Flavor](./set_flavor/)([Aspose::Slides::Export::Flavor](../flavor/)) | مشخصات markdown برای تبدیل ارائه را تعیین می‌کند. مقدار پیش‌فرض **Multi-markdown** است. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | سبک بصری گرادیان را تنظیم می‌کند. [GradientStyle](../../aspose.slides/gradientstyle/) را می‌نویسد. |
| void [set_HandleRepeatedSpaces](./set_handlerepeatedspaces/)([Aspose::Slides::Export::HandleRepeatedSpaces](../handlerepeatedspaces/)) | نحوهٔ برخورد با کاراکترهای فضای معمولی تکراری هنگام صادرات به Markdown را مشخص می‌کند. |
| void [set_ImagesSaveFolderName](./set_imagessavefoldername/)([System::String](../../system/string/)) | نام پوشه‌ای را که تصاویر در آن ذخیره می‌شوند مشخص می‌کند. مقدار پیش‌فرض **[Images](../../aspose.slides/images/)** است. |
| void [set_NewLineType](./set_newlinetype/)([Aspose::Slides::Export::NewLineType](../newlinetype/)) | مشخص می‌کند سند تولید شده باید خطوط جدید \r(Macintosh) یا \n(Unix) یا \r\n(Windows) داشته باشد. مقدار پیش‌فرض **Unix** است. |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | یک شیء callback برای به‌روزرسانی پیشرفت ذخیره‌سازی به درصد را نشان می‌دهد. به [IProgressCallback](../../aspose.slides/iprogresscallback/) مراجعه کنید. |
| void [set_RemoveEmptyLines](./set_removeemptylines/)(**bool**) | اگر به **true** تنظیم شود، خطوط خالی یا فقط حاوی فاصله را از خروجی نهایی Markdown حذف می‌کند. مقدار پیش‌فرض **false** است. |
| void [set_ShowComments](./set_showcomments/)(**bool**) | مشخص می‌کند آیا سند تولید شده نظرات را نشان دهد یا نه. مقدار پیش‌فرض **false** است. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | مشخص می‌کند آیا سند تولید شده اسلایدهای مخفی را شامل شود یا نه. مقدار پیش‌فرض **false** است. |
| void [set_ShowSlideNumber](./set_showslidenumber/)(**bool**) | مشخص می‌کند آیا سند تولید شده شماره هر اسلاید را نشان دهد یا نه. مقدار پیش‌فرض **false** است. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | مشخص می‌کند آیا هنگام ذخیره ارائه پیوندهای دارای فراخوانی JavaScript نادیده گرفته شوند یا نه. **bool** را بنویسید. مقدار پیش‌فرض **false** است. |
| void [set_SlideNumberFormat](./set_slidenumberformat/)([System::String](../../system/string/)) | رشته قالبی که برای سرصفحهٔ شماره اسلایدها در خروجی Markdown استفاده می‌شود را تنظیم می‌کند. قالب باید مکان‌دار \"{0}\" را شامل باشد که هنگام صادرات با اندیس اسلاید جایگزین می‌شود. مثال: \"# Slide {0}\" به \"# Slide 1\", \"# Slide 2\" و … تبدیل می‌شود. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | یک شیء را که هشدارها را دریافت می‌کند و تصمیم می‌گیرد فرآیند بارگذاری ادامه یابد یا قطع شود، باز می‌گرداند یا تنظیم می‌کند. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) را بنویسید. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به‌جای اشتراک‌گذاری) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع اشتراک‌گذاری شده را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع اشتراک‌گذاری شده را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع اشتراک‌گذاری شده را کاهش داده و باز می‌گرداند. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C# است. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | باز کردن قفل با عبارت lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهدارنده [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## تایپ‌دِف‌ها

| تایپ‌دِف | توضیح |
| --- | --- |
| [MarkdownImageSavingHandler](./markdownimagesavinghandler/) | در هنگام صادرات به Markdown برای هر تصویر غیر-SVG (bitmap یا metafile) فراخوانی می‌شود. برای استفاده از *link* مشخص شده **true** را برگردانید، یا برای اعمال منطق ذخیره‌سازی پیش‌فرض **false** را برگردانید. |
| [MarkdownSvgImageSavingHandler](./markdownsvgimagesavinghandler/) | در هنگام صادرات به Markdown برای هر تصویر SVG فراخوانی می‌شود. برای استفاده از *link* مشخص شده **true** را برگردانید، یا برای اعمال منطق ذخیره‌سازی پیش‌فرض **false** را برگردانید. |

## توضیحات

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<MarkdownSaveOptions> markdownSaveOptions = System::MakeObject<MarkdownSaveOptions>();
markdownSaveOptions->set_ShowHiddenSlides(true);
markdownSaveOptions->set_ShowSlideNumber(true);
markdownSaveOptions->set_Flavor(Flavor::Github);
markdownSaveOptions->set_ExportType(MarkdownExportType::Sequential);
markdownSaveOptions->set_NewLineType(NewLineType::Windows);

System::ArrayPtr<int32_t> slideIndices = System::MakeArray<int32_t>({1, 2, 3, 4, 5, 6, 7, 8, 9});

pres->Save(u"doc.md", slideIndices, SaveFormat::Md, markdownSaveOptions);
```

## موارد مرتبط

* کلاس [SaveOptions](../saveoptions/)
* فضای‌نام [Aspose::Slides::Export](../)
* کتابخانه [Aspose.Slides](../../)