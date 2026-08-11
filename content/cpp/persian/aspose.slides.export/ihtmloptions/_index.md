---
title: IHtmlOptions
second_title: مرجع API Aspose.Slides برای C++
description: گزینه‌های خروجی HTML را نشان می‌دهد.
type: docs
weight: 222
url: /fa/aspose.slides.export/ihtmloptions/
---
## IHtmlOptions کلاس

نمایانگر گزینه‌های خروجی HTML است.

```cpp
class IHtmlOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## متدها

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنی‌گذاری [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | فونتی را برمی‌گرداند که در صورتی که فونت منبع یافت نشود استفاده می‌شود. [System::String](../../system/string/) را می‌خواند. |
| virtual **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() | پرچم بولی نشان می‌دهد که آیا بخش‌های برش یافته به عنوان بخشی از سند باقی می‌مانند. اگر true باشد، بخش‌های برش یافته حذف می‌شوند، اگر false باشند، در سند سریال‌سازی می‌شوند (که ممکن است منجر به فایل بزرگتر شود). **bool** را می‌خواند. |
| virtual **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() | مقداری را دریافت می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود یا نه. وقتی به **true** تنظیم شود، لیگچرها در خروجی رندر غیرفعال می‌شوند. به طور پیش‌فرض، این ویژگی به **false** تنظیم شده است. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | سبک بصری گرادیانت را برمی‌گرداند. [GradientStyle](../../aspose.slides/gradientstyle/) را می‌خواند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHtmlFormatter](../ihtmlformatter/)\> [get_HtmlFormatter](./get_htmlformatter/)() | قالب HTML را برمی‌گرداند. [IHtmlFormatter](../ihtmlformatter/) را می‌خواند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | گزینه‌هایی را فراهم می‌کند که ظاهر اشیاء [Ink](../../aspose.slides.ink/) را در سند صادرشده کنترل می‌کند. [IInkOptions](../iinkoptions/) فقط خواندنی است. |
| virtual **uint8_t** [get_JpegQuality](./get_jpegquality/)() | مقداری را برمی‌گرداند که کیفیت تصاویر JPEG داخل سند PDF را تعیین می‌کند. **uint8_t** را می‌خواند. |
| virtual [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() | سطح فشرده‌سازی تصاویر را نشان می‌دهد. [PicturesCompression](../picturescompression/) را می‌خواند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | شیء callback را برای ذخیره‌سازی به‌روزرسانی‌های پیشرفت به درصد نمایش می‌دهد. به [IProgressCallback](../../aspose.slides/iprogresscallback/) مراجعه کنید. |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | مشخص می‌کند که آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. مقدار پیش‌فرض **false** است. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | مشخص می‌کند که آیا هنگام ذخیره ارائه، پیوندهای ابرمتنی با فراخوانی‌های JavaScript صرف‌نظر شوند یا نه. **bool** را می‌خواند. مقدار پیش‌فرض **false** است. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlideImageFormat](../islideimageformat/)\> [get_SlideImageFormat](./get_slideimageformat/)() | گزینه‌های قالب تصویر اسلاید را برمی‌گرداند. [ISlideImageFormat](../islideimageformat/) را می‌خواند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | حالت قرارگیری اسلایدها بر روی صفحه را هنگام صادرات ارائه [ISlidesLayoutOptions](../islideslayoutoptions/) دریافت می‌کند. |
| virtual **bool** [get_SvgResponsiveLayout](./get_svgresponsivelayout/)() | **true** برای حذف ویژگی‌های عرض و ارتفاع از محفظه SVG - که باعث می‌شود طرح‌بندی پاسخگو باشد. **false** در غیر این صورت. **bool** را می‌خواند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | شیئی را برمی‌گرداند که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا لغو شود. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) را می‌خواند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. هش‌سازی اشیاء سفارشی را فعال می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C# است. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | عملکرد قفل‌گذاری عبارت lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء sentinel [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساختن زیرکلاس‌های کپی را فعال می‌سازد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساختن زیرکلاس‌های کپی را فعال می‌سازد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر پایه مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر پایه مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | فونتی را تنظیم می‌کند که در صورتی که فونت منبع یافت نشود استفاده می‌شود. [System::String](../../system/string/) را می‌نویسد. |
| virtual void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) | پرچم بولی نشان می‌دهد که آیا بخش‌های برش یافته به عنوان بخشی از سند باقی می‌مانند. اگر true باشد، بخش‌های برش یافته حذف می‌شوند، اگر false باشند، در سند سریال‌سازی می‌شوند (که ممکن است منجر به فایل بزرگتر شود). **bool** را می‌نویسد. |
| virtual void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) | مقداری را تنظیم می‌کند که نشان می‌دهد آیا متن بدون لیگچر رندر می‌شود. **bool** را می‌نویسد. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | سبک بصری گرادیانت را تنظیم می‌کند. [GradientStyle](../../aspose.slides/gradientstyle/) را می‌نویسد. |
| virtual void [set_HtmlFormatter](./set_htmlformatter/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlFormatter](../ihtmlformatter/)\>) | قالب HTML را تنظیم می‌کند. [IHtmlFormatter](../ihtmlformatter/) را می‌نویسد. |
| virtual void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) | مقدارئی را تنظیم می‌کند که کیفیت تصاویر JPEG داخل سند PDF را تعیین می‌کند. **uint8_t** را می‌نویسد. |
| virtual void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) | سطح فشرده‌سازی تصاویر را نشان می‌دهد. [PicturesCompression](../picturescompression/) را می‌نویسد. |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | یک شیء callback را برای ذخیره‌سازی به‌روزرسانی‌های پیشرفت ... نشان می‌دهد. به [IProgressCallback](../../aspose.slides/iprogresscallback/) مراجعه کنید. |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | مشخص می‌کند که آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. مقدار پیش‌فرض **false** است. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | مشخص می‌کند که آیا هنگام ذخیره ارائه، پیوندهای ابرمتنی با فراخوانی‌های JavaScript صرف‌نظر شوند یا نه. **bool** را می‌نویسد. مقدار پیش‌فرض **false** است. |
| virtual void [set_SlideImageFormat](./set_slideimageformat/)([System::SharedPtr](../../system/sharedptr/)\<[ISlideImageFormat](../islideimageformat/)\>) | گزینه‌های قالب تصویر اسلاید را تنظیم می‌کند. [ISlideImageFormat](../islideimageformat/) را می‌نویسد. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | حالت قرارگیری اسلایدها بر روی صفحه را هنگام صادرات ارائه [ISlidesLayoutOptions](../islideslayoutoptions/) تنظیم می‌کند. |
| virtual void [set_SvgResponsiveLayout](./set_svgresponsivelayout/)(**bool**) | **true** برای حذف ویژگی‌های عرض و ارتفاع از محفظه SVG - که باعث می‌شود طرح‌بندی پاسخگو باشد. **false** در غیر این صورت. **bool** را می‌نویسد. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | شیئی را تنظیم می‌کند که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا لغو شود. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) را می‌نویسد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک Weak Pointer تنظیم می‌کند (به‌جای Shared). امکان تعویض اشاره‌گرها در کانتینرها به حالت weak را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و باز می‌گرداند. نباید به‌صورت مستقیم صدا زده شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C# است. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | عملکرد بازقفل‌گذاری عبارت lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## همچنین ببینید

* کلاس [ISaveOptions](../isaveoptions/)
* فضای نام [Aspose::Slides::Export](../)
* کتابخانه [Aspose.Slides](../../)