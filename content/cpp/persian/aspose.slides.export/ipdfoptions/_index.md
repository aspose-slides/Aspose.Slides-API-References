---
title: IPdfOptions
second_title: مرجع API Aspose.Slides برای C++
description: گزینه‌هایی را فراهم می‌کند که نحوه ذخیره یک ارائه در قالب Pdf را کنترل می‌کنند.
type: docs
weight: 274
url: /fa/aspose.slides.export/ipdfoptions/
---
## IPdfOptions کلاس

Provides options that control how a presentation is saved in Pdf format.

```cpp
class IPdfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## متدها

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | آبجکت‌ها را با استفاده از [Object.Equals](../../system/object/equals/) سمانتیک‌های C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | آبجکت‌های نوع مراجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | آبجکت‌های نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | اگر **true** باشد، رنگ شفاف مشخص‌شده را بر روی تصویر اعمال می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | اگر **true** باشد، رنگ شفاف مشخص‌شده را بر روی تصویر اعمال می‌کند. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() | مجموعه‌ای از پرچم‌ها را شامل می‌شود که مشخص می‌کند کدام دسترسی‌ها هنگام باز شدن سند با دسترسی کاربر باید اعطا شود. ببینید [PdfAccessPermissions](../pdfaccesspermissions/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() | یک آرایه از نام‌های تعریف‌شده توسط کاربر برای خانواده‌های قلم را برمی‌گرداند که [Aspose.Slides](../../aspose.slides/) باید آن‌ها را عمومی در نظر بگیرد. بخوانید [System::String](../../system/string/)[]. |
| virtual **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() | اگر **true** باشد، رنگ شفاف مشخص‌شده را بر روی تصویر اعمال می‌کند. |
| virtual **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() | نشان می‌دهد آیا فشرده‌سازی مؤثرترین (به جای پیش‌فرض) برای هر تصویر باید به‌طور خودکار انتخاب شود. اگر به **bool**.true تنظیم شود، برای هر تصویر در ارائه، الگوریتم فشرده‌سازی مناسب‌ترین انتخاب می‌شود که منجر به حجم کوچکتر سند PDF خروجی می‌شود. |
| virtual [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() | سطح انطباق موردنظر برای سند PDF تولید شده. بخوانید [PdfCompliance](../pdfcompliance/). |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | قلم استفاده‌شده را در صورتی که قلم منبع یافت نشود برمی‌گرداند. می‌خواند [System::String](../../system/string/). |
| virtual **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() | اگر **bool** صحیح باشد، قاب مشکی دور هر اسلاید رسم می‌کند. بخوانید **bool**. |
| virtual **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() | مشخص می‌کند آیا تمام نویسه‌های قلم باید جاسازی شوند یا فقط زیرمجموعه‌ای استفاده شود. بخوانید **bool**. |
| virtual **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() | اگر **bool** صحیح باشد، قلم‌های TrueType برای نویسه‌های ASCII 32-127 جاسازی می‌شوند. [Fonts](../../aspose.slides/fonts/) برای کدهای کاراکتر بالاتر از 127 همیشه جاسازی می‌شوند. بخوانید **bool**. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | سبک بصری گرادیان را برمی‌گرداند. بخوانید [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() | رنگ شفاف تصویر را دریافت می‌کند. |
| virtual **bool** [get_IncludeOleData](./get_includeoledata/)() | اگر **bool** صحیح باشد، تمام داده‌های OLE از ارائه به فایل‌های جاسازی‌شده در PDF خروجی تبدیل می‌شود. بخوانید **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | گزینه‌هایی را فراهم می‌کند که ظاهر اشیای [Ink](../../aspose.slides.ink/) را در سند صادرشده کنترل می‌کند. فقط‌خواندنی [IInkOptions](../iinkoptions/) |
| virtual **uint8_t** [get_JpegQuality](./get_jpegquality/)() | مقداری را برمی‌گرداند که کیفیت تصویر JPEG داخل سند PDF را تعیین می‌کند. بخوانید **uint8_t**. |
| virtual [System::String](../../system/string/) [get_Password](./get_password/)() | تنظیم رمز عبور کاربر برای محافظت از سند PDF. بخوانید [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | یک شیء callback برای ذخیره‌سازی به‌روزرسانی‌های پیشرفت به درصد را نشان می‌دهد. ببینید [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() | نشان می‌دهد آیا متن باید به‌عنوان bitmap رستر شود و به PDF ذخیره شود وقتی قلم از سبک بولد پشتیبانی نمی‌کند. این روش می‌تواند کیفیت متن در PDF خروجی را برای برخی قلم‌ها بهبود بخشد. بخوانید **bool**. |
| virtual **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() | اگر **bool** صحیح باشد، تمام متافایل‌های استفاده‌شده در یک ارائه به تصاویر PNG تبدیل می‌شوند. بخوانید **bool**. |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | مشخص می‌کند آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. پیش‌فرض **false** است. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | مشخص می‌کند آیا هنگام ذخیره‌سازی ارائه، لینک‌های حاوی فراخوانی‌های JavaScript نادیده گرفته شوند یا نه. بخوانید **bool**. مقدار پیش‌فرض **false** است. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | حالت قرارگیری اسلایدها بر روی صفحه هنگام صادرات ارائه را دریافت می‌کند [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual **float** [get_SufficientResolution](./get_sufficientresolution/)() | مقداری را برمی‌گرداند که وضوح تصاویر داخل سند PDF را تعیین می‌کند. |
| virtual [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() | نوع فشرده‌سازی که برای تمام محتوای متنی سند استفاده می‌شود را مشخص می‌کند. بخوانید [PdfTextCompression](../pdftextcompression/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | شیئی را برمی‌گرداند که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود. بخوانید [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیای سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل اپراتور 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با بیان C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور تخصیص. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | آبجکت‌ها را براساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | آبجکت‌ها را براساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقدار نوع مقدار را با nullptr به‌صورت مرجعی مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) | مجموعه‌ای از پرچم‌ها را شامل می‌شود که مشخص می‌کند کدام دسترسی‌ها هنگام باز شدن سند با دسترسی کاربر باید اعطا شود. ببینید [PdfAccessPermissions](../pdfaccesspermissions/). |
| virtual void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) | آرایه‌ای از نام‌های تعریف‌شده توسط کاربر برای خانواده‌های قلم را تنظیم می‌کند که [Aspose.Slides](../../aspose.slides/) باید آن را عمومی در نظر بگیرد. بنویسید [System::String](../../system/string/)[]. |
| virtual void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) | اگر **true** باشد، رنگ شفاف مشخص‌شده را بر روی تصویر اعمال می‌کند. |
| virtual void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) | نشان می‌دهد آیا فشرده‌سازی مؤثرترین (به جای پیش‌فرض) برای هر تصویر باید به‌طور خودکار انتخاب شود. اگر به **bool**.true تنظیم شود، برای هر تصویر در ارائه، الگوریتم فشرده‌سازی مناسب‌ترین انتخاب می‌شود که منجر به حجم کوچکتر سند PDF خروجی می‌شود. |
| virtual void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) | سطح انطباق موردنظر برای سند PDF تولید شده. بنویسید [PdfCompliance](../pdfcompliance/). |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | قلم استفاده‌شده را در صورتی که قلم منبع یافت نشود تنظیم می‌کند. می‌نویسد [System::String](../../system/string/). |
| virtual void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) | اگر **bool** صحیح باشد، قاب مشکی دور هر اسلاید رسم می‌کند. بنویسید **bool**. |
| virtual void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) | مشخص می‌کند آیا تمام نویسه‌های قلم باید جاسازی شوند یا فقط زیرمجموعه‌ای استفاده شود. بنویسید **bool**. |
| virtual void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) | اگر **bool** صحیح باشد، قلم‌های TrueType برای نویسه‌های ASCII 32-127 جاسازی می‌شوند. [Fonts](../../aspose.slides/fonts/) برای کدهای کاراکتر بالاتر از 127 همیشه جاسازی می‌شوند. بنویسید **bool**. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | سبک بصری گرادیان را تنظیم می‌کند. بنویسید [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) | رنگ شفاف تصویر را تنظیم می‌کند. |
| virtual void [set_IncludeOleData](./set_includeoledata/)(**bool**) | اگر **bool** صحیح باشد، تمام داده‌های OLE را از ارائه به فایل‌های جاسازی‌شده در PDF خروجی تبدیل می‌کند. بنویسید **bool**. |
| virtual void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) | مقداری را تنظیم می‌کند که کیفیت تصویر JPEG داخل سند PDF را تعیین می‌کند. بنویسید **uint8_t**. |
| virtual void [set_Password](./set_password/)([System::String](../../system/string/)) | تنظیم رمز عبور کاربر برای محافظت از سند PDF. بنویسید [System::String](../../system/string/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | یک شیء callback برای ذخیره‌سازی به‌روزرسانی‌های پیشرفت به درصد را نشان می‌دهد. ببینید [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) | نشان می‌دهد آیا متن باید به‌عنوان bitmap رستر شود و به PDF ذخیره شود وقتی قلم از سبک بولد پشتیبانی نمی‌کند. این روش می‌تواند کیفیت متن در PDF خروجی را برای برخی قلم‌ها بهبود بخشد. بنویسید **bool**. |
| virtual void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) | اگر **bool** صحیح باشد، تمام متافایل‌های استفاده‌شده در یک ارائه به تصاویر PNG تبدیل می‌شوند. بنویسید **bool**. |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | مشخص می‌کند آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. پیش‌فرض **false** است. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | مشخص می‌کند آیا هنگام ذخیره‌سازی ارائه، لینک‌های حاوی فراخوانی‌های JavaScript نادیده گرفته شوند یا نه. بنویسید **bool**. مقدار پیش‌فرض **false** است. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | حالت قرارگیری اسلایدها بر روی صفحه هنگام صادرات ارائه را تنظیم می‌کند [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual void [set_SufficientResolution](./set_sufficientresolution/)(**float**) | مقدار تعیین‌کننده وضوح تصاویر داخل سند PDF را تنظیم می‌کند. |
| virtual void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) | نوع فشرده‌سازی که برای تمام محتوای متنی سند استفاده می‌شود را مشخص می‌کند. بنویسید [PdfTextCompression](../pdftextcompression/). |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | شیئی را تنظیم می‌کند که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود. بنویسید [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان سوئیچ کردن اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از smart pointers یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به جای آن از smart pointers یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیای سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری با بیان C# lock() را باز می‌کند. مستقیماً فراخوانی کنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از smart pointers یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از smart pointers یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |
## موارد مرتبط

* کلاس [ISaveOptions](../isaveoptions/)
* فضای‌نام [Aspose::Slides::Export](../)
* کتابخانه [Aspose.Slides](../../)