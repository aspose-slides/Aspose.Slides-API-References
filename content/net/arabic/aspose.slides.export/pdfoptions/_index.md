---
title: PdfOptions
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يوفر خيارات تتحكم في كيفية حفظ عرض تقديمي بصيغة Pdf.
type: docs
weight: 4350
url: /ar/aspose.slides.export/pdfoptions/
---
## PdfOptions فئة

يوفر خيارات تتحكم في كيفية حفظ العرض بصيغة PDF.

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
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | يحتوي على مجموعة من العلامات التي تحدد أذونات الوصول التي يجب منحها عندما يُفتح المستند بصلاحية المستخدم. انظر [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | إرجاع أو تعيين مصفوفة من أسماء عائلات الخطوط المعرّفة من قبل المستخدم والتي يجب على Aspose.Slides اعتبارها شائعة. قراءة/كتابة String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | يطبق اللون الشفاف المحدد على الصورة إذا كان `true`. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | يشير إلى ما إذا كان يجب اختيار أكثر ضغط فعّال (بدلاً من الافتراضي) لكل صورة تلقائيًا. إذا تم تعيينه إلى Boolean.true، سيتم اختيار أفضل خوارزمية ضغط لكل صورة في العرض، مما يؤدي إلى صغر حجم مستند PDF الناتج. اختيار أفضل نسبة ضغط للصورة يتطلب حسابًا مكثفًا ويستهلك ذاكرة RAM إضافية، وهذا الخيار يكون Boolean.false بشكل افتراضي. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | المستوى المطلوب للامتثال لمستند PDF المُنشأ. قراءة/كتابة [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | إرجاع أو تعيين الخط المستخدم في حالة عدم العثور على الخط الأصلي. قراءة/كتابة String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | صحيح لرسم إطار أسود حول كل شريحة. قراءة/كتابة Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | يحدد ما إذا كان يجب تضمين جميع أحرف الخط أو فقط مجموعة فرعية مستخدمة. قراءة/كتابة Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | يحدد ما إذا كان Aspose.Slides سيضمّن الخطوط الشائعة لنص ASCII (نطاق الرموز 33..127). الخطوط للأكواد التي تزيد عن 127 تُضمّن دائمًا. تشمل قائمة الخطوط الشائعة الخطوط الأساسية الـ14 في PDF وخطوط إضافية يحددها المستخدم. قراءة/كتابة Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | إرجاع أو تعيين النمط البصري للتدرج. قراءة/كتابة [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | إرجاع أو تعيين لون الشفافية للصورة. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | صحيح لتحويل جميع بيانات OLE من العرض إلى ملفات مضمّنة في PDF الناتج. قراءة/كتابة Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدّر. قراءة فقط [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | إرجاع أو تعيين قيمة تحدد جودة صور JPEG داخل مستند PDF. قراءة/كتابة Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | تعيين كلمة مرور المستخدم لحماية مستند PDF. قراءة/كتابة String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | يمثل كائن استدعاء للعودة لتحديثات حفظ التقدم بالنسبة المئوية. انظر [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | يحدد ما إذا كان يجب تحويل النص إلى صورة نقطية وحفظه إلى PDF عندما لا يدعم الخط نمط الخط العريض. يمكن لهذا النهج تحسين جودة النص في PDF الناتج لبعض الخطوط. قراءة/كتابة Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | صحيح لتحويل جميع ملفات الميتا المستخدمة في العرض إلى صور PNG. قراءة/كتابة Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | يحدد ما إذا كان المستند المُنشأ يجب أن يتضمن شرائح مخفية أم لا. القيمة الافتراضية هي `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | يحدد ما إذا كان يجب تخطي الروابط التشعبية التي تستدعي JavaScript عند حفظ العرض. قراءة/كتابة Boolean. القيمة الافتراضية هي **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | إرجاع أو تعيين الوضع الذي تُوضَع به الشرائح على الصفحة عند تصدير عرض [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | إرجاع أو تعيين قيمة تحدد دقة الصور داخل مستند PDF. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | يحدد نوع الضغط المستخدم لجميع المحتويات النصية في المستند. قراءة/كتابة [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | إرجاع أو تعيين كائن يستقبل التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أم ستُوقف. قراءة/كتابة [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### أمثلة

يعرض المثال التالي كيفية تحويل PowerPoint إلى PDF باستخدام خيارات مخصصة.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// ينشئ كائن من فئة PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// يعيّن جودة JPEG
	pdfOptions.JpegQuality = 90;
	// يعيّن سلوك ملفات الميتا
	pdfOptions.SaveMetafilesAsPng = true;
	// يعيّن مستوى ضغط النص
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// يحدد معيار PDF
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// يحفظ العرض التقديمي كملف PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

يعرض المثال التالي كيفية تحويل PowerPoint إلى PDF مع الشرائح المخفية.

```csharp
[C#]
// ينشئ كائن فئة Presentation يمثل ملف PowerPoint
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

يعرض المثال التالي كيفية تحويل PowerPoint إلى PDF محمي بكلمة مرور.

```csharp
[C#]
// ينشئ كائن Presentation يمثل ملف PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// ينشئ كائن من فئة PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// يعيّن كلمة مرور PDF وأذونات الوصول
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// يحفظ العرض التقديمي كملف PDF
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

يعرض المثال التالي كيفية تحويل PowerPoint إلى PDF مع الملاحظات.

```csharp
[C#]
// إنشاء كائن Presentation يمثل ملف عرض تقديمي
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
* نطاق [Aspose.Slides.Export](../../aspose.slides.export)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->