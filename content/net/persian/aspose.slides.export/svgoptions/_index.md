---
title: SVGOptions
second_title: Aspose.Sildes برای مرجع API .NET
description: نمایانگر گزینه‌های SVG است.
type: docs
weight: 4430
url: /fa/aspose.slides.export/svgoptions/
---
## کلاس SVGOptions

نمایانگر گزینه‌های SVG است.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## سازنده‌ها

| نام | توضیح |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | یک نمونه جدید از کلاس SVGOptions را مقداردهی اولیه می‌کند. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | یک نمونه جدید از کلاس SVGOptions را مقداردهی اولیه می‌کند که شیء کنترل‌کننده جاسازی پیوند را مشخص می‌کند. |

## خصوصیات

| نام | توضیح |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | مقادیر پیش‌فرض را برمی‌گرداند. فقط خواندنی [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | مقادیر تنظیمات برای ساده‌ترین و کوچک‌ترین تولید فایل SVG را برمی‌گرداند. فقط خواندنی [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | مقادیر تنظیمات برای دقیق‌ترین تولید فایل SVG را برمی‌گرداند. فقط خواندنی [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | قلمی را که در صورت عدم یافتن قلم منبع استفاده می‌شود برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | پرچم بولی نشان می‌دهد که آیا بخش‌های بریده شده به عنوان بخشی از سند باقی می‌مانند. اگر true باشد، بخش‌های بریده شده حذف می‌شوند؛ اگر false باشند، در سند سریال‌سازی می‌شوند (که ممکن است منجر به بزرگ‌تر شدن فایل شود). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | تعیین می‌کند که آیا متن 3D در SVG غیرفعال است یا نه. قابل خواندن/نوشتن Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | مقداری را که نشان می‌دهد متن بدون استفاده از لیگچرها رندر می‌شود دریافت یا تنظیم می‌کند. وقتی به `true` تنظیم شود، لیگچرها در خروجی رندر شده غیرفعال می‌شوند. به‌طور پیش‌فرض، این خصوصیت روی `false` تنظیم شده است. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | تقسیم گرادیان‌های FromCornerX و FromCenter را غیرفعال می‌کند. قابل خواندن/نوشتن Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | نسخه SVG 1.1 امکان تعریف داخلی‌ها برای مارکرها را ندارد. موتور نوشتن SVG در Aspose.Slides راه‌حلی برای این مشکل دارد: انتهای خط با پیکان را برش می‌دهد تا خط با مارکرها تداخل نداشته باشد. این گزینه این رفتار را غیرفعال می‌کند. قابل خواندن/نوشتن Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | روشی برای مدیریت قلم‌های بارگذاری‌شده به‌صورت خارجی را تعیین می‌کند. قابل خواندن/نوشتن [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | سبک بصری گرادیان را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | گزینه‌هایی را فراهم می‌کند که ظاهر اشیاء Ink در سند صادر شده را کنترل می‌کند. فقط خواندنی [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | کیفیت رمزگذاری JPEG را تعیین می‌کند. قابل خواندن/نوشتن Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | حد پایین وضوح برای رسترسازی متافایل را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | سطح فشرده‌سازی تصاویر را نشان می‌دهد |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | شیء بازگشتی برای ذخیره‌سازی به‌روزرسانی‌های پیشرفت به‌صورت درصدی را نشان می‌دهد. ببینید [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | یک رابط بازگشتی را برمی‌گرداند و تنظیم می‌کند که به کاربر امکان کنترل تبدیل شکل را می‌دهد. قابل خواندن/نوشتن [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | مشخص می‌کند آیا هنگام ذخیره‌سازی ارائه، پیوندهایهای ابرمتنی با فراخوانی JavaScript رد شوند یا نه. قابل خواندن/نوشتن Boolean. مقدار پیش‌فرض **false** است. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | تعیین می‌کند آیا دوران مشخص‌شدهٔ شکل هنگام رندر انجام شود یا نه. قابل خواندن/نوشتن Boolean. مقدار پیش‌فرض true است. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | تعیین می‌کند آیا قاب متن در ناحیه رندر گنجانده شود یا نه. قابل خواندن/نوشتن Boolean. مقدار پیش‌فرض false است. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | تعیین می‌کند آیا متن روی اسلاید به‌صورت گرافیک ذخیره شود یا نه. قابل خواندن/نوشتن Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | یک شیء را که هشدارها را دریافت می‌کند و تصمیم می‌گیرد فرآیند بارگذاری ادامه یابد یا لغو شود، برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### موارد مرتبط

* کلاس [SaveOptions](../saveoptions)
* رابط [ISVGOptions](../isvgoptions)
* فضای‌نام [Aspose.Slides.Export](../../aspose.slides.export)
* مونتاژ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->