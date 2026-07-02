---
title: PdfOptions
second_title: Aspose.Sildes برای مرجع API .NET
description: گزینه‌هایی را فراهم می‌کند که نحوه ذخیره یک ارائه در قالب Pdf را کنترل می‌کنند.
type: docs
weight: 4330
url: /fa/aspose.slides.export/pdfoptions/
---
## کلاس PdfOptions

گزینه‌هایی را فراهم می‌کند که نحوه ذخیره یک ارائه در قالب Pdf را کنترل می‌کنند.

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## سازنده‌ها

| نام | توضیح |
| --- | --- |
| [PdfOptions](pdfoptions)() | سازندهٔ پیش‌فرض. |

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | مجموعه‌ای از پرچم‌ها را شامل می‌شود که تعیین می‌کند هنگام باز کردن سند با دسترسی کاربر، چه اجازه‌دسترسی‌هایی اعطا شود. نگاه کنید به [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | یک آرایه از نام‌های تعریف‌شده توسط کاربر برای خانواده‌های قلم که Aspose.Slides باید به عنوان عمومی در نظر بگیرد، را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | اگر `true` باشد، رنگ شفاف مشخص‌شده را روی تصویر اعمال می‌کند. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | نشان می‌دهد آیا فشرده‌سازی مؤثرترین (به‌جای پیش‌فرض) برای هر تصویر باید به صورت خودکار انتخاب شود یا خیر. اگر به Boolean.true تنظیم شود، برای هر تصویر در ارائه، الگوریتم فشرده‌سازی مناسب‌ترین انتخاب می‌شود که منجر به کوچک‌تر شدن حجم سند PDF نهایی می‌شود. انتخاب بهترین نسبت فشرده‌سازی تصویر هزینه محاسباتی بالایی دارد و مقدار بیشتری RAM مصرف می‌کند، و این گزینه به‌صورت پیش‌فرض Boolean.false است. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | سطح انطباق مطلوب برای سند PDF تولیدشده. خواندنی/نوشتنی [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | قلم استفاده‌شده را در صورتی که قلم منبع یافت نشود، بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | اگر true باشد، قاب سیاه دور هر اسلاید رسم می‌شود. خواندنی/نوشتنی Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | مشخص می‌کند آیا تمام کاراکترهای قلم باید جاسازی شوند یا فقط زیرمجموعه‌ای استفاده شود. خواندنی/نوشتنی Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | مشخص می‌کند آیا Aspose.Slides قلم‌های عمومی را برای متن ASCII (بازه کد 33..127) جاسازی کند یا نه. قلم‌های برای کدهای کاراکتر بیش از 127 همیشه جاسازی می‌شوند. لیست قلم‌های عمومی شامل 14 قلم پایه PDF و قلم‌های اضافه شده توسط کاربر است. خواندنی/نوشتنی Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | سبک بصری گرادیان را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | رنگ شفاف تصویر را دریافت یا تنظیم می‌کند. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | اگر true باشد، تمام داده‌های OLE از ارائه به فایل‌های جاسازی‌شده در PDF نهایی تبدیل می‌شود. خواندنی/نوشتنی Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | گزینه‌هایی را فراهم می‌کند که ظاهر اشیاء Ink در سند صادرشده را کنترل می‌کند. فقط‌خواندنی [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | مقداری را بازمی‌گرداند یا تنظیم می‌کند که کیفیت تصاویر JPEG داخل سند PDF را تعیین می‌کند. خواندنی/نوشتنی Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | تنظیم رمز عبور کاربر برای محافظت از سند PDF. خواندنی/نوشتنی String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | یک شیء فراخوانی بازگشتی را برای به‌روزرسانی پیشرفت ذخیره به‌صورت درصد نشان می‌دهد. نگاه کنید به [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | مشخص می‌کند آیا متن باید به‌عنوان بیت‌مپ رستر شود و به PDF ذخیره گردد وقتی قلم از استایل بولد پشتیبانی نمی‌کند. این رویکرد می‌تواند کیفیت متن در PDF نهایی را برای برخی قلم‌ها بهبود بخشد. خواندنی/نوشتنی Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | اگر true باشد، تمام متافایل‌های استفاده‌شده در یک ارائه به تصاویر PNG تبدیل می‌شوند. خواندنی/نوشتنی Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | مشخص می‌کند آیا سند تولیدشده باید اسلایدهای پنهان را شامل شود یا نه. پیش‌فرض `false` است. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | مشخص می‌کند آیا هنگام ذخیرهٔ ارائه، پیوندهایهای دارای فراخوانی JavaScript نادیده گرفته شوند یا نه. خواندنی/نوشتنی Boolean. مقدار پیش‌فرض **false** است. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | حالت قرارگیری اسلایدها بر صفحه هنگام صادرات یک ارائه را دریافت یا تنظیم می‌کند [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | مقداری را بازمی‌گرداند یا تنظیم می‌کند که وضوح تصاویر داخل سند PDF را تعیین می‌کند. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | نوع فشرده‌سازی مورد استفاده برای تمام محتوای متنی در سند را مشخص می‌کند. خواندنی/نوشتنی [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | یک شیء را بازمی‌گرداند یا تنظیم می‌کند که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود. خواندنی/نوشتنی [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### مثال‌ها

مثال زیر نشان می‌دهد چگونه می‌توان PowerPoint را به PDF با گزینه‌های سفارشی تبدیل کرد.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// یک نمونه از کلاس PdfOptions را ایجاد می‌کند
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

مثال زیر نشان می‌دهد چگونه می‌توان PowerPoint را به PDF با اسلایدهای پنهان تبدیل کرد.

```csharp
[C#]
// یک نمونه از کلاس Presentation که نمایانگر یک فایل PowerPoint است
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// یک نمونه از کلاس PdfOptions را ایجاد می‌کند
	PdfOptions pdfOptions = new PdfOptions();
	// اسلایدهای مخفی را اضافه می‌کند
	pdfOptions.ShowHiddenSlides = true;
	// ارائه را به صورت PDF ذخیره می‌کند
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

مثال زیر نشان می‌دهد چگونه می‌توان PowerPoint را به PDF با محافظت توسط رمز عبور تبدیل کرد.

```csharp
[C#]
// یک نمونه از شیء Presentation که نمایانگر یک فایل PowerPoint است
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// یک نمونه از کلاس PdfOptions را ایجاد می‌کند
	PdfOptions pdfOptions = new PdfOptions();
	// رمز عبور PDF و اجازه‌های دسترسی را تنظیم می‌کند
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// ارائه را به صورت PDF ذخیره می‌کند
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

مثال زیر نشان می‌دهد چگونه می‌توان PowerPoint را به PDF با یادداشت‌ها تبدیل کرد.

```csharp
[C#]
// یک شیء Presentation را که نمایانگر یک فایل ارائه است، ایجاد می‌کند
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
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->