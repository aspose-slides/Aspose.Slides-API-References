---
title: IPictureFillFormat
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: एक चित्र भराव शैली का प्रतिनिधित्व करता है।
type: docs
weight: 6650
url: /hi/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat इंटरफ़ेस

एक चित्र भराव शैली का प्रतिनिधित्व करता है।

```csharp
public interface IPictureFillFormat : IFillParamSource
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | बेस IFillParamSource इंटरफ़ेस प्राप्त करने की अनुमति देता है। केवल पढ़ने योग्य [`IFillParamSource`](../ifillparamsource)। |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | छवि की वास्तविक ऊँचाई के प्रतिशत को लौटाता या सेट करता है जो चित्र के नीचे से काटे गए हैं। पढ़ें/लिखें Single। |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | छवि की वास्तविक चौड़ाई के प्रतिशत को लौटाता या सेट करता है जो चित्र के बाएँ से काटे गए हैं। पढ़ें/लिखें Single। |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | छवि की वास्तविक चौड़ाई के प्रतिशत को लौटाता या सेट करता है जो चित्र के दाएँ से काटे गए हैं। पढ़ें/लिखें Single। |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | छवि की वास्तविक ऊँचाई के प्रतिशत को लौटाता या सेट करता है जो चित्र के ऊपर से काटे गए हैं। पढ़ें/लिखें Single। |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | एक चित्र को भरने के लिए उपयोग किए जाने वाले DPI को लौटाता या सेट करता है। पढ़ें/लिखें Int32। |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | चित्र को लौटाता है। केवल पढ़ने योग्य [`ISlidesPicture`](../islidespicture)। |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | चित्र भराव मोड को लौटाता या सेट करता है। पढ़ें/लिखें [`PictureFillMode`](../picturefillmode)। |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | भरण आयत के निचले किनारे को सेट या लौटाता है, जो आकार की बाउंडिंग बॉक्स के निचले किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित होता है। एक सकारात्मक प्रतिशत इनसिट दर्शाता है, जबकि नकारात्मक प्रतिशत आउटसेट दर्शाता है। पढ़ें/लिखें Single। |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | भरण आयत के बाएँ किनारे को सेट या लौटाता है, जो आकार की बाउंडिंग बॉक्स के बाएँ किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित होता है। एक सकारात्मक प्रतिशत इनसिट दर्शाता है, जबकि नकारात्मक प्रतिशत आउटसेट दर्शाता है। पढ़ें/लिखें Single। |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | भरण आयत के दाएँ किनारे को सेट या लौटाता है, जो आकार की बाउंडिंग बॉक्स के दाएँ किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित होता है। एक सकारात्मक प्रतिशत इनसिट दर्शाता है, जबकि नकारात्मक प्रतिशत आउटसेट दर्शाता है। पढ़ें/लिखें Single। |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | भरण आयत के ऊपर किनारे को सेट या लौटाता है, जो आकार की बाउंडिंग बॉक्स के ऊपर किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित होता है। एक सकारात्मक प्रतिशत इनसिट दर्शाता है, जबकि नकारात्मक प्रतिशत आउटसेट दर्शाता है। पढ़ें/लिखें Single। |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | टेक्सचर को आकार के भीतर कैसे संरेखित किया जाता है, इसे सेट या लौटाता है। यह सेटिंग टेक्सचर पैटर्न की शुरूआती बिंदु और इसे आकार पर कैसे दोहराया जाता है, नियंत्रित करती है। पढ़ें/लिखें [`RectangleAlignment`](../rectanglealignment)। |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | टेक्सचर टाइल को उसके क्षैतिज, लंबवत या दोनों अक्षों के आसपास उलटता है। पढ़ें/लिखें [`TileFlip`](../tileflip)। |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | आकार की मूल बिंदु से टेक्सचर का क्षैतिज ऑफ़सेट पॉइंट्स में सेट या लौटाता है। एक सकारात्मक मान टेक्सचर को दाएँ ले जाता है, जबकि नकारात्मक मान बाएँ ले जाता है। पढ़ें/लिखें Single। |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | आकार की मूल बिंदु से टेक्सचर का लंबवत ऑफ़सेट पॉइंट्स में सेट या लौटाता है। एक सकारात्मक मान टेक्सचर को नीचे ले जाता है, जबकि नकारात्मक मान ऊपर ले जाता है। पढ़ें/लिखें Single। |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | टेक्सचर भराव के लिए क्षैतिज स्केल को प्रतिशत के रूप में सेट या लौटाता है। पढ़ें/लिखें Single। |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | टेक्सचर भराव के लिए लंबवत स्केल को प्रतिशत के रूप में सेट या लौटाता है। पढ़ें/लिखें Single। |

## विधाएँ

| नाम | विवरण |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | आकार के आकार और निर्दिष्ट रिज़ॉल्यूशन के आधार पर छवि का आकार घटाकर उसे संकुचित करता है। वैकल्पिक रूप से, यह कटे हुए क्षेत्रों को भी हटा देता है। |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | आकार के आकार और निर्दिष्ट रिज़ॉल्यूशन के आधार पर छवि का आकार घटाकर उसे संकुचित करता है। वैकल्पिक रूप से, यह कटे हुए क्षेत्रों को भी हटा देता है। |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | भराव चित्र के कटे हुए क्षेत्रों को हटाता है। |

### देखें

* इंटरफ़ेस [IFillParamSource](../ifillparamsource)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->