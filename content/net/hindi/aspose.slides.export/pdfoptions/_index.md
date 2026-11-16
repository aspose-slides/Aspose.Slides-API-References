---
title: PdfOptions
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: विकल्प प्रदान करता है जो नियंत्रित करते हैं कि प्रस्तुति को Pdf प्रारूप में कैसे सहेजा जाता है।
type: docs
weight: 4350
url: /hi/aspose.slides.export/pdfoptions/
---
## PdfOptions क्लास

एक प्रस्तुति को Pdf फ़ॉर्मेट में सहेजने के तरीकों को नियंत्रित करने वाले विकल्प प्रदान करता है।

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## Constructors

| नाम | विवरण |
| --- | --- |
| [PdfOptions](pdfoptions)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## Properties

| नाम | विवरण |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | फ़्लैगों का एक सेट शामिल करता है जो यह निर्दिष्ट करता है कि दस्तावेज़ को उपयोगकर्ता एक्सेस के साथ खोलने पर कौन सी पहुँच अनुमतियों को दिया जाना चाहिए। देखें [`PdfAccessPermissions`](../pdfaccesspermissions)। |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | फ़ॉन्ट फ़ैमिलियों के उपयोगकर्ता-परिभाषित नामों की एक सरणी लौटाता है या सेट करता है जिसे Aspose.Slides सामान्य माना जाना चाहिए। पढ़ें/लिखें String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | यदि `true` हो तो निर्दिष्ट पारदर्शी रंग को छवि पर लागू करता है। |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | इसे इंगित करता है कि क्या प्रत्येक छवि के लिए सबसे प्रभावी संपीड़न (डिफ़ॉल्ट के बजाय) स्वचालित रूप से चयनित किया जाना चाहिए। यदि इसे Boolean.true पर सेट किया जाता है, तो प्रस्तुति में प्रत्येक छवि के लिए सबसे उपयुक्त संपीड़न एल्गोरिद्म चुना जाएगा, जिससे परिणामी PDF दस्तावेज़ का आकार छोटा होगा। सर्वोत्तम छवि संपीड़न अनुपात चयन गणनात्मक रूप से महंगा है और अतिरिक्त RAM की आवश्यकता होती है, और यह विकल्प डिफ़ॉल्ट रूप से Boolean.false है। |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | निर्मित PDF दस्तावेज़ के लिए इच्छित अनुपालन स्तर। पढ़ें/लिखें [`PdfCompliance`](../pdfcompliance)। |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले फ़ॉन्ट को लौटाता है या सेट करता है। पढ़ें/लिखें String। |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | प्रत्येक स्लाइड के चारों ओर काला फ्रेम ड्रॉ करने के लिए true। पढ़ें/लिखें Boolean। |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | निर्धारित करता है कि फ़ॉन्ट के सभी अक्षरों को एम्बेड किया जाए या केवल प्रयुक्त उपसमुच्चय। पढ़ें/लिखें Boolean। |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | निर्धारित करता है कि Aspose.Slides ASCII (33..127 कोड रेंज) टेक्स्ट के लिए सामान्य फ़ॉन्ट एम्बेड करेगा या नहीं। 127 से अधिक कोड वाले अक्षरों के फ़ॉन्ट हमेशा एम्बेड होते हैं। सामान्य फ़ॉन्ट सूची में PDF के बेस 14 फ़ॉन्ट और अतिरिक्त उपयोगकर्ता-निर्दिष्ट फ़ॉन्ट शामिल हैं। पढ़ें/लिखें Boolean। |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | ग्रेडिएंट की दृश्य शैली को लौटाता है या सेट करता है। पढ़ें/लिखें [`GradientStyle`](../../aspose.slides/gradientstyle)। |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | छवि का पारदर्शी रंग प्राप्त करता है या सेट करता है। |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | प्रस्तुति से सभी OLE डेटा को परिणामी PDF में एम्बेडेड फ़ाइलों में परिवर्तित करने के लिए true। पढ़ें/लिखें Boolean। |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | निर्यात किए गए दस्तावेज़ में Ink ऑब्जेक्ट्स की दिखावट को नियंत्रित करने वाले विकल्प प्रदान करता है। केवल पढ़ने योग्य [`IInkOptions`](../iinkoptions)। |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | PDF दस्तावेज़ के भीतर JPEG छवियों की गुणवत्ता निर्धारित करने वाला मान लौटाता है या सेट करता है। पढ़ें/लिखें Byte। |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | PDF दस्तावेज़ की सुरक्षा के लिए उपयोगकर्ता पासवर्ड सेट करता है। पढ़ें/लिखें String। |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | प्रतिशत में सहेजने की प्रगति अपडेट के लिए एक callback ऑब्जेक्ट का प्रतिनिधित्व करता है। देखें [`IProgressCallback`](../../aspose.slides/iprogresscallback)। |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | जब फ़ॉन्ट बोल्ड स्टाइलिंग का समर्थन नहीं करता है, तो टेक्स्ट को बिटमैप के रूप में रास्टराइज़ किया जाए और PDF में सहेजा जाए, यह दर्शाता है। यह तरीका कुछ फ़ॉन्ट्स के लिए परिणामस्वरूप PDF में टेक्स्ट की गुणवत्ता को बढ़ा सकता है। पढ़ें/लिखें Boolean। |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | प्रस्तुति में उपयोग किए गए सभी मेटा फ़ाइलों को PNG छवियों में परिवर्तित करने के लिए true। पढ़ें/लिखें Boolean। |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल होनी चाहिए या नहीं। डिफ़ॉल्ट `false` है। |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | प्रस्तुति सहेजते समय JavaScript कॉल वाले हाइपरलिंक को छोड़ना है या नहीं, यह निर्दिष्ट करता है। पढ़ें/लिखें Boolean। डिफ़ॉल्ट मान **false** है। |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर जिस मोड में रखा जाता है, उसे प्राप्त करता है या सेट करता है [`ISlidesLayoutOptions`](../islideslayoutoptions)। |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | PDF दस्तावेज़ के भीतर छवियों के रिज़ॉल्यूशन को निर्धारित करने वाला मान लौटाता है या सेट करता है। |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | दस्तावेज़ में सभी पाठ्य सामग्री के लिए उपयोग किए जाने वाले संपीड़न प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [`PdfTextCompression`](../pdftextcompression)। |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | एक ऑब्जेक्ट लौटाता है या सेट करता है जो चेतावनियों को प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द की जाएगी। पढ़ें/लिखें [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback)। |

