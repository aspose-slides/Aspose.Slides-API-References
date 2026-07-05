---
title: PdfOptions
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: विकल्प प्रदान करता है जो नियंत्रित करते हैं कि एक प्रस्तुति को PDF स्वरूप में कैसे सहेजा जाता है।
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
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | फ़्लैग्स का एक सेट शामिल करता है जो यह निर्दिष्ट करता है कि दस्तावेज़ को उपयोगकर्ता पहुँच के साथ खोलते समय कौन सी एक्सेस अनुमतियाँ प्रदान की जाएँ। देखें [`PdfAccessPermissions`](../pdfaccesspermissions)। |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | फ़ॉन्ट परिवारों के उपयोगकर्ता-परिभाषित नामों की एक सरणी लौटाता है या सेट करता है जिसे Aspose.Slides सामान्य मानना चाहिए। पढ़ें/लिखें String[]। |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | यदि `true` हो तो निर्दिष्ट पारदर्शी रंग को एक छवि पर लागू करता है। |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | निर्दिष्ट करता है कि प्रत्येक छवि के लिए सबसे प्रभावी संपीड़न (डिफ़ॉल्ट के बजाय) स्वचालित रूप से चयनित किया जाना चाहिए या नहीं। यदि इसे Boolean.true पर सेट किया जाता है, तो प्रस्तुति में प्रत्येक छवि के लिए सबसे उपयुक्त संपीड़न एल्गोरिथ्म चुना जाएगा, जिससे परिणामी PDF दस्तावेज़ का आकार छोटा होगा। सर्वोत्तम छवि संपीड़न अनुपात का चयन गणनात्मक रूप से महंगा है और अतिरिक्त RAM उपयोग करता है, और यह विकल्प डिफ़ॉल्ट रूप से Boolean.false है। |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | जनरेट किए गए PDF दस्तावेज़ के लिए वांछित अनुपालन स्तर। पढ़ें/लिखें [`PdfCompliance`](../pdfcompliance)। |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किया जाने वाला फ़ॉन्ट लौटाता है या सेट करता है। पढ़ें-लिखें String। |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | प्रत्येक स्लाइड के चारों ओर काली फ़्रेम बनाने के लिए true। पढ़ें/लिखें Boolean। |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | निर्धारित करता है कि फ़ॉन्ट के सभी अक्षर एम्बेड किए जाएँ या केवल उपयोग किए गए उपसमुच्चय। पढ़ें/लिखें Boolean। |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | निर्धारित करता है कि Aspose.Slides ASCII (33..127 कोड रेंज) टेक्स्ट के लिए सामान्य फ़ॉन्ट एम्बेड करेगा या नहीं। 127 से बड़े अक्षर कोड के फ़ॉन्ट हमेशा एम्बेड होते हैं। सामान्य फ़ॉन्ट सूची में PDF के बेस 14 फ़ॉन्ट तथा अतिरिक्त उपयोगकर्ता निर्दिष्ट फ़ॉन्ट शामिल हैं। पढ़ें/लिखें Boolean। |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | ग्रेडिएंट की दृश्य शैली लौटाता है या सेट करता है। पढ़ें/लिखें [`GradientStyle`](../../aspose.slides/gradientstyle)। |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | छवि के पारदर्शी रंग को प्राप्त करता है या सेट करता है। |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | प्रस्तुति से सभी OLE डेटा को परिणामी PDF में एम्बेडेड फ़ाइलें में बदलने के लिए true। पढ़ें/लिखें Boolean। |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | निर्यातित दस्तावेज़ में Ink वस्तुओं की रूपरेखा को नियंत्रित करने वाले विकल्प प्रदान करता है। केवल पढ़ने योग्य [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | PDF दस्तावेज़ के भीतर JPEG छवियों की गुणवत्ता निर्धारित करने वाला मान लौटाता है या सेट करता है। पढ़ें/लिखें Byte। |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | PDF दस्तावेज़ की सुरक्षा के लिए उपयोगकर्ता पासवर्ड सेट करना। पढ़ें/लिखें String। |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | प्रति प्रतिशत में सहेजने की प्रगति अद्यतनों के लिए एक कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है। देखें [`IProgressCallback`](../../aspose.slides/iprogresscallback)। |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | यह इंगित करता है कि फ़ॉन्ट बोल्ड स्टाइलिंग का समर्थन नहीं करता तो टेक्स्ट को बिटमैप के रूप में रास्टराइज़ करके PDF में सहेजा जाना चाहिए या नहीं। यह उपाय कुछ फ़ॉन्ट्स के लिए परिणामस्वरूप PDF में टेक्स्ट की गुणवत्ता को बढ़ा सकता है। पढ़ें/लिखें Boolean। |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | प्रस्तुति में उपयोग किए गए सभी मेटा फ़ाइलों को PNG छवियों में बदलने के लिए true। पढ़ें/लिखें Boolean। |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल होंगी या नहीं। डिफ़ॉल्ट `false` है। |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | प्रस्तुति सहेजते समय JavaScript कॉल वाले हाइपरलिंक को छोड़ें या नहीं, यह निर्दिष्ट करता है। पढ़ें/लिखें Boolean। डिफ़ॉल्ट मान **false** है। |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | प्रस्तुति को निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है [`ISlidesLayoutOptions`](../islideslayoutoptions)। |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | PDF दस्तावेज़ के भीतर छवियों की रिज़ॉल्यूशन निर्धारित करने वाला मान लौटाता है या सेट करता है। |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | दस्तावेज़ में सभी पाठ सामग्री के लिए उपयोग किए जाने वाले संपीड़न प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [`PdfTextCompression`](../pdftextcompression)। |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | चेतावनियां प्राप्त करने वाले और यह निर्णय लेने वाले ऑब्जेक्ट को लौटाता है या सेट करता है कि लोडिंग प्रक्रिया जारी रहेगी या रोक दी जाएगी। पढ़ें/लिखें [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback)। |

### उदाहरण

निम्न उदाहरण दिखाता है कि कैसे कस्टम विकल्पों के साथ PowerPoint को PDF में बदला जा सकता है।

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// PdfOptions क्लास का उदाहरण बनाता है
	PdfOptions pdfOptions = new PdfOptions();
	// Jpeg गुणवत्ता सेट करता है
	pdfOptions.JpegQuality = 90;
	// मेटाफाइलों के व्यवहार को सेट करता है
	pdfOptions.SaveMetafilesAsPng = true;
	// टेक्स्ट संपीड़न स्तर सेट करता है
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// PDF मानक को परिभाषित करता है
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// प्रस्तुति को PDF के रूप में सहेजता है
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

निम्न उदाहरण दिखाता है कि कैसे छिपी स्लाइड्स के साथ PowerPoint को PDF में बदला जा सकता है।

```csharp
[C#]
// PowerPoint फ़ाइल का प्रतिनिधित्व करने वाले Presentation क्लास का उदाहरण बनाता है
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// PdfOptions क्लास का उदाहरण बनाता है
	PdfOptions pdfOptions = new PdfOptions();
	// छिपी स्लाइड्स जोड़ता है
	pdfOptions.ShowHiddenSlides = true;
	// प्रस्तुति को PDF के रूप में सहेजता है
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

निम्न उदाहरण दिखाता है कि कैसे PowerPoint को पासवर्ड-संरक्षित PDF में बदला जा सकता है।

```csharp
[C#]
// PowerPoint फ़ाइल का प्रतिनिधित्व करने वाले Presentation ऑब्जेक्ट का उदाहरण बनाता है
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// PdfOptions क्लास का उदाहरण बनाता है
	PdfOptions pdfOptions = new PdfOptions();
	// PDF पासवर्ड और पहुँच अनुमतियों को सेट करता है
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// प्रस्तुति को PDF के रूप में सहेजता है
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

निम्न उदाहरण दिखाता है कि कैसे नोट्स के साथ PowerPoint को PDF में बदला जा सकता है।

```csharp
[C#]
// एक Presentation ऑब्जेक्ट का उदाहरण बनाता है जो एक प्रस्तुति फ़ाइल का प्रतिनिधित्व करता है
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

### देखें

* क्लास [SaveOptions](../saveoptions)
* इंटरफ़ेस [IPdfOptions](../ipdfoptions)
* नामस्थान [Aspose.Slides.Export](../../aspose.slides.export)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->