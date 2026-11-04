---
title: IPdfOptions
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: विकल्प प्रदान करता है जो यह नियंत्रित करते हैं कि प्रस्तुति को Pdf प्रारूप में कैसे सहेजा जाता है।
type: docs
weight: 4020
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
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | जब दस्तावेज़ को उपयोगकर्ता पहुंच के साथ खोलते हैं तो किस एक्सेस अनुमतियों को प्रदान किया जाना चाहिए, यह निर्दिष्ट करने वाले फ़्लैग्स का एक सेट शामिल करता है। देखें [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | फ़ॉन्ट परिवारों के उपयोगकर्ता-परिभाषित नामों की सरणी लौटाता है या सेट करता है, जिन्हें Aspose.Slides सामान्य मानना चाहिए। पढ़ें/लिखें String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | यदि `true` हो तो निर्दिष्ट ट्रांसपेरेंट रंग को छवि पर लागू करता है। |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | ISaveOptions इंटरफ़ेस लौटाता है। केवल-रीड [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | यदि यह निर्धारित करता है कि प्रत्येक छवि के लिए सबसे प्रभावी संपीड़न (डिफ़ॉल्ट के बजाय) स्वचालित रूप से चुना जाना चाहिए। यदि इसे Boolean.true पर सेट किया जाता है, तो प्रस्तुति की प्रत्येक छवि के लिए सबसे उपयुक्त संपीड़न एल्गोरिदम चुना जाएगा, जिससे उत्पन्न PDF दस्तावेज़ का आकार छोटा होगा। सर्वोत्तम छवि संपीड़न अनुपात चयन गणनात्मक रूप से महंगा है और अतिरिक्त RAM उपयोग करता है, और यह विकल्प डिफ़ॉल्ट रूप से Boolean.false है। |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | उत्पन्न PDF दस्तावेज़ के लिए वांछित अनुरूपता स्तर। पढ़ें/लिखें [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | यदि true हो तो प्रत्येक स्लाइड के चारों ओर काली फ्रेम बनाएं। पढ़ें/लिखें Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | निर्धारित करता है कि फ़ॉन्ट के सभी वर्ण एम्बेड किए जाने चाहिए या केवल उपयोग किया गया उपसमुच्चय। पढ़ें/लिखें Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | यदि true हो तो ASCII वर्ण 32-127 के लिये TrueType फ़ॉन्ट एम्बेड करें। 127 से बड़े कैरेक्टर कोड वाले फ़ॉन्ट हमेशा एम्बेड होते हैं। पढ़ें/लिखें Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | छवि का ट्रांसपेरेंट रंग प्राप्त करता है या सेट करता है। |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | यदि true हो तो प्रस्तुति से सभी OLE डेटा को उत्पन्न PDF में एम्बेडेड फ़ाइलों में बदलें। पढ़ें/लिखें Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | निर्यात किए गए दस्तावेज़ में Ink ऑब्जेक्ट्स की उपस्थिति को नियंत्रित करने वाले विकल्प प्रदान करता है। केवल-रीड [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | PDF दस्तावेज़ के भीतर JPEG छवियों की गुणवत्ता निर्धारित करने वाले मान को लौटाता है या सेट करता है। पढ़ें/लिखें Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | PDF दस्तावेज़ को सुरक्षित करने के लिये उपयोगकर्ता पासवर्ड सेट करना। पढ़ें/लिखें String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | निर्धारित करता है कि जब फ़ॉन्ट बोल्ड स्टाइलिंग का समर्थन नहीं करता है तो टेक्स्ट को बिटमैप के रूप में रास्टराइज़ करके PDF में सहेजा जाए। यह तरीका कुछ फ़ॉन्ट्स के लिए उत्पन्न PDF में टेक्स्ट की गुणवत्ता को बढ़ा सकता है। पढ़ें/लिखें Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | यदि true हो तो प्रस्तुति में उपयोग किए गए सभी मेटा फ़ाइलों को PNG छवियों में बदलें। पढ़ें/लिखें Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | निर्धारित करता है कि उत्पन्न दस्तावेज़ में छुपी हुई स्लाइडें शामिल होंगी या नहीं। डिफ़ॉल्ट `false` है। |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | प्रस्तुति निर्यात करते समय स्लाइडों को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | PDF दस्तावेज़ के भीतर छवियों के रिज़ॉल्यूशन को निर्धारित करने वाले मान को लौटाता है या सेट करता है। |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | दस्तावेज़ में सभी टेक्स्ट सामग्री के लिये उपयोग किए जाने वाले संपीड़न प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [`PdfTextCompression`](../pdftextcompression). |

### संबंधित देखें

* इंटरफ़ेस [ISaveOptions](../isaveoptions)
* नेमस्पेस [Aspose.Slides.Export](../../aspose.slides.export)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->