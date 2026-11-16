---
title: PdfOptions
second_title: Aspose.Sildes برای مرجع API .NET
description: گزینه‌هایی را فراهم می‌کند که نحوه ذخیره یک ارائه را در قالب Pdf کنترل می‌کند.
type: docs
weight: 4350
url: /fa/aspose.slides.export/pdfoptions/
---
## PdfOptions کلاس

گزینه‌هایی را فراهم می‌کند که نحوه ذخیره‌سازی یک ارائه در قالب Pdf را کنترل می‌کند.

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## سازنده‌ها

| نام | توضیح |
| --- | --- |
| [PdfOptions](pdfoptions)() | سازنده پیش‌فرض. |

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | حاوی مجموعه‌ای از پرچم‌ها است که مشخص می‌کند هنگام باز کردن سند با دسترسی کاربر چه مجوزهای دسترسی اعطا شود. برای جزئیات به [`PdfAccessPermissions`](../pdfaccesspermissions) مراجعه کنید. |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | آرایه‌ای از نام‌های تعریف‌شده توسط کاربر برای خانواده‌های قلم را برمی‌گرداند یا تنظیم می‌کند که Aspose.Slides باید آن‌ها را مشترک در نظر بگیرد. خواندن/نوشتن String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | اگر `true` باشد، رنگ شفاف مشخص‌شده را بر روی تصویر اعمال می‌کند. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | نمایش می‌دهد آیا فشرده‌سازی مؤثرترین (به‌جای پیش‌فرض) برای هر تصویر باید به‌صورت خودکار انتخاب شود. اگر به Boolean.true تنظیم شود، برای هر تصویر در ارائه مناسب‌ترین الگوریتم فشرده‌سازی انتخاب می‌شود که منجر به حجم کمتر سند PDF خروجی می‌شود. انتخاب بهترین نسبت فشرده‌سازی تصویر هزینه محاسباتی بالایی دارد و مقدار RAM بیشتری مصرف می‌کند، و این گزینه به طور پیش‌فرض Boolean.false است. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | سطح سازگاری موردنظر برای سند PDF تولید شده. خواندن/نوشتن [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | قلم مورد استفاده را در صورتی که قلم منبع یافت نشود برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | اگر true باشد، قاب سیاه دور هر اسلاید رسم می‌شود. خواندن/نوشتن Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | مشخص می‌کند آیا همه‌نویسه‌های قلم باید جاسازی شوند یا فقط زیرمجموعه‌ای استفاده شود. خواندن/نوشتن Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | مشخص می‌کند آیا Aspose.Slides قلم‌های مشترک برای متن ASCII (بازه کد 33..127) را جاسازی خواهد کرد. قلم‌های برای کدهای کاراکتر بالاتر از 127 همیشه جاسازی می‌شوند. فهرست قلم‌های مشترک شامل 14 قلم پایه PDF و قلم‌های کاربر اضافه شده است. خواندن/نوشتن Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | سبک بصری گرادیانت را بر می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | رنگ شفاف تصویر را بر می‌گرداند یا تنظیم می‌کند. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | اگر true باشد، تمام داده‌های OLE از ارائه به فایل‌های جاسازی‌شده در PDF خروجی تبدیل می‌شود. خواندن/نوشتن Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | گزینه‌هایی را فراهم می‌کند که ظاهر اشیای Ink در سند صادرشده را کنترل می‌کند. فقط-خواندنی [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | مقدار تعیین‌کننده کیفیت تصاویر JPEG داخل سند PDF را بر می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | تنظیم رمز عبور کاربر برای محافظت از سند PDF. خواندن/نوشتن String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | یک شیء بازخوانی (callback) را برای به‌روزرسانی درصد پیشرفت ذخیره‌سازی نشان می‌دهد. برای جزئیات به [`IProgressCallback`](../../aspose.slides/iprogresscallback) مراجعه کنید. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | نشان می‌دهد آیا متن باید هنگام عدم پشتیبانی قلم از قالب بولد به‌صورت bitmap رستریزه شود و در PDF ذخیره گردد. این روش می‌تواند کیفیت متن در PDF خروجی را برای برخی قلم‌ها بهبود بخشد. خواندن/نوشتن Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | اگر true باشد، تمام متافایل‌های استفاده‌شده در یک ارائه به تصاویر PNG تبدیل می‌شوند. خواندن/نوشتن Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | مشخص می‌کند آیا سند تولید شده اسلایدهای مخفی را شامل شود یا نه. پیش‌فرض `false` است. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | مشخص می‌کند آیا هنگام ذخیره‌سازی ارائه، پیوندهای فراخوانی JavaScript صرف‌نظر شوند یا نه. خواندن/نوشتن Boolean. مقدار پیش‌فرض **false** است. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | حالت قرارگیری اسلایدها بر روی صفحه هنگام صادرات یک ارائه [`ISlidesLayoutOptions`](../islideslayoutoptions) را بر می‌گرداند یا تنظیم می‌کند. |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | مقدار تعیین‌کننده وضوح تصاویر داخل سند PDF را بر می‌گرداند یا تنظیم می‌کند. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | نوع فشرده‌سازی که برای تمام محتوای متنی سند استفاده می‌شود را مشخص می‌کند. خواندن/نوشتن [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | یک شیء را بر می‌گرداند یا تنظیم می‌کند که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود. خواندن/نوشتن [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### مثال‌ها

مثال زیر نشان می‌دهد چگونه PowerPoint را با گزینه‌های سفارشی به PDF تبدیل کنید.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// یک شی از کلاس PdfOptions ایجاد می‌کند
	PdfOptions pdfOptions = new PdfOptions();
	// کیفیت Jpeg را تنظیم می‌کند
	pdfOptions.JpegQuality = 90;
	// رفتار متافایل‌ها را تنظیم می‌کند
	pdfOptions.SaveMetafilesAsPng = true;
	// سطح فشرده‌سازی متن را تنظیم می‌کند
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// استاندارد PDF را تعریف می‌کند
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// ارائه را به صورت PDF ذخیره می‌کند
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

مثال زیر نشان می‌دهد چگونه PowerPoint را با اسلایدهای مخفی به PDF تبدیل کنید.

```csharp
[C#]
// یک شی از کلاس Presentation ایجاد می‌کند که نمایانگر فایل PowerPoint است
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// یک شی از کلاس PdfOptions ایجاد می‌کند
	PdfOptions pdfOptions = new PdfOptions();
	// اسلایدهای مخفی را اضافه می‌کند
	pdfOptions.ShowHiddenSlides = true;
	// ارائه را به صورت PDF ذخیره می‌کند
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

مثال زیر نشان می‌دهد چگونه PowerPoint را به PDF محافظت‌شده با رمز عبور تبدیل کنید.

```csharp
[C#]
// یک شی از کلاس Presentation ایجاد می‌کند که نمایانگر یک فایل PowerPoint است
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// یک شی از کلاس PdfOptions ایجاد می‌کند
	PdfOptions pdfOptions = new PdfOptions();
	// رمز عبور PDF و مجوزهای دسترسی را تنظیم می‌کند
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// ارائه را به صورت PDF ذخیره می‌کند
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

مثال زیر نشان می‌دهد چگونه PowerPoint را با یادداشت‌ها به PDF تبدیل کنید.

```csharp
[C#]
// یک شی Presentation ایجاد می‌کند که نمایانگر یک فایل ارائه است
using (Presentation presentation = new Presentation("SelectedSlides.pptx"))
{
    using (Presentation auxPresentation = new Presentation())
    {
        ISlide slide = presentation.Slides[0];
        auxPresentation.Slides.InsertClone(0, slide);
        // تنظیم نوع اسلاید و اندازه
        //auxPresentation.SlideSize.SetSize(presentation.SlideSize.Size.Width, presentation.SlideSize.Size.Height,SlideSizeScaleType.EnsureFit);
        auxPresentation.SlideSize.SetSize(612F, 792F, SlideSizeScaleType.EnsureFit);
        PdfOptions pdfOptions = new PdfOptions();
        pdfOptions.SlidesLayoutOptions = new NotesCommentsLayoutingOptions() { NotesPosition = NotesPositions.BottomFull };
        auxPresentation.Save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
    }
}
```

### مطالب مرتبط

* کلاس [SaveOptions](../saveoptions)
* واسط [IPdfOptions](../ipdfoptions)
* فضای‌نام [Aspose.Slides.Export](../../aspose.slides.export)
* مونتاژ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->