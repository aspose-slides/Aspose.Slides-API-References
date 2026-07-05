---
title: IPdfOptions
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: विकल्प प्रदान करता है जो नियंत्रित करते हैं कि एक प्रस्तुति को Pdf फ़ॉर्मेट में कैसे सहेजा जाता है।
type: docs
weight: 4000
url: /hi/aspose.slides.export/ipdfoptions/
---
## IPdfOptions इंटरफ़ेस

एक प्रस्तुति को Pdf फ़ॉर्मेट में सहेजने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।

```csharp
public interface IPdfOptions : ISaveOptions
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | एक समूह फ़्लैग्स शामिल करता है जो निर्दिष्ट करता है कि दस्तावेज़ को उपयोगकर्ता पहुंच के साथ खोलते समय कौन-से अभिगम अनुमति दी जानी चाहिए। देखें [`PdfAccessPermissions`](../pdfaccesspermissions)। |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | फ़ॉन्ट फ़ैमिलियों के उपयोगकर्ता-परिभाषित नामों की एक सरणी लौटाता या सेट करता है जिन्हें Aspose.Slides सामान्य मानना चाहिए। पढ़ने/लिखने योग्य String[]। |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | यदि `true` हो तो निर्दिष्ट पारदर्शी रंग को छवि पर लागू करता है। |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | ISaveOptions इंटरफ़ेस लौटाता है। केवल-पढ़ने योग्य [`ISaveOptions`](../isaveoptions)। |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | यह दर्शाता है कि क्या प्रत्येक छवि के लिए सबसे प्रभावी संपीड़न (डिफ़ॉल्ट के बजाय) स्वचालित रूप से चयनित होना चाहिए। यदि इसे Boolean.true पर सेट किया जाता है, तो प्रस्तुति में प्रत्येक छवि के लिए सबसे उपयुक्त संपीड़न एल्गोरिदम चुना जाएगा, जिससे उत्पन्न PDF दस्तावेज़ का आकार छोटा रहेगा। सर्वोत्तम छवि संपीड़न अनुपात का चयन कम्प्यूटेशनली खर्चीला है और अतिरिक्त RAM लेता है, और यह विकल्प डिफ़ॉल्ट रूप से Boolean.false है। |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | जेनरेट किए गए PDF दस्तावेज़ के लिए वांछित अनुरूपता स्तर। पढ़ने/लिखने योग्य [`PdfCompliance`](../pdfcompliance)। |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | यदि true हो तो प्रत्येक स्लाइड के आसपास काली फ्रेम खींचें। पढ़ने/लिखने योग्य Boolean। |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | निर्धारित करता है कि फ़ॉन्ट के सभी अक्षर एम्बेड किए जाएँ या केवल उपयोग किए गए उपसमूह। पढ़ने/लिखने योग्य Boolean। |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | यदि true हो तो ASCII अक्षरों 32-127 के लिए TrueType फ़ॉन्ट एम्बेड करें। 127 से बड़े अक्षर कोड के फ़ॉन्ट हमेशा एम्बेड होते हैं। पढ़ने/लिखने योग्य Boolean। |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | छवि के पारदर्शी रंग को प्राप्त करता या सेट करता है। |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | यदि true हो तो प्रस्तुति से सभी OLE डेटा को उत्पन्न PDF में एम्बेडेड फ़ाइलों में परिवर्तित करें। पढ़ने/लिखने योग्य Boolean। |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | निर्यात किए गए दस्तावेज़ में इंक वस्तुओं के रूप को नियंत्रित करने वाले विकल्प प्रदान करता है। केवल-पढ़ने योग्य [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | PDF दस्तावेज़ के भीतर JPEG छवियों की गुणवत्ता निर्धारित करने वाला मान लौटाता या सेट करता है। पढ़ने/लिखने योग्य Byte। |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | PDF दस्तावेज़ की सुरक्षा के लिए उपयोगकर्ता पासवर्ड सेट करना। पढ़ने/लिखने योग्य String। |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | यह दर्शाता है कि क्या फ़ॉन्ट में बोल्ड शैली समर्थन नहीं होने पर पाठ को बिटमैप के रूप में रास्टराइज़ कर PDF में सहेजा जाना चाहिए। यह दृष्टिकोण कुछ फ़ॉन्ट्स के लिए उत्पन्न PDF में पाठ की गुणवत्ता बढ़ा सकता है। पढ़ने/लिखने योग्य Boolean। |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | यदि true हो तो प्रस्तुति में उपयोग किए गए सभी मेटा फ़ाइलों को PNG छवियों में परिवर्तित करें। पढ़ने/लिखने योग्य Boolean। |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | निर्धारित करता है कि जेनरेट किए गए दस्तावेज़ में छिपी स्लाइडें शामिल होनी चाहिए या नहीं। डिफ़ॉल्ट `false` है। |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | प्रस्तुति निर्यात करते समय स्लाइडों को पृष्ठ पर जिस मोड में रखा जाता है, उसे प्राप्त करता या सेट करता है [`ISlidesLayoutOptions`](../islideslayoutoptions)। |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | PDF दस्तावेज़ के भीतर छवियों की रेज़ोल्यूशन निर्धारित करने वाला मान लौटाता या सेट करता है। |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | दस्तावेज़ में सभी पाठ्य सामग्री के लिए उपयोग किए जाने वाले संपीड़न प्रकार को निर्दिष्ट करता है। पढ़ने/लिखने योग्य [`PdfTextCompression`](../pdftextcompression)। |

### देखें

* इंटरफ़ेस [ISaveOptions](../isaveoptions)
* नामस्थान [Aspose.Slides.Export](../../aspose.slides.export)
* असेम्बली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->