### उदाहरण

निम्न उदाहरण दिखाता है कि कैसे कस्टम विकल्पों के साथ PowerPoint को PDF में परिवर्तित किया जाए।

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// PdfOptions क्लास को बनाता है
	PdfOptions pdfOptions = new PdfOptions();
	// Jpeg गुणवत्ता सेट करता है
	pdfOptions.JpegQuality = 90;
	// मेटा फ़ाइलों के व्यवहार को सेट करता है
	pdfOptions.SaveMetafilesAsPng = true;
	// टेक्स्ट संपीड़न स्तर सेट करता है
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// PDF मानक को परिभाषित करता है
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// प्रस्तुति को PDF के रूप में सहेजता है
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

निम्न उदाहरण दिखाता है कि कैसे छिपी स्लाइड्स के साथ PowerPoint को PDF में परिवर्तित किया जाए।

```csharp
[C#]
// Presentation क्लास को इंस्टैंसिएट करता है जो एक PowerPoint फ़ाइल का प्रतिनिधित्व करता है
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// PdfOptions क्लास को इंस्टैंसिएट करता है
	PdfOptions pdfOptions = new PdfOptions();
	// छिपी स्लाइड्स जोड़ता है
	pdfOptions.ShowHiddenSlides = true;
	// प्रस्तुति को PDF के रूप में सहेजता है
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

निम्न उदाहरण दिखाता है कि कैसे पासवर्ड सुरक्षित PDF के साथ PowerPoint को PDF में परिवर्तित किया जाए।

```csharp
[C#]
// Presentation ऑब्जेक्ट को इंस्टैंसिएट करता है जो एक PowerPoint फ़ाइल का प्रतिनिधित्व करता है
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// PdfOptions क्लास को इंस्टैंसिएट करता है
	PdfOptions pdfOptions = new PdfOptions();
	// PDF पासवर्ड और पहुँच अनुमतियों को सेट करता है
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// प्रस्तुति को PDF के रूप में सहेजता है
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

निम्न उदाहरण दिखाता है कि कैसे नोट्स के साथ PowerPoint को PDF में परिवर्तित किया जाए।

```csharp
[C#]
// प्रस्तुतीकरण फ़ाइल का प्रतिनिधित्व करने वाले Presentation ऑब्जेक्ट को बनाता है
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
* नेमस्पेस [Aspose.Slides.Export](../../aspose.slides.export)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->