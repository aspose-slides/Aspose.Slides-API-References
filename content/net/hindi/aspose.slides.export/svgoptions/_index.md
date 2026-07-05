---
title: SVGOptions
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक SVG विकल्प का प्रतिनिधित्व करता है।
type: docs
weight: 4430
url: /hi/aspose.slides.export/svgoptions/
---
## SVGOptions कक्षा

एक SVG विकल्प का प्रतिनिधित्व करता है।

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | SVGOptions कक्षा का नया उदाहरण प्रारंभ करता है। |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | SVGOptions कक्षा का नया उदाहरण प्रारंभ करता है, जिसमें लिंक एम्बेड कंट्रोलर ऑब्जेक्ट निर्दिष्ट किया गया है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | डिफ़ॉल्ट सेटिंग्स लौटाता है। केवल-पढ़ने योग्य [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | सबसे आसान और सबसे छोटे SVG फ़ाइल निर्माण के लिए सेटिंग्स लौटाता है। केवल-पढ़ने योग्य [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | सबसे सटीक SVG फ़ाइल निर्माण के लिए सेटिंग्स लौटाता है। केवल-पढ़ने योग्य [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | फ़ॉन्ट लौटाता है या सेट करता है जिसका उपयोग स्रोत फ़ॉन्ट न मिलने पर किया जाता है। पढ़ने/लिखने योग्य String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | एक बूलियन फ़्लैग दर्शाता है कि कटे हुए भाग दस्तावेज़ का हिस्सा बने रहें। यदि true हो तो कटे हुए भाग हटा दिए जाएंगे, यदि false हो तो वे दस्तावेज़ में क्रमबद्ध किए जाएँगे (जो संभवतः फ़ाइल को बड़ा बना सकता है)। |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | निर्धारित करता है कि SVG में 3D टेक्स्ट अक्षम है या नहीं। पढ़ने/लिखने योग्य Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि टेक्स्ट लिगेचर का उपयोग किए बिना रेंडर किया जाए। जब `true` सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर अक्षम हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी `false` पर सेट होती है। |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | FromCornerX और FromCenter ग्रेडिएंट्स को विभाजित करने को अक्षम करता है। पढ़ने/लिखने योग्य Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1 में मार्कर्स के लिए इनसेट्स को परिभाषित करने की क्षमता नहीं है। Aspose.Slides SVG लेखन इंजन इस समस्या के लिए एक उपाय प्रदान करता है: यह तीर वाले लाइन के अंत को क्रॉप कर देता है, ताकि लाइन मार्कर्स के ऊपर न आए। यह विकल्प इस व्यवहार को बंद कर देता है। पढ़ने/लिखने योग्य Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | बाहरी लोड किए गए फ़ॉन्ट्स को हैंडल करने का तरीका निर्धारित करता है। पढ़ने/लिखने योग्य [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | ग्रेडिएंट की दृश्य शैली लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | निर्यात किए गए दस्तावेज़ में Ink ऑब्जेक्ट्स की दिखावट को नियंत्रित करने वाले विकल्प प्रदान करता है। केवल-पढ़ने योग्य [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | JPEG एन्कोडिंग गुणवत्ता को निर्धारित करता है। पढ़ने/लिखने योग्य Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | मेटाफाइल रास्टराइज़ेशन के लिए निचली रिज़ॉल्यूशन सीमा को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | चित्र संपीड़न स्तर का प्रतिनिधित्व करता है |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | प्रगति अपडेट को प्रतिशत में सहेजने के लिए एक कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है। देखें [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | एक कॉलबैक इंटरफ़ेस लौटाता और सेट करता है जो उपयोगकर्ता को आकार रूपांतरण नियंत्रित करने की अनुमति देता है। पढ़ने/लिखने योग्य [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | प्रेजेंटेशन सहेजते समय JavaScript कॉल वाले हाइपरलिंक को छोड़ना है या नहीं, इसे निर्दिष्ट करता है। पढ़ने/लिखने योग्य Boolean. डिफ़ॉल्ट मान **false** है। |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | रेंडरिंग के समय आकार को निर्दिष्ट घुमाव करने है या नहीं, इसे निर्धारित करता है। पढ़ने/लिखने योग्य Boolean. डिफ़ॉल्ट मान true है। |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | टेक्स्ट फ्रेम को रेंडरिंग क्षेत्र में शामिल करना है या नहीं, इसे निर्धारित करता है। पढ़ने/लिखने योग्य Boolean. डिफ़ॉल्ट मान false है। |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | स्लाइड पर टेक्स्ट को ग्राफ़िक्स के रूप में सहेजना है या नहीं, इसे निर्धारित करता है। पढ़ने/लिखने योग्य Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | एक ऑब्जेक्ट लौटाता या सेट करता है जो चेतावनियों को प्राप्त करता है और निर्णय लेता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द कर दी जाएगी। पढ़ने/लिखने योग्य [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### संबंधित देखें

* कक्षा [SaveOptions](../saveoptions)
* इंटरफ़ेस [ISVGOptions](../isvgoptions)
* नेमस्पेस [Aspose.Slides.Export](../../aspose.slides.export)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->