---
title: PdfOptions
second_title: مرجع API Aspose.Slides برای C++
description: گزینه‌هایی را فراهم می‌کند که نحوهٔ ذخیرهٔ یک ارائه را در قالب Pdf کنترل می‌کند.
type: docs
weight: 573
url: /fa/aspose.slides.export/pdfoptions/
---
## کلاس PdfOptions

Provides options that control how a presentation is saved in Pdf format.

```cpp
class PdfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::IPdfOptions
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقادیری نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقادیری نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای موارد داخلی. |
| [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() override | مجموعه‌ای از پرچم‌ها را شامل می‌شود که مشخص می‌کند چه مجوزهای دسترسی‌ای هنگام باز کردن سند با دسترسی کاربر اعطا شوند. ببینید [PdfAccessPermissions](../pdfaccesspermissions/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() override | یک آرایه از نام‌های تعریف‌شده توسط کاربر برای خانواده‌های فونت که [Aspose.Slides](../../aspose.slides/) باید به‌عنوان عمومی در نظر بگیرد، بازمی‌گرداند. خواندن [System::String](../../system/string/)[]. |
| **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() override | اگر **true** باشد، رنگ شفاف مشخص شده را بر روی تصویر اعمال می‌کند. |
| **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() override | نشان می‌دهد آیا فشرده‌سازی مؤثرترین (به‌جای پیش‌فرض) برای هر تصویر باید به‌صورت خودکار انتخاب شود. اگر به **bool**.true تنظیم شود، برای هر تصویر در ارائه، بهینه‌ترین الگوریتم فشرده‌سازی انتخاب می‌شود که منجر به کوچکتر شدن اندازه سند PDF خروجی می‌گردد. |
| [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() override | سطح انطباق مطلوب برای سند PDF تولید شده. خواندن [PdfCompliance](../pdfcompliance/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | فونتی را بازمی‌گرداند که در صورت عدم یافتن فونت منبع استفاده می‌شود. خواندن [System::String](../../system/string/). |
| **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() override | اگر **bool** صحیح باشد، قاب سیاه اطراف هر اسلاید رسم می‌شود. خواندن **bool**. |
| **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() override | مشخص می‌کند آیا همهٔ کاراکترهای فونت باید جاسازی شوند یا فقط زیرمجموعه‌ای استفاده شود. خواندن **bool**. |
| **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() override | مشخص می‌کند آیا [Aspose.Slides](../../aspose.slides/) فونت‌های عمومی را برای متن ASCII (دامنه کد 33..127) جاسازی خواهد کرد. [Fonts](../../aspose.slides/fonts/) برای کدهای کاراکتر بزرگتر از 127 همیشه جاسازی می‌شوند. فهرست فونت‌های عمومی شامل ۱۴ فونت پایه PDF و فونت‌های اضافی تعیین‌شده توسط کاربر است. خواندن **bool**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | سبک بصری گرادیان را بازمی‌گرداند. خواندن [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() override | رنگ شفاف تصویر را دریافت می‌کند. |
| **bool** [get_IncludeOleData](./get_includeoledata/)() override | اگر **bool** صحیح باشد، تمام داده‌های OLE از ارائه به فایل‌های جاسازی‌شده در PDF خروجی تبدیل می‌شوند. خواندن **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | گزینه‌هایی را فراهم می‌کند که ظاهر اشیاء [Ink](../../aspose.slides.ink/) را در سند صادرشده کنترل می‌کند. فقط-خواندنی [IInkOptions](../iinkoptions/) |
| **uint8_t** [get_JpegQuality](./get_jpegquality/)() override | مقداری را بازمی‌گرداند که کیفیت تصاویر JPEG داخل سند PDF را تعیین می‌کند. خواندن **uint8_t**. |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | تنظیم رمز عبور کاربر برای حفاظت از سند PDF. خواندن [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | یک شیء بازخوردی را نمایندگی می‌کند برای ذخیره‌سازی به‌روزرسانی‌های پیشرفت به درصد. ببینید [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() override | نشان می‌دهد آیا متن باید به‌صورت بیت‌مپ رستر شده و در PDF ذخیره شود وقتی فونت از استایل بولد پشتیبانی نمی‌کند. این روش می‌تواند کیفیت متن در PDF خروجی را برای برخی فونت‌ها بهبود بخشد. خواندن **bool**. |
| **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() override | اگر **bool** صحیح باشد، تمام متافایل‌های استفاده‌شده در یک ارائه به تصاویر PNG تبدیل می‌شوند. خواندن **bool**. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | مشخص می‌کند آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. پیش‌فرض **false** است. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | مشخص می‌کند آیا هنگام ذخیره‌سازی ارائه، پیوندهای فراخوانی‌دار JavaScript رد شوند یا نه. خواندن **bool**. مقدار پیش‌فرض **false** است. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | حالت قرارگیری اسلایدها روی صفحه هنگام صادر کردن یک ارائه [ISlidesLayoutOptions](../islideslayoutoptions/) را دریافت می‌کند. |
| **float** [get_SufficientResolution](./get_sufficientresolution/)() override | مقدار تعیین‌کننده وضوح تصاویر داخل سند PDF را بازمی‌گرداند. |
| [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() override | نوع فشرده‌سازی مورد استفاده برای تمام محتوای متنی در سند را مشخص می‌کند. خواندن [PdfTextCompression](../pdftextcompression/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | یک شیء را بازمی‌گرداند یا تنظیم می‌کند که هشدارها را دریافت کند و تصمیم بگیرد آیا فرآیند بارگذاری ادامه یابد یا قطع شود. خواندن [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نماینده یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' C#. |
| void [Lock](../../system/object/lock/)() | اجرا کننده قفل‌گذاری عبارت C# lock(). مستقیماً فراخوانی کنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
|  [PdfOptions](./pdfoptions/)() | سازندهٔ پیش‌فرض. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجعی شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) override | مجموعه‌ای از پرچم‌ها را شامل می‌شود که مشخص می‌کند چه مجوزهای دسترسی‌ای هنگام باز کردن سند با دسترسی کاربر اعطا شوند. ببینید [PdfAccessPermissions](../pdfaccesspermissions/). |
| void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) override | یک آرایه از نام‌های تعریف‌شده توسط کاربر برای خانواده‌های فونت که [Aspose.Slides](../../aspose.slides/) باید به‌عنوان عمومی در نظر بگیرد، تنظیم می‌کند. نوشتن [System::String](../../system/string/)[]. |
| void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) override | اگر **true** باشد، رنگ شفاف مشخص شده را بر روی تصویر اعمال می‌کند. |
| void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) override | نشان می‌دهد آیا فشرده‌سازی مؤثرترین (به‌جای پیش‌فرض) برای هر تصویر باید به‌صورت خودکار انتخاب شود. اگر به **bool**.true تنظیم شود، برای هر تصویر در ارائه، بهینه‌ترین الگوریتم فشرده‌سازی انتخاب می‌شود که منجر به کوچکتر شدن اندازه سند PDF خروجی می‌گردد. |
| void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) override | سطح انطباق مطلوب برای سند PDF تولید شده. نوشتن [PdfCompliance](../pdfcompliance/). |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | فونت مورد استفاده را در صورت عدم یافتن فونت منبع تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) override | اگر **bool** صحیح باشد، قاب سیاه اطراف هر اسلاید رسم می‌شود. نوشتن **bool**. |
| void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) override | مشخص می‌کند آیا همهٔ کاراکترهای فونت باید جاسازی شوند یا فقط زیرمجموعه‌ای استفاده شود. نوشتن **bool**. |
| void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) override | مشخص می‌کند آیا [Aspose.Slides](../../aspose.slides/) فونت‌های عمومی را برای متن ASCII (دامنه کد 33..127) جاسازی خواهد کرد. [Fonts](../../aspose.slides/fonts/) برای کدهای کاراکتر بزرگتر از 127 همیشه جاسازی می‌شوند. فهرست فونت‌های عمومی شامل ۱۴ فونت پایه PDF و فونت‌های اضافی تعیین‌شده توسط کاربر است. نوشتن **bool**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | سبک بصری گرادیان را تنظیم می‌کند. نوشتن [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) override | رنگ شفاف تصویر را تنظیم می‌کند. |
| void [set_IncludeOleData](./set_includeoledata/)(**bool**) override | اگر **bool** صحیح باشد، تمام داده‌های OLE از ارائه به فایل‌های جاسازی‌شده در PDF خروجی تبدیل می‌شوند. نوشتن **bool**. |
| void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) override | مقدار تعیین‌کننده کیفیت تصاویر JPEG داخل سند PDF را تنظیم می‌کند. نوشتن **uint8_t**. |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | تنظیم رمز عبور کاربر برای حفاظت از سند PDF. نوشتن [System::String](../../system/string/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | یک شیء بازخوردی را نمایندگی می‌کند برای ذخیره‌سازی به‌روزرسانی‌های پیشرفت به درصد. ببینید [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) override | نشان می‌دهد آیا متن باید به‌صورت بیت‌مپ رستر شده و در PDF ذخیره شود وقتی فونت از استایل بولد پشتیبانی نمی‌کند. این روش می‌تواند کیفیت متن در PDF خروجی را برای برخی فونت‌ها بهبود بخشد. نوشتن **bool**. |
| void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) override | اگر **bool** صحیح باشد، تمام متافایل‌های استفاده‌شده در یک ارائه به تصاویر PNG تبدیل می‌شوند. نوشتن **bool**. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | مشخص می‌کند آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. پیش‌فرض **false** است. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | مشخص می‌کند آیا هنگام ذخیره‌سازی ارائه، پیوندهای فراخوانی‌دار JavaScript رد شوند یا نه. نوشتن **bool**. مقدار پیش‌فرض **false** است. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | حالت قرارگیری اسلایدها روی صفحه هنگام صادر کردن یک ارائه [ISlidesLayoutOptions](../islideslayoutoptions/) را تنظیم می‌کند. |
| void [set_SufficientResolution](./set_sufficientresolution/)(**float**) override | مقدار تعیین‌کننده وضوح تصاویر داخل سند PDF را تنظیم می‌کند. |
| void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) override | نوع فشرده‌سازی مورد استفاده برای تمام محتوای متنی در سند را مشخص می‌کند. نوشتن [PdfTextCompression](../pdftextcompression/). |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | یک شیء را بازمی‌گرداند یا تنظیم می‌کند که هشدارها را دریافت کند و تصمیم بگیرد آیا فرآیند بارگذاری ادامه یابد یا قطع شود. نوشتن [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگوی یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌سازد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و بازمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | اجرای سازهٔ C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | اجرای باز کردن قفل عبارت C# lock(). مستقیماً فراخوانی کنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## توضیحات

مثال زیر نشان می‌دهد چگونه پاورپوینت را با گزینه‌های سفارشی به PDF تبدیل کنید. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// یک شیء از کلاس PdfOptions ایجاد می‌کند
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// کیفیت Jpeg را تنظیم می‌کند
pdfOptions->set_JpegQuality(90);
// رفتار متافایل‌ها را تنظیم می‌کند
pdfOptions->set_SaveMetafilesAsPng(true);
// سطح فشرده‌سازی متن را تنظیم می‌کند
pdfOptions->set_TextCompression(PdfTextCompression::Flate);
// استاندارد PDF را تعریف می‌کند
pdfOptions->set_Compliance(PdfCompliance::Pdf15);
// ارائه را به‌صورت PDF ذخیره می‌کند
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
مثال زیر نشان می‌دهد چگونه پاورپوینت را با اسلایدهای مخفی به PDF تبدیل کنید. 
```cpp
// یک شئ از کلاس Presentation که نمایانگر یک فایل PowerPoint است را ایجاد می‌کند
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// یک شئ از کلاس PdfOptions را ایجاد می‌کند
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// اسلایدهای مخفی را اضافه می‌کند
pdfOptions->set_ShowHiddenSlides(true);
// ارائه را به‌صورت PDF ذخیره می‌کند
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
مثال زیر نشان می‌دهد چگونه پاورپوینت را به PDF حفاظتی با رمز عبور تبدیل کنید. 
```cpp
// یک شیء Presentation که نمایانگر یک فایل PowerPoint است را ایجاد می‌کند
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();

// گذرواژه PDF و مجوزهای دسترسی را تنظیم می‌کند
pdfOptions->set_Password(u"password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
// ارائه را به‌صورت PDF ذخیره می‌کند
presentation->Save(u"PPTX-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
مثال زیر نشان می‌دهد چگونه پاورپوینت را با یادداشت‌ها به PDF تبدیل کنید. 
```cpp
// یک شیء Presentation که نمایانگر یک فایل ارائه است را ایجاد می‌کند
auto presentation = System::MakeObject<Presentation>(u"SelectedSlides.pptx");

auto auxPresentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auxPresentation->get_Slides()->InsertClone(0, slide);

// Setting Slide Type and Size
auxPresentation->get_SlideSize()->SetSize(612.F, 792.F, SlideSizeScaleType::EnsureFit);

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
pdfOptions->set_SlidesLayoutOptions(slidesLayoutOptions);
auxPresentation->Save(u"PDFnotes_out.pdf", SaveFormat::Pdf, pdfOptions);
```

## مراجع

* کلاس [SaveOptions](../saveoptions/)
* کلاس [IPdfOptions](../ipdfoptions/)
* فضای‌نام [Aspose::Slides::Export](../)
* کتابخانه [Aspose.Slides](../../)