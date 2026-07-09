---
title: PdfOptions
second_title: Aspose.Sildes .NET के लिए API संदर्भ
description: एक प्रस्तुति को Pdf प्रारूप में सहेजने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।
type: docs
weight: 4330
url: /hi/aspose.slides.export/pdfoptions/
---
## PdfOptions क्लास

Provides options that control how a presentation is saved in Pdf format.

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [PdfOptions](pdfoptions)() | डिफ़ॉल्ट कंस्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | दस्तावेज़ को उपयोगकर्ता पहुँच के साथ खोलते समय किन एक्सेस अनुमतियों को प्रदान किया जाना चाहिए, यह निर्दिष्ट करने वाले फ़्लैग का सेट शामिल करता है। देखें [`PdfAccessPermissions`](../pdfaccesspermissions)। |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Aspose.Slides द्वारा सामान्य माना जाने वाले फ़ॉन्ट परिवारों के उपयोगकर्ता-परिभाषित नामों की सरणी को प्राप्त करता है या सेट करता है। पढ़ें/लिखें String[]। |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | यदि `true` हो तो छवि पर निर्दिष्ट पारदर्शी रंग लागू करता है। |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | प्रत्येक छवि के लिए सबसे प्रभावी संपीड़न (डिफ़ॉल्ट के बजाय) को स्वचालित रूप से चुनना चाहिए या नहीं को दर्शाता है। यदि Boolean.true पर सेट किया जाता है, तो प्रस्तुति में हर छवि के लिए सबसे उपयुक्त संपीड़न एल्गोरिदम चुना जाएगा, जिससे उत्पन्न PDF दस्तावेज़ का आकार छोटा होगा। सर्वोत्तम छवि संपीड़न अनुपात चयन गणनात्मक रूप से महंगा है और अतिरिक्त RAM लेता है, और यह विकल्प डिफ़ॉल्ट रूप से Boolean.false है। |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | उत्पन्न PDF दस्तावेज़ के लिए वांछित अनुपालन स्तर। पढ़ें/लिखें [`PdfCompliance`](../pdfcompliance)। |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | स्रोत फ़ॉन्ट न मिलने पर उपयोग किए जाने वाले फ़ॉन्ट को प्राप्त करता है या सेट करता है। पढ़ें/लिखें String। |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | प्रत्येक स्लाइड के चारों ओर काली फ्रेम बनाने के लिए true। पढ़ें/लिखें Boolean। |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | सभी अक्षरों को एम्बेड किया जाना चाहिए या केवल उपयोग किए गए उपसमुच्चय को, यह निर्धारित करता है। पढ़ें/लिखें Boolean। |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | ASCII (33..127 कोड रेंज) पाठ के लिए Aspose.Slides सामान्य फ़ॉन्ट्स को एम्बेड करेगा या नहीं। 127 से बड़े कोड वाले फ़ॉन्ट हमेशा एम्बेड किए जाते हैं। सामान्य फ़ॉन्ट सूची में PDF के बेज़ 14 फ़ॉन्ट और उपयोगकर्ता-निर्दिष्ट अतिरिक्त फ़ॉन्ट शामिल हैं। पढ़ें/लिखें Boolean। |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | ग्रेडिएंट की दृश्य शैली को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`GradientStyle`](../../aspose.slides/gradientstyle)। |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | चित्र के पारदर्शी रंग को प्राप्त करता है या सेट करता है। |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | प्रस्तुति से सभी OLE डेटा को परिणामस्वरूप PDF में एम्बेडेड फ़ाइलों में बदलने के लिए true। पढ़ें/लिखें Boolean। |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | निर्यातित दस्तावेज़ में Ink वस्तुओं के स्वरूप को नियंत्रित करने के विकल्प प्रदान करता है। केवल-पढ़ने योग्य [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | PDF दस्तावेज़ के भीतर JPEG चित्रों की गुणवत्ता निर्धारित करने वाला मान प्राप्त करता है या सेट करता है। पढ़ें/लिखें Byte। |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | PDF दस्तावेज़ की सुरक्षा हेतु उपयोगकर्ता पासवर्ड सेट करता है। पढ़ें/लिखें String। |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | प्रतिशत में सहेजने की प्रगति अपडेट के लिए कॉलबैक ऑब्जेक्ट दर्शाता है। देखें [`IProgressCallback`](../../aspose.slides/iprogresscallback)। |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | जब फ़ॉन्ट बोल्ड शैली का समर्थन नहीं करता, तो पाठ को बिटमैप के रूप में रास्टराइज़ करके PDF में सहेजना चाहिए या नहीं यह दर्शाता है। यह दृष्टिकोण कुछ फ़ॉन्ट्स के लिए परिणामस्वरूप PDF में पाठ की गुणवत्ता बढ़ा सकता है। पढ़ें/लिखें Boolean। |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | प्रस्तुति में उपयोग की गई सभी मेटाफाइल्स को PNG चित्रों में बदलने के लिए true। पढ़ें/लिखें Boolean। |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल करनी चाहिए या नहीं, इसे निर्दिष्ट करता है। डिफ़ॉल्ट `false` है। |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | प्रस्तुति सहेजते समय जावास्क्रिप्ट कॉल वाली हाइपरलिंक्स को छोड़ना चाहिए या नहीं। पढ़ें/लिखें Boolean। डिफ़ॉल्ट मान **false** है। |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है [`ISlidesLayoutOptions`](../islideslayoutoptions)। |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | PDF दस्तावेज़ के भीतर चित्रों का रिज़ॉल्यूशन निर्धारित करने वाला मान प्राप्त करता है या सेट करता है। |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | दस्तावेज़ की सभी टेक्स्ट्युअल सामग्री के लिए उपयोग किए जाने वाले संपीड़न प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [`PdfTextCompression`](../pdftextcompression)। |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | चेतावनियों को प्राप्त करने और यह तय करने वाले ऑब्जेक्ट को प्राप्त करता है या सेट करता है कि लोडिंग प्रक्रिया जारी रखनी है या रोकनी है। पढ़ें/लिखें [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback)। |

### उदाहरण

PowerPoint को कस्टम विकल्पों के साथ PDF में बदलने का निम्न उदाहरण दिखाया गया है।

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// PdfOptions क्लास का इंस्टेंस बनाता है
	PdfOptions pdfOptions = new PdfOptions();
	// Jpeg गुणवत्ता सेट करता है
	pdfOptions.JpegQuality = 90;
	// मेटाफाइल्स के व्यवहार को सेट करता है
	pdfOptions.SaveMetafilesAsPng = true;
	// टेक्स्ट संपीड़न स्तर सेट करता है
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// PDF मानक को परिभाषित करता है
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// प्रस्तुति को PDF के रूप में सहेजता है
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

PowerPoint को छिपी स्लाइड्स के साथ PDF में बदलने का निम्न उदाहरण दिखाया गया है।

```csharp
[C#]
// एक Presentation क्लास का इंस्टेंस बनाता है जो PowerPoint फ़ाइल का प्रतिनिधित्व करता है
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// PdfOptions क्लास का इंस्टेंस बनाता है
	PdfOptions pdfOptions = new PdfOptions();
	// छिपी स्लाइड्स जोड़ता है
	pdfOptions.ShowHiddenSlides = true;
	// प्रस्तुति को PDF के रूप में सहेजता है
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

PowerPoint को पासवर्ड सुरक्षा वाले PDF में बदलने का निम्न उदाहरण दिखाया गया है।

```csharp
[C#]
// एक Presentation ऑब्जेक्ट का इंस्टेंस बनाता है जो PowerPoint फ़ाइल का प्रतिनिधित्व करता है
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// PdfOptions क्लास का इंस्टेंस बनाता है
	PdfOptions pdfOptions = new PdfOptions();
	// PDF पासवर्ड और एक्सेस अनुमतियों को सेट करता है
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// प्रस्तुति को PDF के रूप में सहेजता है
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

PowerPoint को नोट्स के साथ PDF में बदलने का निम्न उदाहरण दिखाया गया है।

```csharp
[C#]
// एक Presentation ऑब्जेक्ट बनाता है जो प्रस्तुति फ़ाइल का प्रतिनिधित्व करता है
using (Presentation presentation = new Presentation("SelectedSlides.pptx"))
{
	using (Presentation auxPresentation = new Presentation())
	{
		ISlide slide = presentation.Slides[0];
		auxPresentation.Slides.InsertClone(0, slide);
		// स्लाइड प्रकार और आकार सेट करना
		//auxPresentation.SlideSize.SetSize(presentation.SlideSize.Size.Width, presentation.SlideSize.Size.Height,SlideSizeScaleType.EnsureFit);
		auxPresentation.SlideSize.SetSize(612F, 792F, SlideSizeScaleType.EnsureFit);
		PdfOptions pdfOptions = new PdfOptions();
		pdfOptions.SlidesLayoutOptions = new NotesCommentsLayoutingOptions() { NotesPosition = NotesPositions.BottomFull };
		auxPresentation.Save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
	}
}
```

### संदर्भ

* क्लास [SaveOptions](../saveoptions)
* इंटरफ़ेस [IPdfOptions](../ipdfoptions)
* नेमस्पेस [Aspose.Slides.Export](../../aspose.slides.export)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->