---
title: SVGOptions
second_title: مرجع API Aspose.Slides برای C++
description: نمایانگر یک گزینه SVG است.
type: docs
weight: 703
url: /fa/aspose.slides.export/svgoptions/
---
## SVGOptions کلاس

نمایانگر یک گزینه SVG است.

```cpp
class SVGOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISVGOptions
```

## متدها

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | مقایسهٔ اشیاء با استفاده از معنای [Object.Equals](../../system/object/equals/) در C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | مقایسهٔ اشیاء نوع مرجع در سبک C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | مقایسهٔ اشیاء نوع مقدار در سبک C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | شبیه‌سازی مقایسهٔ نقاط شناور به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر پایهٔ IEC 60559:1989، NaN برابر با هیچ مقداری نیست، حتی NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | شبیه‌سازی مقایسهٔ نقاط شناور به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر پایهٔ IEC 60559:1989، NaN برابر با هیچ مقداری نیست، حتی NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای استفاده داخلی. |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Default](./get_default/)() | تنظیمات پیش‌فرض را برمی‌گرداند. فقط‌خواندنی [SVGOptions](./). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | فونتی را که در صورت یافت نشدن فونت منبع استفاده می‌شود برمی‌گرداند. خواند [System::String](../../system/string/). |
| **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() override | یک پرچم بولی نشان می‌دهد که آیا بخش‌های برش خورده به عنوان بخشی از سند باقی می‌مانند یا نه. اگر true باشد، بخش‌های برش خورده حذف می‌شوند؛ اگر false باشند، در سند سریال‌سازی می‌شوند (که ممکن است منجر به فایل بزرگ‌تر شود). |
| **bool** [get_Disable3DText](./get_disable3dtext/)() override | تعیین می‌کند که آیا متن 3D در SVG غیرفعال است یا نه. خواند **bool**. |
| **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() override | مقداری را برمی‌گرداند که نشان می‌دهد آیا متن بدون استفاده از لیگاتور رندر می‌شود یا نه. وقتی به **true** تنظیم شود، لیگاتورها در خروجی رندر شده غیرفعال می‌شوند. به‌طور پیش‌فرض، این ویژگی به **false** تنظیم شده است. |
| **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() override | تقسیم گرادیان‌های FromCornerX و FromCenter را غیرفعال می‌کند. خواند **bool**. |
| **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() override | SVG 1.1 توانایی تعریف تو رفتگی برای مارکرها را ندارد. [Aspose.Slides](../../aspose.slides/) موتور نوشتن SVG برای این مشکل راه‌حلی دارد: انتهای خط با پیکان را برش می‌دهد تا خط با مارکرها تداخل نداشته باشد. این گزینه این رفتار را غیرفعال می‌کند. خواند **bool**. |
| [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() override | روشی برای مدیریت فونت‌های بارگذاری شده از خارج را تعیین می‌کند. خواند [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | سبک بصری گرادیان را برمی‌گرداند. خواند [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | گزینه‌هایی را فراهم می‌کند که ظاهر اشیاء [Ink](../../aspose.slides.ink/) را در سند صادر شده کنترل می‌کند. فقط‌خواندنی [IInkOptions](../iinkoptions/) |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | کیفیت رمزگذاری JPEG را تعیین می‌کند. خواند **int32_t**. |
| **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() override | حد پایین وضوح برای رستر‌سازی متافایل را برمی‌گرداند. خواند **int32_t**. |
| [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() override | سطح فشرده‌سازی تصاویر را نشان می‌دهد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | شیء callback برای ذخیره‌سازی به‌روزرسانی‌های پیشرفت به درصد را نشان می‌دهد. ببینید [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() override | یک رابط callback را برمی‌گرداند و تنظیم می‌کند که به کاربر امکان کنترل تبدیل شکل را می‌دهد. خواند [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Simple](./get_simple/)() | تنظیماتی را برای تولید ساده‌ترین و کوچک‌ترین فایل SVG برمی‌گرداند. فقط‌خواندنی [SVGOptions](./). |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | مشخص می‌کند که آیا هنگام ذخیرهٔ ارائه، پیوندهای فراخوانی‌کننده JavaScript رد شوند یا نه. خواند **bool**. مقدار پیش‌فرض **false** است. |
| **bool** [get_UseFrameRotation](./get_useframerotation/)() override | تعیین می‌کند که آیا هنگام رندر، چرخش مشخص‌شدهٔ شکل اجرا شود یا نه. خواند **bool**. مقدار پیش‌فرض true است. |
| **bool** [get_UseFrameSize](./get_useframesize/)() override | تعیین می‌کند که آیا قاب متن در ناحیه رندر گنجانده شود یا نه. خواند **bool**. مقدار پیش‌فرض false است. |
| **bool** [get_VectorizeText](./get_vectorizetext/)() override | تعیین می‌کند که آیا متن روی اسلاید به‌صورت گرافیک ذخیره شود یا نه. خواند **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | شیئی را برمی‌گرداند یا تنظیم می‌کند که هشدارها را دریافت کند و تصمیم بگیرد که فرآیند بارگذاری ادامه یابد یا خاتمه یابد. خواند [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_WYSIWYG](./get_wysiwyg/)() | تنظیماتی را برای تولید دقیق‌ترین فایل SVG برمی‌گرداند. فقط‌خواندنی [SVGOptions](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارندهٔ مرجع مرتبط با شیء را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر ‘is’ در C#. |
| void [Lock](../../system/object/lock/)() | قفل کردن بیان lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نظارتی [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. واقعاً چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را می‌دهد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. واقعاً چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را می‌دهد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخصی کاهش می‌دهد. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | فونتی را که در صورت یافت نشدن فونت منبع استفاده می‌شود تنظیم می‌کند. می‌نویسد [System::String](../../system/string/). |
| void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) override | یک پرچم بولی نشان می‌دهد که آیا بخش‌های برش خورده به عنوان بخشی از سند باقی می‌مانند یا نه. اگر **true** باشد، بخش‌های برش خورده حذف می‌شوند؛ اگر **false** باشند، در سند سریال‌سازی می‌شوند (که ممکن است منجر به فایل بزرگ‌تر شود). |
| void [set_Disable3DText](./set_disable3dtext/)(**bool**) override | تعیین می‌کند که آیا متن 3D در SVG غیرفعال است یا نه. می‌نویسد **bool**. |
| void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) override | مقداری را تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگاتور رندر شود یا نه. وقتی به **true** تنظیم شود، لیگاتورها در خروجی رندر غیرفعال می‌شوند. به‌طور پیش‌فرض، این ویژگی به **false** تنظیم شده است. |
| void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) override | تقسیم گرادیان‌های FromCornerX و FromCenter را غیرفعال می‌کند. می‌نویسد **bool**. |
| void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) override | SVG 1.1 توانایی تعریف تو رفتگی برای مارکرها را ندارد. [Aspose.Slides](../../aspose.slides/) موتور نوشتن SVG برای این مشکل راه‌حلی دارد: انتهای خط با پیکان را برش می‌دهد تا خط با مارکرها تداخل نداشته باشد. این گزینه این رفتار را غیرفعال می‌کند. می‌نویسد **bool**. |
| void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) override | روشی برای مدیریت فونت‌های بارگذاری‌شده از خارج را تعیین می‌کند. می‌نویسد [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | سبک بصری گرادیان را تنظیم می‌کند. می‌نویسد [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | کیفیت رمزگذاری JPEG را تعیین می‌کند. می‌نویسد **int32_t**. |
| void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) override | حد پایین وضوح برای رستر‌سازی متافایل را تنظیم می‌کند. می‌نویسد **int32_t**. |
| void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) override | سطح فشرده‌سازی تصاویر را نشان می‌دهد. |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | شیء callback برای ذخیره‌سازی به‌روزرسانی‌های پیشرفت به درصد را نشان می‌دهد. ببینید [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) override | یک رابط callback را برمی‌گرداند و تنظیم می‌کند که به کاربر امکان کنترل تبدیل شکل را می‌دهد. می‌نویسد [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | مشخص می‌کند که آیا هنگام ذخیرهٔ ارائه، پیوندهای فراخوانی‌کننده JavaScript رد شوند یا نه. می‌نویسد **bool**. مقدار پیش‌فرض **false** است. |
| void [set_UseFrameRotation](./set_useframerotation/)(**bool**) override | تعیین می‌کند که آیا هنگام رندر، چرخش مشخص‌شدهٔ شکل اجرا شود یا نه. می‌نویسد **bool**. مقدار پیش‌فرض true است. |
| void [set_UseFrameSize](./set_useframesize/)(**bool**) override | تعیین می‌کند که آیا قاب متن در ناحیه رندر گنجانده شود یا نه. می‌نویسد **bool**. مقدار پیش‌فرض false است. |
| void [set_VectorizeText](./set_vectorizetext/)(**bool**) override | تعیین می‌کند که آیا متن روی اسلاید به‌صورت گرافیک ذخیره شود یا نه. می‌نویسد **bool**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | شیئی را برمی‌گرداند یا تنظیم می‌کند که هشدارها را دریافت کند و تصمیم بگیرد که آیا فرآیند بارگذاری ادامه یابد یا خاتمه یابد. می‌نویسد [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به یک weak pointer (نه shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت weak را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از هوشمندها یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از هوشمندها یا ThisProtector استفاده کنید. |
|  [SVGOptions](./svgoptions/)() | یک نمونهٔ جدید از کلاس [SVGOptions](./) را مقداردهی اولیه می‌کند. |
|  [SVGOptions](./svgoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ILinkEmbedController](../ilinkembedcontroller/)\>) | یک نمونهٔ جدید از کلاس [SVGOptions](./) را با مشخص کردن شیء کنترل‌کنندهٔ جاسازی لینک مقداردهی اولیه می‌کند. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری بیان lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نظارتی [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از هوشمندها یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از هوشمندها یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## همچنین ببینید

* کلاس [SaveOptions](../saveoptions/)
* کلاس [ISVGOptions](../isvgoptions/)
* فضای‌نام [Aspose::Slides::Export](../)
* کتابخانه [Aspose.Slides](../../)