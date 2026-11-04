---
title: SVGOptions
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: एक SVG विकल्प का प्रतिनिधित्व करता है।
type: docs
weight: 4450
url: /hi/aspose.slides.export/svgoptions/
---
## SVGOptions क्लास

एक SVG विकल्प का प्रतिनिधित्व करता है।

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | Initializes a new instance of the SVGOptions class. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Initializes a new instance of the SVGOptions class specifying the link embedding controller object. |

## गुण

| नाम | विवरण |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | डिफ़ॉल्ट सेटिंग्स लौटाता है। केवल-पढ़ने योग्य [`SVGOptions`](../svgoptions)। |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | सबसे सरल और सबसे छोटे SVG फ़ाइल उत्पन्न करने के लिए सेटिंग्स लौटाता है। केवल-पढ़ने योग्य [`SVGOptions`](../svgoptions)। |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | सबसे सटीक SVG फ़ाइल उत्पन्न करने के लिए सेटिंग्स लौटाता है। केवल-पढ़ने योग्य [`SVGOptions`](../svgoptions)। |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किया जाने वाला फ़ॉन्ट लौटाता या सेट करता है। पढ़ने/लिखने योग्य String। |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | एक बूलियन फ़्लैग दर्शाता है कि क्रॉप किए गए भाग दस्तावेज़ का हिस्सा बने रहें। यदि true है तो क्रॉप किए गए भाग हटा दिए जाएंगे, यदि false है तो वे दस्तावेज़ में क्रमबद्ध किए जाएंगे (जिससे फ़ाइल बड़ा हो सकती है)। |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | निर्धारित करता है कि SVG में 3D टेक्स्ट अक्षम है या नहीं। पढ़ने/लिखने योग्य Boolean। |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | एक मान प्राप्त करता या सेट करता है जो यह दर्शाता है कि टेक्स्ट को लिगेचर का उपयोग किए बिना रेंडर किया जाए। जब `true` पर सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर अक्षम हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी `false` पर सेट होती है। |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | FromCornerX और FromCenter ग्रेडिएंट्स के विभाजन को अक्षम करता है। पढ़ने/लिखने योग्य Boolean। |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1 में मार्कर के लिये इनसेट परिभाषित करने की क्षमता नहीं है। Aspose.Slides SVG लेखन इंजन इस समस्या के लिये एक वैकल्पिक उपाय प्रदान करता है: यह तीर वाले रेखा के अंत को क्रॉप करता है, ताकि रेखा मार्कर के ऊपर न आए। यह विकल्प इस व्यवहार को बंद कर देता है। पढ़ने/लिखने योग्य Boolean। |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | बाहरी रूप से लोड किए गए फ़ॉन्ट्स को संभालने का तरीका निर्धारित करता है। पढ़ने/लिखने योग्य [`SvgExternalFontsHandling`](../svgexternalfontshandling)। |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | ग्रेडिएंट की दृश्य शैली लौटाता या सेट करता है। पढ़ने/लिखने योग्य [`GradientStyle`](../../aspose.slides/gradientstyle)। |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | एक्सपोर्ट किए गए दस्तावेज़ में Ink वस्तुओं की दिखावट को नियंत्रित करने वाले विकल्प प्रदान करता है। केवल-पढ़ने योग्य [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | JPEG एन्कोडिंग गुणवत्ता निर्धारित करता है। पढ़ने/लिखने योग्य Int32। |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | मेटा-फ़ाइल रास्टराइज़ेशन के लिये न्यूनतम रिज़ॉल्यूशन सीमा लौटाता या सेट करता है। पढ़ने/लिखने योग्य Int32। |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | चित्र संपीड़न स्तर को दर्शाता है |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | प्रति शुल्क प्रगति अद्यतन को प्रतिशत में सहेजने के लिये एक कॉलबैक वस्तु को दर्शाता है। देखें [`IProgressCallback`](../../aspose.slides/iprogresscallback)। |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | एक कॉलबैक इंटरफ़ेस लौटाता और सेट करता है जो उपयोगकर्ता को आकार रूपांतरण नियंत्रित करने की अनुमति देता है। पढ़ने/लिखने योग्य [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller)। |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | प्रस्तुति सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक को छोड़ना है या नहीं को निर्दिष्ट करता है। पढ़ने/लिखने योग्य Boolean। डिफ़ॉल्ट मान **false** है। |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | रेंडरिंग के समय आकार के निर्दिष्ट घुमाव को लागू करना है या नहीं निर्धारित करता है। पढ़ने/लिखने योग्य Boolean। डिफ़ॉल्ट मान true है। |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | रेंडरिंग क्षेत्र में टेक्स्ट फ्रेम को शामिल करना है या नहीं निर्धारित करता है। पढ़ने/लिखने योग्य Boolean। डिफ़ॉल्ट मान false है। |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | स्लाइड पर टेक्स्ट को ग्राफ़िक के रूप में सहेजना है या नहीं निर्धारित करता है। पढ़ने/लिखने योग्य Boolean। |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | एक वस्तु लौटाता या सेट करता है जो चेतावनियाँ प्राप्त करती है और तय करती है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द हो जाएगी। पढ़ने/लिखने योग्य [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback)। |

### देखें

* क्लास [SaveOptions](../saveoptions)
* इंटरफ़ेस [ISVGOptions](../isvgoptions)
* नामस्थान [Aspose.Slides.Export](../../aspose.slides.export)
* असेंब्ली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->