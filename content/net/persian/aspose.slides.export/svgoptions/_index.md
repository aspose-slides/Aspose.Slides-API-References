---
title: SVGOptions
second_title: Aspose.Sildes برای مرجع API .NET
description: یک گزینهٔ SVG را نمایندگی می‌کند.
type: docs
weight: 4450
url: /fa/aspose.slides.export/svgoptions/
---
## کلاس SVGOptions

یک گزینهٔ SVG را نمایندگی می‌کند.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## سازنده‌ها

| Name | Description |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | یک نمونهٔ جدید از کلاس SVGOptions را مقداردهی اولیه می‌کند. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | یک نمونهٔ جدید از کلاس SVGOptions را با تعیین شیء کنترل‌کنندهٔ جاسازی پیوند مقداردهی اولیه می‌کند. |

## ویژگی‌ها

| Name | Description |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | تنظیمات پیش‌فرض را برمی‌گرداند. فقط-خواندنی [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | تنظیمات برای ساده‌ترین و کوچک‌ترین تولید فایل SVG را برمی‌گرداند. فقط-خواندنی [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | تنظیمات برای دقیق‌ترین تولید فایل SVG را برمی‌گرداند. فقط-خواندنی [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | قلم مورد استفاده را وقتی قلم منبع یافت نشود، برمی‌گرداند یا تنظیم می‌کند. قابل-خواندن-و-نوشتن String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | یک پرچم بولی نشان می‌دهد آیا بخش‌های برش‌ خورده به‌عنوان بخشی از سند باقی می‌مانند یا خیر. اگر true باشد، بخش‌های برش‌ خورده حذف می‌شوند، اگر false باشند، در سند سریال‌سازی می‌شوند (که ممکن است منجر به فایل بزرگ‌تر شود). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | تعیین می‌کند که آیا متن 3D در SVG غیرفعال باشد یا نه. قابل-خواندن-و-نوشتن Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | یک مقدار که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود را برمی‌گرداند یا تنظیم می‌کند. وقتی به `true` تنظیم شود، لیگچرها در خروجی رندر شده غیرفعال می‌شوند. به طور پیش‌فرض، این ویژگی روی `false` تنظیم شده است. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | تقسیم گرادیان‌های FromCornerX و FromCenter را غیرفعال می‌کند. قابل-خواندن-و-نوشتن Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1 توانایی تعریف تو رفتگی‌ها برای علائم را ندارد. موتور نوشتن SVG Aspose.Slides راه‌حلی برای این مشکل دارد: انتهای خط با پیکان برش می‌خورد تا خط بر روی علامت‌ها قرار نگیرد. این گزینه این رفتار را غیرفعال می‌کند. قابل-خواندن-و-نوشتن Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | روشی برای مدیریت قلم‌های بارگذاری‌شده به‌صورت خارجی را تعیین می‌کند. قابل-خواندن-و-نوشتن [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | سبک بصری گرادیان را برمی‌گرداند یا تنظیم می‌کند. قابل-خواندن-و-نوشتن [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | گزینه‌هایی را ارائه می‌دهد که ظاهر اشیای Ink را در سند صادرشده کنترل می‌کند. فقط-خواندنی [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | کیفیت رمزگذاری JPEG را تعیین می‌کند. قابل-خواندن-و-نوشتن Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | حد پایین وضوح برای رسترسازی متافایل را برمی‌گرداند یا تنظیم می‌کند. قابل-خواندن-و-نوشتن Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | سطح فشرده‌سازی تصاویر را نمایندگی می‌کند |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | یک شیء callback برای ذخیره‌سازی به‌روزرسانی‌های پیشرفت به‌صورت درصدی را نمایندگی می‌کند. برای جزئیات به [`IProgressCallback`](../../aspose.slides/iprogresscallback) مراجعه کنید. |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | یک رابط callback را که به کاربر امکان کنترل تبدیل شکل را می‌دهد، برمی‌گرداند و تنظیم می‌کند. قابل-خواندن-و-نوشتن [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | مشخص می‌کند آیا هنگام ذخیره‌سازی ارائه، پیوندهای شامل فراخوانی‌های JavaScript رد شوند یا نه. قابل-خواندن-و-نوشتن Boolean. مقدار پیش‌فرض **false** است. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | تعیین می‌کند آیا دوران مشخص‌شدهٔ شکل هنگام رندر انجام شود یا نه. قابل-خواندن-و-نوشتن Boolean. مقدار پیش‌فرض true است. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | تعیین می‌کند آیا قاب متن در ناحیه رندر گنجانده شود یا نه. قابل-خواندن-و-نوشتن Boolean. مقدار پیش‌فرض false است. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | تعیین می‌کند آیا متن روی اسلاید به‌عنوان گرافیک ذخیره شود یا نه. قابل-خواندن-و-نوشتن Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | یک شیء را که هشدارها را دریافت می‌کند و تصمیم می‌گیرد فرآیند بارگذاری ادامه یابد یا متوقف شود، برمی‌گرداند یا تنظیم می‌کند. قابل-خواندن-و-نوشتن [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### موارد مرتبط

* کلاس [SaveOptions](../saveoptions)
* رابط [ISVGOptions](../isvgoptions)
* فضای نام [Aspose.Slides.Export](../../aspose.slides.export)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->