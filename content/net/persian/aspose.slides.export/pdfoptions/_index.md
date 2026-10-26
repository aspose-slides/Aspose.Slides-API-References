---
title: PdfOptions
second_title: مرجع API Aspose.Sildes برای .NET
description: گزینه‌هایی را فراهم می‌کند که نحوه ذخیرهٔ یک ارائه در قالب Pdf را کنترل می‌کند.
type: docs
weight: 4330
url: /fa/aspose.slides.export/pdfoptions/
---
## کلاس PdfOptions

گزینه‌هایی را فراهم می‌کند که کنترل می‌کند یک ارائه چگونه در قالب Pdf ذخیره شود.

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
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | مجموعه‌ای از پرچم‌ها را شامل می‌شود که تعیین می‌کند چه دسترسی‌هایی هنگام باز شدن سند با دسترسی کاربر اعطا شود. به [`PdfAccessPermissions`](../pdfaccesspermissions) مراجعه کنید. |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | یک آرایه از نام‌های کاربری تعریف‌شدهٔ خانواده‌های قلم را که Aspose.Slides باید به‌عنوان مشترک در نظر بگیرد، باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | اگر `true` باشد، رنگ شفاف مشخص‌شده را بر روی تصویر اعمال می‌کند. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | مشخص می‌کند آیا فشرده‌سازی مؤثرترین (به‌جای پیش‌فرض) برای هر تصویر باید به‌صورت خودکار انتخاب شود. اگر به Boolean.true تنظیم شود، برای هر تصویر در ارائه، مناسب‌ترین الگوریتم فشرده‌سازی انتخاب می‌شود که منجر به اندازهٔ کوچکتر سند PDF خروجی می‌گردد. انتخاب بهترین نسبت فشرده‌سازی تصویر هزینهٔ محاسباتی بالایی دارد و مقدار RAM بیشتری مصرف می‌کند، و به طور پیش‌فرض این گزینه Boolean.false است. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | سطح انطباق دلخواه برای سند PDF تولید شده. خواندن/نوشتن [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | قلم استفاده‌شده را در صورتی که قلم منبع پیدا نشود، باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | `true` برای رسم چهارچوب سیاه دور هر اسلاید. خواندن/نوشتن Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | تعیین می‌کند آیا تمام کاراکترهای قلم باید جاسازی شوند یا فقط زیرمجموعهٔ مورد استفاده. خواندن/نوشتن Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | تعیین می‌کند آیا Aspose.Slides قلم‌های رایج برای متن ASCII (بازهٔ کد 33..127) را جاسازی می‌کند یا نه. قلم‌های با کد کاراکتر بزرگتر از 127 همیشه جاسازی می‌شوند. فهرست قلم‌های رایج شامل 14 قلم پایهٔ PDF و قلم‌های کاربری اضافه‌شده است. خواندن/نوشتن Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | سبک بصری گرادیان را باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | رنگ شفاف تصویر را دریافت یا تنظیم می‌کند. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | `true` برای تبدیل تمام داده‌های OLE از ارائه به فایل‌های جاسازی‌شده در PDF خروجی. خواندن/نوشتن Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | گزینه‌هایی را که ظاهر اشیای Ink در سند صادرشده را کنترل می‌کنند، فراهم می‌کند. فقط خواندنی [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | مقدار کیفیت تصاویر JPEG داخل سند PDF را تعیین می‌کند. خواندن/نوشتن Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | رمز عبور کاربری برای محافظت از سند PDF را تنظیم می‌کند. خواندن/نوشتن String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | یک شیء بازخورد برای به‌روزرسانی پیشرفت ذخیره‌سازی به درصد را نشان می‌دهد. به [`IProgressCallback`](../../aspose.slides/iprogresscallback) مراجعه کنید. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | مشخص می‌کند آیا متن باید به‌صورت بیت‌مپ رستر شده و در PDF ذخیره شود وقتی قلم قابلیت سبک بولد را پشتیبانی نمی‌کند. این رویکرد می‌تواند کیفیت متن در PDF خروجی را برای برخی قلم‌ها بهبود بخشد. خواندن/نوشتن Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | `true` برای تبدیل تمام متافایل‌های به‌کاررفته در یک ارائه به تصاویر PNG. خواندن/نوشتن Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | مشخص می‌کند آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. به‌طور پیش‌فرض `false` است. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | مشخص می‌کند آیا هنگام ذخیره‌سازی ارائه، پیوندهای اینترنتی با فراخوانی‌های JavaScript نادیده گرفته شوند یا نه. خواندن/نوشتن Boolean. مقدار پیش‌فرض **false** است. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | حالت قرارگرفتن اسلایدها روی صفحه هنگام صادرات یک ارائه را دریافت یا تنظیم می‌کند [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | مقدار وضوح تصاویر داخل سند PDF را تعیین می‌کند. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | نوع فشرده‌سازی مورد استفاده برای تمام محتوای متنی در سند را تعیین می‌کند. خواندن/نوشتن [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | یک شیء که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا خاتمه یابد را باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### مثال‌ها

مثال زیر نشان می‌دهد چگونه پاورپوینت را با گزینه‌های سفارشی به PDF تبدیل کنیم.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// ایجاد یک نمونه از کلاس PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// کیفیت Jpeg را تنظیم می‌کند
	pdfOptions.JpegQuality = 90;
	// رفتار متافایل‌ها را تنظیم می‌کند
	pdfOptions.SaveMetafilesAsPng = true;
	// سطح فشرده‌سازی متن را تنظیم می‌کند
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// استاندارد PDF را تعریف می‌کند
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// ارائه را به عنوان PDF ذخیره می‌کند
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

مثال زیر نشان می‌دهد چگونه پاورپوینت را با اسلایدهای مخفی به PDF تبدیل کنیم.

```csharp
[C#]
// یک نمونه از کلاس Presentation را که نمایانگر یک فایل PowerPoint است ایجاد می‌کند
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// یک نمونه از کلاس PdfOptions را ایجاد می‌کند
	PdfOptions pdfOptions = new PdfOptions();
	// اسلایدهای مخفی را اضافه می‌کند
	pdfOptions.ShowHiddenSlides = true;
	// ارائه را به‌صورت PDF ذخیره می‌کند
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

مثال زیر نشان می‌دهد چگونه پاورپوینت را به PDF محافظت‌شده با رمز عبور تبدیل کنیم.

```csharp
[C#]
// یک شیء Presentation که نشان‌دهنده یک فایل PowerPoint است را ایجاد می‌کند
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// یک نمونه از کلاس PdfOptions را ایجاد می‌کند
	PdfOptions pdfOptions = new PdfOptions();
	// رمز عبور PDF و مجوزهای دسترسی را تنظیم می‌کند
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// ارائه را به‌صورت PDF ذخیره می‌کند
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

مثال زیر نشان می‌دهد چگونه پاورپوینت را با یادداشت‌ها به PDF تبدیل کنیم.

```csharp
[C#]
// یک شیء Presentation که نمایانگر یک فایل ارائه است را ایجاد می‌کند
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

### موارد مرتبط

* کلاس [SaveOptions](../saveoptions)
* رابط [IPdfOptions](../ipdfoptions)
* فضای‌نام [Aspose.Slides.Export](../../aspose.slides.export)
* مجتمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->