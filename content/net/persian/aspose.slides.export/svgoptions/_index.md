---
title: SVGOptions
second_title: مرجع API Aspose.Sildes برای .NET
description: نمایانگر گزینه‌های SVG است.
type: docs
weight: 4430
url: /fa/aspose.slides.export/svgoptions/
---
## کلاس SVGOptions

نمایانگر تنظیمات SVG است.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## سازندگان

| نام | توضیح |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | یک نمونه جدید از کلاس SVGOptions را مقداردهی اولیه می‌کند. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | یک نمونه جدید از کلاس SVGOptions را مقداردهی اولیه می‌کند که شیء کنترل‌کننده‌امجاژ لینک را مشخص می‌کند. |

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | پیکربندی‌های پیش‌فرض را برمی‌گرداند. فقط-خواندنی [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | پیکربندی‌های تولید ساده‌ترین و کم‌حجم‌ترین فایل SVG را برمی‌گرداند. فقط-خواندنی [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | پیکربندی‌های تولید دقیق‌ترین فایل SVG را برمی‌گرداند. فقط-خواندنی [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | قلمی را که در صورت یافت نشدن قلم منبع استفاده می‌شود برمی‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | پرچم منطقی‌ای که نشان می‌دهد آیا بخش‌های برش‌خورده به عنوان بخشی از سند باقی می‌مانند یا نه. اگر true باشد بخش‌های برش‌خورده حذف می‌شوند، اگر false باشند در سند سریالیزه می‌شوند (که ممکن است منجر به فایل بزرگتر شود). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | تعیین می‌کند آیا متن ۳بعدی در SVG غیرفعال باشد یا نه. خواندنی-نوشتنی Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | مقداری را که نشان می‌دهد آیا متن بدون استفاده از لیگاتور رندر می‌شود یا نه، برمی‌گرداند یا تنظیم می‌کند. وقتی به `true` تنظیم شود، لیگاتورها در خروجی رندر غیرفعال می‌شوند. به طور پیش‌فرض این ویژگی به `false` تنظیم شده است. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | تقسیم گرادیان‌های FromCornerX و FromCenter را غیرفعال می‌کند. خواندنی-نوشتنی Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1 توانایی تعریف تو رفتگی برای مارکرها را ندارد. موتور نوشتن SVG Aspose.Slides راه‌حلی برای این مشکل دارد: انتهای خط با پیکان را برش می‌دهد تا خط با مارکرها همپوشانی نکنند. این گزینه چنین رفتاری را غیرفعال می‌کند. خواندنی-نوشتنی Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | روشی برای مدیریت قلم‌های بارگذاری شده از بیرون را تعیین می‌کند. خواندنی-نوشتنی [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | استایل بصری گرادیان را برمی‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | گزینه‌هایی را که ظاهر اشیاء Ink را در سند صادر شده کنترل می‌کنند، فراهم می‌آورد. فقط-خواندنی [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | کیفیت رمزنگاری JPEG را تعیین می‌کند. خواندنی-نوشتنی Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | حد پایین وضوح برای رسترسازی متافایل را برمی‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | سطح فشرده‌سازی تصاویر را نشان می‌دهد |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | شیء callback برای ذخیره‌سازی به‌روزرسانی‌های پیشرفت به درصد را نشان می‌دهد. ببینید [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | یک رابط callback که به کاربر امکان کنترل تبدیل شکل را می‌دهد، برمی‌گرداند و تنظیم می‌کند. خواندنی-نوشتنی [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | مشخص می‌کند آیا هنگام ذخیره‌سازی ارائه، پیوندهای هایپرلینک‌دار با فراخوانی‌های JavaScript نادیده گرفته شوند یا نه. خواندنی-نوشتنی Boolean. مقدار پیش‌فرض **false** است. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | تعیین می‌کند آیا هنگام رندر، چرخش مشخص‌شده شکل اعمال شود یا نه. خواندنی-نوشتنی Boolean. مقدار پیش‌فرض true است. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | تعیین می‌کند آیا قاب متن در ناحیه رندر گنجانده شود یا نه. خواندنی-نوشتنی Boolean. مقدار پیش‌فرض false است. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | تعیین می‌کند آیا متن اسلاید به‌عنوان گرافیک ذخیره شود یا نه. خواندنی-نوشتنی Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | شیئی را که هشدارها را دریافت می‌کند و تصمیم می‌گیرد فرآیند بارگذاری ادامه یابد یا متوقف شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### موارد مرتبط

* کلاس [SaveOptions](../saveoptions)
* رابط [ISVGOptions](../isvgoptions)
* فضای نام [Aspose.Slides.Export](../../aspose.slides.export)
* مجوعه [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->