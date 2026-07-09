---
title: SVGOptions
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: एक SVG विकल्प का प्रतिनिधित्व करता है।
type: docs
weight: 4430
url: /hi/aspose.slides.export/svgoptions/
---
## SVGOptions क्लास

एक SVG विकल्प को दर्शाता है।

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## निर्माताएँ

| नाम | विवरण |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | SVGOptions क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | SVGOptions क्लास का एक नया उदाहरण प्रारंभ करता है जो लिंक एम्बेड कंट्रोलर ऑब्जेक्ट को निर्दिष्ट करता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | डिफ़ॉल्ट सेटिंग्स लौटाता है। केवल-पढ़ने योग्य [`SVGOptions`](../svgoptions)। |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | सबसे सरल और सबसे छोटे SVG फ़ाइल निर्माण के लिए सेटिंग्स लौटाता है। केवल-पढ़ने योग्य [`SVGOptions`](../svgoptions)। |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | सबसे सटीक SVG फ़ाइल निर्माण के लिए सेटिंग्स लौटाता है। केवल-पढ़ने योग्य [`SVGOptions`](../svgoptions)। |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले फ़ॉन्ट को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य स्ट्रिंग। |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | एक बूलियन फ़्लैग दर्शाता है कि काटे गए भाग दस्तावेज़ का हिस्सा रहेंगे। यदि सत्य है तो काटे गए भाग हटा दिए जाएंगे, यदि असत्य है तो वे दस्तावेज़ में क्रमबद्ध किए जाएंगे (जिससे फ़ाइल आकार बड़ा हो सकता है)। |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | निर्धारित करता है कि SVG में 3D टेक्स्ट अक्षम है या नहीं। पढ़ने/लिखने योग्य बूलियन। |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | एक मान प्राप्त करता या सेट करता है जो दर्शाता है कि टेक्स्ट को लिगेचर के बिना रेंडर किया जाए या नहीं। जब `true` पर सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर अक्षम हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी `false` पर सेट है। |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | FromCornerX और FromCenter ग्रेडिएंट्स के विभाजन को अक्षम करता है। पढ़ने/लिखने योग्य बूलियन। |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1 में मार्कर्स के लिए इनसेट परिभाषित करने की क्षमता नहीं है। Aspose.Slides SVG राइटिंग इंजन इस समस्या का समाधान करता है: यह तीर वाले लाइन के अंत को काटता है, जिससे लाइन मार्कर्स के साथ ओवरलैप नहीं करता। यह विकल्प इस व्यवहार को बंद करता है। पढ़ने/लिखने योग्य बूलियन। |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | बाहरी रूप से लोड किए गए फ़ॉन्ट्स को संभालने के तरीके को निर्धारित करता है। पढ़ने/लिखने योग्य [`SvgExternalFontsHandling`](../svgexternalfontshandling)। |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | ग्रेडिएंट की दृश्य शैली को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`GradientStyle`](../../aspose.slides/gradientstyle)। |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | निर्यात किए गए दस्तावेज़ में Ink ऑब्जेक्ट्स की दिखावट को नियंत्रित करने वाले विकल्प प्रदान करता है। केवल-पढ़ने योग्य [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | JPEG एन्कोडिंग गुणवत्ता निर्धारित करता है। पढ़ने/लिखने योग्य Int32। |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | मेटाफाइल रास्टराइज़ेशन के लिए निचले रिज़ॉल्यूशन सीमा को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य Int32। |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | चित्रों का संपीड़न स्तर दर्शाता है। |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | प्रगति अपडेट को प्रतिशत में सहेजने के लिए एक कॉलबैक ऑब्जेक्ट दर्शाता है। देखें [`IProgressCallback`](../../aspose.slides/iprogresscallback)। |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | एक कॉलबैक इंटरफ़ेस लौटाता और सेट करता है जो उपयोगकर्ता को शेप रूपांतरण नियंत्रित करने की अनुमति देता है। पढ़ने/लिखने योग्य [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller)। |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | प्रेजेंटेशन सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक को छोड़ना है या नहीं यह निर्दिष्ट करता है। पढ़ने/लिखने योग्य बूलियन। डिफ़ॉल्ट मान **false** है। |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | रेंडरिंग के दौरान शेप के निर्दिष्ट घूर्णन को लागू करना है या नहीं निर्धारित करता है। पढ़ने/लिखने योग्य बूलियन। डिफ़ॉल्ट मान true है। |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | निर्धारित करता है कि टेक्स्ट फ्रेम रेंडरिंग क्षेत्र में शामिल किया जाएगा या नहीं। पढ़ने/लिखने योग्य बूलियन। डिफ़ॉल्ट मान false है। |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | निर्धारित करता है कि स्लाइड पर टेक्स्ट को ग्राफ़िक्स के रूप में सहेजा जाएगा या नहीं। पढ़ने/लिखने योग्य बूलियन। |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | एक ऑब्जेक्ट लौटाता या सेट करता है जो चेतावनियां प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द की जाएगी। पढ़ने/लिखने योग्य [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback)। |

### देखें

* क्लास [SaveOptions](../saveoptions)
* इंटरफ़ेस [ISVGOptions](../isvgoptions)
* नेमस्पेस [Aspose.Slides.Export](../../aspose.slides.export)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->