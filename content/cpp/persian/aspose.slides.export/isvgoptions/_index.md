---
title: ISVGOptions
second_title: مرجع API Aspose.Slides برای C++
description: نمایانگر یک گزینه SVG است.
type: docs
weight: 404
url: /fa/aspose.slides.export/isvgoptions/
---
## ISVGOptions کلاس

نمایانگر یک گزینه SVG است.

```cpp
class ISVGOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معانی [Object.Equals](../../system/object/equals/) C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقداری را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | فونتی را که در صورت عدم یافتن فونت منبع استفاده می‌شود برمی‌گرداند. [System::String](../../system/string/) را می‌خواند. |
| virtual **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() | یک پرچم بولی نشان می‌دهد که آیا قسمت‌های برش‌خورده به عنوان بخشی از سند باقی می‌مانند یا نه. اگر true باشد، قسمت‌های برش‌خورده حذف می‌شوند؛ اگر false باشد، در سند سریالیزه می‌شوند (که ممکن است منجر به فایل بزرگ‌تر شود). **bool** را می‌خواند. |
| virtual **bool** [get_Disable3DText](./get_disable3dtext/)() | تعیین می‌کند که آیا متن 3D در SVG غیرفعال است یا نه. **bool** را می‌خواند. |
| virtual **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود یا نه. وقتی به **true** تنظیم شود، لیگچرها در خروجی رندر غیرفعال می‌شوند. به طور پیش‌فرض، این خصوصیت برابر **false** است. |
| virtual **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() | تقسیم گرادیان‌های FromCornerX و FromCenter را غیرفعال می‌کند. **bool** را می‌خواند. |
| virtual **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() | SVG 1.1 توانایی تعریف تو رفتگی برای نشانگرها را ندارد. موتور نوشتن SVG [Aspose.Slides](../../aspose.slides/) راه‌حلی برای این مشکل دارد: انتهای خط با پیکان را برش می‌دهد تا خط با نشانگرها همپوشانی نکند. این گزینه این رفتار را خاموش می‌کند. **bool** را می‌خواند. |
| virtual [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() | روشی برای مدیریت فونت‌های بارگذاری شده به‌صورت خارجی را تعیین می‌کند. [SvgExternalFontsHandling](../svgexternalfontshandling/) را می‌خواند. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | سبک بصری گرادیان را برمی‌گرداند. [GradientStyle](../../aspose.slides/gradientstyle/) را می‌خواند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | گزینه‌هایی را ارائه می‌دهد که ظاهر اشیاء [Ink](../../aspose.slides.ink/) را در سند صادراتی کنترل می‌کند. فقط خواندنی [IInkOptions](../iinkoptions/) |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | کیفیت رمزگذاری JPEG را تعیین می‌کند. **int32_t** را می‌خواند. |
| virtual **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() | حد پایین وضوح برای رستر‌سازی متافایل را برمی‌گرداند. **int32_t** را می‌خواند. |
| virtual [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() | سطح فشرده‌سازی تصاویر را نشان می‌دهد. [PicturesCompression](../picturescompression/) را می‌خواند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | یک شیء بازخورد برای ذخیره‌سازی به‌روزرسانی‌های پیشرفت به درصد را نشان می‌دهد. به [IProgressCallback](../../aspose.slides/iprogresscallback/) مراجعه کنید. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() | یک رابط بازخورد را برمی‌گرداند و تنظیم می‌کند که به کاربر امکان کنترل تبدیل شکل را می‌دهد. [ISvgShapeFormattingController](../isvgshapeformattingcontroller/) را می‌خواند. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | مشخص می‌کند آیا هنگام ذخیره-سازی ارائه، پیوندهای با فراخوانی‌های JavaScript رد شوند یا نه. **bool** را می‌خواند. مقدار پیش‌فرض **false** است. |
| virtual **bool** [get_UseFrameRotation](./get_useframerotation/)() | تعیین می‌کند آیا چرخش مشخص شده شکل هنگام رندر انجام شود یا نه. **bool** را می‌خواند. مقدار پیش‌فرض true است. |
| virtual **bool** [get_UseFrameSize](./get_useframesize/)() | تعیین می‌کند آیا فریم متن در ناحیه رندر گنجانده شود یا نه. **bool** را می‌خواند. مقدار پیش‌فرض false است. |
| virtual **bool** [get_VectorizeText](./get_vectorizetext/)() | تعیین می‌کند آیا متن در اسلاید به‌صورت گرافیک ذخیره شود یا نه. **bool** را می‌خواند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | شیئی را برمی‌گرداند که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرایند بارگذاری ادامه یابد یا متوقف شود. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) را می‌خواند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). هش‌گذاری اشیاء سفارشی را فعال می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با استفاده از بیان C# lock() را پیاده‌سازی می‌کند. به‌طور مستقیم صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را می‌دهد. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده‌ی کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان سازنده‌ی کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان سازنده‌ی کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را به‌صورت ارجاعی مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را به‌صورت ارجاعی مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقداری را با nullptr به‌صورت ارجاعی مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را به مقدار مشخص شده کاهش می‌دهد. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | فونتی را که در صورت عدم یافتن فونت منبع استفاده می‌شود تنظیم می‌کند. [System::String](../../system/string/) را می‌نویسد. |
| virtual void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) | پرچم بولی نشان می‌دهد که آیا قسمت‌های برش‌خورده به عنوان بخشی از سند باقی می‌مانند یا نه. اگر true باشد، قسمت‌های برش‌خورده حذف می‌شوند؛ اگر false باشد، در سند سریالیزه می‌شوند (که ممکن است منجر به فایل بزرگ‌تر شود). **bool** را می‌نویسد. |
| virtual void [set_Disable3DText](./set_disable3dtext/)(**bool**) | تعیین می‌کند آیا متن 3D در SVG غیرفعال است یا نه. **bool** را می‌نویسد. |
| virtual void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) | مقداری را تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر شود یا نه. وقتی به **true** تنظیم شود، لیگچرها در خروجی رندر غیرفعال می‌شوند. به‌طور پیش‌فرض، این خصوصیت برابر **false** است. |
| virtual void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) | تقسیم گرادیان‌های FromCornerX و FromCenter را غیرفعال می‌کند. **bool** را می‌نویسد. |
| virtual void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) | SVG 1.1 توانایی تعریف تو رفتگی برای نشانگرها را ندارد. موتور نوشتن SVG [Aspose.Slides](../../aspose.slides/) راه‌حلی برای این مشکل دارد: انتهای خط با پیکان را برش می‌دهد تا خط با نشانگرها همپوشانی نکند. این گزینه این رفتار را خاموش می‌کند. **bool** را می‌نویسد. |
| virtual void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) | روشی برای مدیریت فونت‌های بارگذاری شده به‌صورت خارجی را تعیین می‌کند. [SvgExternalFontsHandling](../svgexternalfontshandling/) را می‌نویسد. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | سبک بصری گرادیان را تنظیم می‌کند. [GradientStyle](../../aspose.slides/gradientstyle/) را می‌نویسد. |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | کیفیت رمزگذاری JPEG را تعیین می‌کند. **int32_t** را می‌نویسد. |
| virtual void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) | حد پایین وضوح برای رستر‌سازی متافایل را تنظیم می‌کند. **int32_t** را می‌نویسد. |
| virtual void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) | سطح فشرده‌سازی تصاویر را نشان می‌دهد. [PicturesCompression](../picturescompression/) را می‌نویسد. |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | یک شیء بازخورد برای ذخیره‌سازی به‌روزرسانی‌های پیشرفت به درصد را نشان می‌دهد. به [IProgressCallback](../../aspose.slides/iprogresscallback/) مراجعه کنید. |
| virtual void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) | یک رابط بازخورد را برمی‌گرداند و تنظیم می‌کند که به کاربر امکان کنترل تبدیل شکل را می‌دهد. [ISvgShapeFormattingController](../isvgshapeformattingcontroller/) را می‌نویسد. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | مشخص می‌کند آیا هنگام ذخیره-سازی ارائه، پیوندهای با فراخوانی‌های JavaScript رد شوند یا نه. **bool** را می‌نویسد. مقدار پیش‌فرض **false** است. |
| virtual void [set_UseFrameRotation](./set_useframerotation/)(**bool**) | تعیین می‌کند آیا چرخش مشخص شده شکل هنگام رندر انجام شود یا نه. **bool** را می‌نویسد. مقدار پیش‌فرض true است. |
| virtual void [set_UseFrameSize](./set_useframesize/)(**bool**) | تعیین می‌کند آیا فریم متن در ناحیه رندر گنجانده شود یا نه. **bool** را می‌نویسد. مقدار پیش‌فرض false است. |
| virtual void [set_VectorizeText](./set_vectorizetext/)(**bool**) | تعیین می‌کند آیا متن در اسلاید به‌صورت گرافیک ذخیره شود یا نه. **bool** را می‌نویسد. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | شیئی را تنظیم می‌کند که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرایند بارگذاری ادامه یابد یا متوقف شود. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) را می‌نویسد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را می‌دهد. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | قالب typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گشایی با استفاده از بیان C# lock() را پیاده‌سازی می‌کند. به‌طور مستقیم صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را تخریب می‌کند. تمام ساختارهای داخلی را آزاد می‌سازد. |

## موارد مرتبط

* کلاس [ISaveOptions](../isaveoptions/)
* فضای‌نام [Aspose::Slides::Export](../)
* کتابخانه [Aspose.Slides](../../)