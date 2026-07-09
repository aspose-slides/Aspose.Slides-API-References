---
title: IPictureFillFormat
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक चित्र भराव शैली का प्रतिनिधित्व करता है।
type: docs
weight: 6650
url: /hi/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat इंटरफ़ेस

Represents a picture fill style.

```csharp
public interface IPictureFillFormat : IFillParamSource
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | IFillParamSource बेस इंटरफ़ेस को प्राप्त करने की अनुमति देता है। केवल-पढ़ने योग्य [`IFillParamSource`](../ifillparamsource). |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | चित्र की नीचे से वास्तविक छवि ऊँचाई के प्रतिशत को क्रॉप करने के प्रतिशत को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Single. |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | चित्र के बाएँ से वास्तविक छवि चौड़ाई के प्रतिशत को क्रॉप करने के प्रतिशत को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Single. |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | चित्र के दाएँ से वास्तविक छवि चौड़ाई के प्रतिशत को क्रॉप करने के प्रतिशत को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Single. |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | चित्र के ऊपर से वास्तविक छवि ऊँचाई के प्रतिशत को क्रॉप करने के प्रतिशत को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Single. |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | चित्र को भरने के लिए उपयोग किए जाने वाले DPI को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Int32. |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | चित्र को प्राप्त करता है। केवल-पढ़ने योग्य [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | चित्र भरने के मोड को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | भराव आयत के निचले किनारे को परिभाषित करता है जो आकार के बाउंडिंग बॉक्स के नीचे किनारे से प्रतिशत ऑफसेट द्वारा निर्धारित होता है। सकारात्मक प्रतिशत एक इनसेट को निर्दिष्ट करता है, जबकि नकारात्मक प्रतिशत एक आउटसेट को निर्दिष्ट करता है। पढ़ने/लिखने योग्य Single. |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | भराव आयत के बाएँ किनारे को परिभाषित करता है जो आकार के बाउंडिंग बॉक्स के बाएँ किनारे से प्रतिशत ऑफसेट द्वारा निर्धारित होता है। सकारात्मक प्रतिशत एक इनसेट को निर्दिष्ट करता है, जबकि नकारात्मक प्रतिशत एक आउटसेट को निर्दिष्ट करता है। पढ़ने/लिखने योग्य Single. |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | भराव आयत के दाएँ किनारे को परिभाषित करता है जो आकार के बाउंडिंग बॉक्स के दाएँ किनारे से प्रतिशत ऑफसेट द्वारा निर्धारित होता है। सकारात्मक प्रतिशत एक इनसेट को निर्दिष्ट करता है, जबकि नकारात्मक प्रतिशत एक आउटसेट को निर्दिष्ट करता है। पढ़ने/लिखने योग्य Single. |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | भराव आयत के ऊपर किनारे को परिभाषित करता है जो आकार के बाउंडिंग बॉक्स के ऊपर किनारे से प्रतिशत ऑफसेट द्वारा निर्धारित होता है। सकारात्मक प्रतिशत एक इनसेट को निर्दिष्ट करता है, जबकि नकारात्मक प्रतिशत एक आउटसेट को निर्दिष्ट करता है। पढ़ने/लिखने योग्य Single. |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | यह निर्धारित करता है कि बनावट आकार के भीतर कैसे संरेखित होती है। यह सेटिंग बनावट पैटर्न का प्रारंभिक बिंदु और आकार के भीतर इसकी पुनरावृत्ति को नियंत्रित करती है। पढ़ने/लिखने योग्य [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | बनावट टाइल को उसके क्षैतिज, लंबवत या दोनों धुरी के आसपास उलटता है। पढ़ने/लिखने योग्य [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | बनावट को आकार के मूल बिंदु से प्वाइंट में क्षैतिज ऑफसेट को प्राप्त करता है या सेट करता है। सकारात्मक मान बनावट को दाईं ओर ले जाता है, जबकि नकारात्मक मान बाएँ ओर। पढ़ने/लिखने योग्य Single. |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | बनावट को आकार के मूल बिंदु से प्वाइंट में ऊर्ध्वाधर ऑफसेट को प्राप्त करता है या सेट करता है। सकारात्मक मान बनावट को नीचे ले जाता है, जबकि नकारात्मक मान ऊपर। पढ़ने/लिखने योग्य Single. |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | बनावट भराव के लिए क्षैतिज स्केल को प्रतिशत के रूप में प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Single. |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | बनावट भराव के लिए ऊर्ध्वाधर स्केल को प्रतिशत के रूप में प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Single. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | आकार के आकार और निर्दिष्ट रिज़ॉल्यूशन के आधार पर आकार को कम करके छवि को संकुचित करता है। वैकल्पिक रूप से, यह क्रॉप किए गए क्षेत्रों को भी हटाता है। |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | आकार के आकार और निर्दिष्ट रिज़ॉल्यूशन के आधार पर आकार को कम करके छवि को संकुचित करता है। वैकल्पिक रूप से, यह क्रॉप किए गए क्षेत्रों को भी हटाता है। |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | भराव चित्र के क्रॉप किए गए क्षेत्रों को हटाता है। |

### देखें

* इंटरफ़ेस [IFillParamSource](../ifillparamsource)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->