---
title: IPdfOptions
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: विकल्प प्रदान करता है जो नियंत्रित करते हैं कि प्रस्तुति को Pdf स्वरूप में कैसे सहेजा जाता है।
type: docs
weight: 4000
url: /hi/aspose.slides.export/ipdfoptions/
---
## IPdfOptions इंटरफ़ेस

Provides options that control how a presentation is saved in Pdf format.

```csharp
public interface IPdfOptions : ISaveOptions
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | जब दस्तावेज़ उपयोगकर्ता पहुंच के साथ खोला जाता है तो कौन सी पहुंच अनुमतियों को दिया जाना चाहिए, यह निर्दिष्ट करने वाले फ़्लैग्स का एक सेट सम्मिलित करता है। देखें [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | Aspose.Slides द्वारा सामान्य मानने के लिए फ़ॉन्ट परिवारों के उपयोगकर्ता-परिभाषित नामों की एक सरणी को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | यदि `true` है तो निर्दिष्ट पारदर्शी रंग को छवि पर लागू करता है। |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | ISaveOptions इंटरफ़ेस को लौटाता है। केवल पढ़ने योग्य [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | यह दर्शाता है कि प्रत्येक छवि के लिए सबसे प्रभावी संपीड़न (डिफ़ॉल्ट के बजाय) को स्वचालित रूप से चुना जाना चाहिए या नहीं। यदि Boolean.true पर सेट किया गया है, तो प्रस्तुति की प्रत्येक छवि के लिए सबसे उपयुक्त संपीड़न एल्गोरिद्म चुना जाएगा, जिससे उत्पन्न PDF दस्तावेज़ का आकार छोटा होगा। सर्वोत्तम छवि संपीड़न अनुपात का चयन गणनात्मक रूप से महंगा है और अतिरिक्त RAM की आवश्यकता होती है, और यह विकल्प डिफ़ॉल्ट रूप से Boolean.false है। |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | उत्पन्न PDF दस्तावेज़ के लिए वांछित अनुरूपता स्तर। पढ़ने/लिखने योग्य [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | प्रत्येक स्लाइड के चारों ओर काला फ्रेम खींचने के लिए True। पढ़ने/लिखने योग्य Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | निर्धारित करता है कि फ़ॉन्ट के सभी अक्षर एम्बेड किए जाएँ या केवल उपयोग किया गया उपसमुच्चय। पढ़ने/लिखने योग्य Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | ASCII अक्षर 32-127 के लिए True टाइप फ़ॉन्ट एम्बेड करने के लिए True। 127 से बड़े अक्षर कोड के फ़ॉन्ट हमेशा एम्बेड किए जाते हैं। पढ़ने/लिखने योग्य Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | छवि के पारदर्शी रंग को प्राप्त करता है या सेट करता है. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | प्रस्तुति से सभी OLE डेटा को परिणामी PDF में एम्बेडेड फ़ाइलों में बदलने के लिए True। पढ़ने/लिखने योग्य Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | निर्यात किए गए दस्तावेज़ में Ink वस्तुओं की उपस्थिति को नियंत्रित करने वाले विकल्प प्रदान करता है। केवल पढ़ने योग्य [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | PDF दस्तावेज़ के भीतर JPEG छवियों की गुणवत्ता निर्धारित करने वाला मान लौटाता है या सेट करता है। पढ़ने/लिखने योग्य Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | PDF दस्तावेज़ को संरक्षित करने के लिए उपयोगकर्ता पासवर्ड सेट करना। पढ़ने/लिखने योग्य String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | यदि फ़ॉन्ट बोल्ड शैली का समर्थन नहीं करता है तो पाठ को बिटमैप के रूप में रास्टराइज़ करके PDF में सहेजना चाहिए या नहीं, यह दर्शाता है। यह दृष्टिकोण कुछ फ़ॉन्ट्स के लिए परिणामस्वरूप PDF में पाठ की गुणवत्ता को बढ़ा सकता है। पढ़ने/लिखने योग्य Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | प्रस्तुति में उपयोग किए गए सभी मेटाफाइलों को PNG छवियों में बदलने के लिए True। पढ़ने/लिखने योग्य Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइडें शामिल होनी चाहिए या नहीं। डिफ़ॉल्ट `false` है। |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | PDF दस्तावेज़ के भीतर छवियों के रिज़ॉल्यूशन को निर्धारित करने वाला मान लौटाता है या सेट करता है. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | दस्तावेज़ के सभी पाठ्य सामग्री के लिए उपयोग किए जाने वाले संपीड़न प्रकार को निर्दिष्ट करता है। पढ़ने/लिखने योग्य [`PdfTextCompression`](../pdftextcompression). |

### देखें

* इंटरफ़ेस [ISaveOptions](../isaveoptions)
* नामस्थान [Aspose.Slides.Export](../../aspose.slides.export)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->