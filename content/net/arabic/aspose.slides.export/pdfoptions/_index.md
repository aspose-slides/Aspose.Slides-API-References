---
title: PdfOptions
second_title: Aspose.Sildes لـ .NET مرجع API
description: يقدم خيارات تتحكم في كيفية حفظ العرض التقديمي بتنسيق Pdf.
type: docs
weight: 4330
url: /ar/aspose.slides.export/pdfoptions/
---
## فئة PdfOptions

يوفر خيارات تتحكم في كيفية حفظ العرض التقديمي بتنسيق Pdf.

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## المنشئات

| Name | Description |
| --- | --- |
| [PdfOptions](pdfoptions)() | المنشئ الافتراضي. |

## الخصائص

| Name | Description |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | تحتوي على مجموعة من العلامات التي تحدد أية أذونات وصول يجب منحها عند فتح المستند مع وصول المستخدم. راجع [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | تعيد أو تعين مصفوفة من أسماء عائلات الخطوط المعرفة من قبل المستخدم والتي يجب على Aspose.Slides اعتبارها شائعة. قراءة/كتابة String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | يطبق اللون الشفاف المحدد على الصورة إذا كان `true`. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | يشير إلى ما إذا كان يجب اختيار أفضل ضغط (بدلاً من الضغط الافتراضي) لكل صورة تلقائيًا. إذا تم ضبطه على Boolean.true، سيتم اختيار خوارزمية الضغط الأكثر ملاءمة لكل صورة في العرض التقديمي، مما يؤدي إلى صغر حجم مستند PDF الناتج. اختيار أفضل نسبة ضغط للصور يتطلب حسابات مكثفة ويستهلك كمية إضافية من الذاكرة RAM، وهذا الخيار هو Boolean.false بشكل افتراضي. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | مستوى الامتثال المطلوب لمستند PDF المُنشأ. قراءة/كتابة [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | تعيد أو تعين الخط المستخدم في حال عدم العثور على الخط المصدر. قراءة/كتابة String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | True لرسم إطار أسود حول كل شريحة. قراءة/كتابة Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | يحدد ما إذا كان يجب تضمين جميع أحرف الخط أم فقط مجموعة فرعية مستخدمة. قراءة/كتابة Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | يحدد ما إذا كان Aspose.Slides سيضمّن خطوطًا شائعة لنص ASCII (نطاق الرموز 33..127). الخطوط للرموز التي تزيد عن 127 تُضمّن دائمًا. تشمل قائمة الخطوط الشائعة الخطوط الأساسية 14 في PDF وخطوطًا إضافية يحددها المستخدم. قراءة/كتابة Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | تعيد أو تعين النمط البصري للتدرج. قراءة/كتابة [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | تسترجع أو تعين لون شفافية الصورة. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | True لتحويل جميع بيانات OLE من العرض التقديمي إلى ملفات مضمّنة في PDF الناتج. قراءة/كتابة Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | توفر خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدَّر. قراءة فقط [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | تعيد أو تعين قيمة تحدد جودة صور JPEG داخل مستند PDF. قراءة/كتابة Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | تعيين كلمة مرور المستخدم لحماية مستند PDF. قراءة/كتابة String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | يمثل كائن استدعاء لتحديثات حفظ التقدم بنسب مئوية. راجع [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | يشير إلى ما إذا كان يجب تحويل النص إلى صورة نقطية وحفظه في PDF عندما لا يدعم الخط تنسيق غامق. هذا النهج يمكن أن يعزز جودة النص في PDF الناتج لبعض الخطوط. قراءة/كتابة Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | True لتحويل جميع ملفات الميتا المستخدمة في العرض التقديمي إلى صور PNG. قراءة/كتابة Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | يحدد ما إذا كان المستند المُولد يجب أن يتضمن الشرائح المخفية أم لا. القيمة الافتراضية هي `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | يحدد ما إذا كان يجب تخطي الروابط التشعبية التي تستدعي جافا سكربت عند حفظ العرض التقديمي. قراءة/كتابة Boolean. القيمة الافتراضية هي **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | تسترجع أو تعين الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | تعيد أو تعين قيمة تحدد دقة الصور داخل مستند PDF. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | يحدد نوع الضغط المستخدم لجميع المحتويات النصية في المستند. قراءة/كتابة [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | تعيد أو تعين كائنًا يستقبل التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أم ستُفصل. قراءة/كتابة [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### أمثلة

المثال التالي يوضح كيفية تحويل PowerPoint إلى PDF باستخدام خيارات مخصصة.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// ينشئ فئة PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// يحدد جودة Jpeg
	pdfOptions.JpegQuality = 90;
	// يحدد سلوك ملفات الميتا
	pdfOptions.SaveMetafilesAsPng = true;
	// يحدد مستوى ضغط النص
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// يحدد معيار PDF
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// يحفظ العرض التقديمي كملف PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

المثال التالي يوضح كيفية تحويل PowerPoint إلى PDF مع تضمين الشرائح المخفية.

```csharp
[C#]
// ينشئ فئة Presentation التي تمثل ملف PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// ينشئ فئة PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// يضيف الشرائح المخفية
	pdfOptions.ShowHiddenSlides = true;
	// يحفظ العرض التقديمي كملف PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

المثال التالي يوضح كيفية تحويل PowerPoint إلى PDF محمي بكلمة مرور.

```csharp
[C#]
// ينشئ كائن Presentation الذي يمثل ملف PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// ينشئ فئة PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// يحدد كلمة مرور PDF وأذونات الوصول
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// يحفظ العرض التقديمي كملف PDF
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

المثال التالي يوضح كيفية تحويل PowerPoint إلى PDF مع الملاحظات.

```csharp
[C#]
// إنشاء كائن Presentation الذي يمثل ملف عرض تقديمي
using (Presentation presentation = new Presentation("SelectedSlides.pptx"))
{
	using (Presentation auxPresentation = new Presentation())
	{
		ISlide slide = presentation.Slides[0];
		auxPresentation.Slides.InsertClone(0, slide);
		// تحديد نوع الشريحة وحجمها
		//auxPresentation.SlideSize.SetSize(presentation.SlideSize.Size.Width, presentation.SlideSize.Size.Height,SlideSizeScaleType.EnsureFit);
		auxPresentation.SlideSize.SetSize(612F, 792F, SlideSizeScaleType.EnsureFit);
		PdfOptions pdfOptions = new PdfOptions();
		pdfOptions.SlidesLayoutOptions = new NotesCommentsLayoutingOptions() { NotesPosition = NotesPositions.BottomFull };
		auxPresentation.Save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
	}
}
```

### انظر أيضًا

* فئة [SaveOptions](../saveoptions)
* واجهة [IPdfOptions](../ipdfoptions)
* نطاق الاسم [Aspose.Slides.Export](../../aspose.slides.export)
* تجميعة [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->