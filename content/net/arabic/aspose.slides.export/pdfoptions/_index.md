---
title: PdfOptions
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يوفر خيارات تتحكم في كيفية حفظ عرض تقديمي بصيغة Pdf.
type: docs
weight: 4330
url: /ar/aspose.slides.export/pdfoptions/
---
## فئة PdfOptions

يوفر خيارات تتحكم في كيفية حفظ العرض التقديمي بصيغة Pdf.

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfOptions](pdfoptions)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | يحتوي على مجموعة من العلامات التي تحدد أي أذونات وصول يجب منحها عند فتح المستند باستخدام وصول المستخدم. راجع [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | إرجاع أو تعيين مصفوفة من أسماء عائلات الخطوط المعرفة من قبل المستخدم والتي يجب على Aspose.Slides اعتبارها شائعة. قراءة/كتابة String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | يطبق اللون الشفاف المحدد على الصورة إذا كان `true`. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | يشير إلى ما إذا كان يجب اختيار أقوى ضغط (بدلاً من الضغط الافتراضي) لكل صورة تلقائيًا. إذا تم ضبطه على Boolean.true، سيتم اختيار خوارزمية الضغط الأنسب لكل صورة في العرض، مما سيؤدي إلى حجم أصغر لمستند PDF الناتج. اختيار أفضل نسبة ضغط للصور يتطلب حسابيًا تكلفة عالية ويستهلك مقدارًا إضافيًا من الذاكرة RAM، وهذا الخيار هو Boolean.false بشكل افتراضي. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | مستوى التوافق المطلوب لمستند PDF المُولَّد. قراءة/كتابة [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | إرجاع أو تعيين الخط المستخدم في حالة عدم العثور على الخط المصدر. قراءة/كتابة String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | صحيح لرسم إطار أسود حول كل شريحة. قراءة/كتابة Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | يحدد ما إذا كان يجب تضمين جميع أحرف الخط أو فقط المجموعة المستخدمة. قراءة/كتابة Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | يحدد ما إذا كانت Aspose.Slides ستضمّن الخطوط الشائعة لنص ASCII (نطاق الرموز 33..127). الخطوط للأكواد التي تزيد عن 127 يتم تضمينها دائمًا. قائمة الخطوط الشائعة تشمل الخطوط الأساسية الـ14 في PDF وخطوط إضافية يحددها المستخدم. قراءة/كتابة Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | إرجاع أو تعيين النمط البصري للتدرج. قراءة/كتابة [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | إرجاع أو تعيين اللون الشفاف للصورة. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | صحيح لتحويل جميع بيانات OLE من العرض إلى ملفات مضمّنة في PDF الناتج. قراءة/كتابة Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدّر. قراءة فقط [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | إرجاع أو تعيين قيمة تحدد جودة صور JPEG داخل مستند PDF. قراءة/كتابة Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | تعيين كلمة مرور المستخدم لحماية مستند PDF. قراءة/كتابة String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | يمثل كائن رد نداء لتحديثات تقدم الحفظ بالنسبة المئوية. راجع [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | يشير إلى ما إذا كان يجب تحويل النص إلى صورة نقطية (bitmap) وحفظه في PDF عندما لا يدعم الخط تنسيق غامق. يمكن لهذا النهج تحسين جودة النص في PDF الناتج لبعض الخطوط. قراءة/كتابة Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | صحيح لتحويل جميع ملفات metafile المستخدمة في العرض إلى صور PNG. قراءة/كتابة Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | يحدد ما إذا كان يجب أن يتضمن المستند المُولد شرائح مخفية أم لا. القيمة الافتراضية هي `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | يحدد ما إذا كان يجب تخطي الروابط التشعبية التي تحتوي على استدعاءات JavaScript عند حفظ العرض. قراءة/كتابة Boolean. القيمة الافتراضية هي **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | إرجاع أو تعيين الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير العرض [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | إرجاع أو تعيين قيمة تحدد دقة الصور داخل مستند PDF. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | يحدد نوع الضغط المستخدم لجميع المحتويات النصية في المستند. قراءة/كتابة [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | إرجاع أو تعيين كائن يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أم ستُوقف. قراءة/كتابة [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### أمثلة

المثال التالي يوضح كيفية تحويل PowerPoint إلى PDF باستخدام خيارات مخصصة.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// ينشئ كائن من فئة PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// يضبط جودة JPEG
	pdfOptions.JpegQuality = 90;
	// يضبط سلوك ملفات الميتا
	pdfOptions.SaveMetafilesAsPng = true;
	// يضبط مستوى ضغط النص
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// يعرف معيار PDF
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// يحفظ العرض التقديمي كملف PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

المثال التالي يوضح كيفية تحويل PowerPoint إلى PDF مع الشرائح المخفية.

```csharp
[C#]
// ينشئ كائن من فئة Presentation التي تمثل ملف PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// ينشئ كائن من فئة PdfOptions
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
	/// ينشئ كائن من فئة PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// يضبط كلمة مرور PDF وأذونات الوصول
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
		// تعيين نوع الشريحة وحجمها
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
* مساحة اسم [Aspose.Slides.Export](../../aspose.slides.export)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->