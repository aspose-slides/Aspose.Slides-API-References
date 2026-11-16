---
title: IPictureFillFormat
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक चित्र भराव शैली का प्रतिनिधित्व करता है।
type: docs
weight: 6670
url: /hi/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat interface

एक चित्र भराव शैली का प्रतिनिधित्व करता है।

```csharp
public interface IPictureFillFormat : IFillParamSource
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | आधार IFillParamSource इंटरफ़ेस को प्राप्त करने की अनुमति देता है। केवल-पढ़ने योग्य [`IFillParamSource`](../ifillparamsource)। |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | चित्र के नीचे से काटी गई वास्तविक छवि ऊँचाई के प्रतिशत संख्या को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य Single। |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | चित्र के बाएँ से काटी गई वास्तविक छवि चौड़ाई के प्रतिशत संख्या को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य Single। |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | चित्र के दाएँ से काटी गई वास्तविक छवि चौड़ाई के प्रतिशत संख्या को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य Single। |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | चित्र के ऊपर से काटी गई वास्तविक छवि ऊँचाई के प्रतिशत संख्या को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य Single। |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | चित्र भरने के लिए प्रयुक्त dpi को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य Int32। |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | चित्र लौटाता है। केवल-पढ़ने योग्य [`ISlidesPicture`](../islidespicture)। |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | चित्र भराव मोड को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`PictureFillMode`](../picturefillmode)। |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | नीचे की किनारा को प्रतिशत ऑफ़सेट द्वारा परिभाषित भराव आयत का नीचे का किनारा लौटाता है या सेट करता है। सकारात्मक प्रतिशत इन्सेट को दर्शाता है, जबकि नकारात्मक प्रतिशत आउटसेट को। पढ़ने/लिखने योग्य Single। |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | बाएँ किनारा को प्रतिशत ऑफ़सेट द्वारा परिभाषित भराव आयत का बाएँ किनारा लौटाता है या सेट करता है। सकारात्मक प्रतिशत इन्सेट को दर्शाता है, जबकि नकारात्मक प्रतिशत आउटसेट को। पढ़ने/लिखने योग्य Single। |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | दाएँ किनारा को प्रतिशत ऑफ़सेट द्वारा परिभाषित भराव आयत का दाएँ किनारा लौटाता है या सेट करता है। सकारात्मक प्रतिशत इन्सेट को दर्शाता है, जबकि नकारात्मक प्रतिशत आउटसेट को। पढ़ने/लिखने योग्य Single। |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | ऊपर का किनारा को प्रतिशत ऑफ़सेट द्वारा परिभाषित भराव आयत का ऊपर का किनारा लौटाता है या सेट करता है। सकारात्मक प्रतिशत इन्सेट को दर्शाता है, जबकि नकारात्मक प्रतिशत आउटसेट को। पढ़ने/लिखने योग्य Single। |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | टेक्सचर को आकार के भीतर कैसे संरेखित किया जाता है, यह निर्धारित करता है। यह सेटिंग टेक्सचर पैटर्न की प्रारंभिक बिंदु और आकार में दोहराव को नियंत्रित करती है। पढ़ने/लिखने योग्य [`RectangleAlignment`](../rectanglealignment)। |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | टेक्सचर टाइल को क्षैतिज, लंबवत या दोनों अक्षों के चारों ओर उलटता है। पढ़ने/लिखने योग्य [`TileFlip`](../tileflip)। |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | टेक्सचर का क्षैतिज ऑफ़सेट बिंदुओं में लौटाता है या सेट करता है। सकारात्मक मान टेक्सचर को दाएँ ले जाता है, जबकि नकारात्मक मान बाएँ। पढ़ने/लिखने योग्य Single। |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | टेक्सचर का लंबवत ऑफ़सेट बिंदुओं में लौटाता है या सेट करता है। सकारात्मक मान टेक्सचर को नीचे ले जाता है, जबकि नकारात्मक मान ऊपर। पढ़ने/लिखने योग्य Single। |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | टेक्सचर भराव के लिए क्षैतिज स्केल को प्रतिशत के रूप में लौटाता है या सेट करता है। पढ़ने/लिखने योग्य Single। |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | टेक्सचर भराव के लिए लंबवत स्केल को प्रतिशत के रूप में लौटाता है या सेट करता है। पढ़ने/लिखने योग्य Single। |

## विधियां

| नाम | विवरण |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | आकार और निर्दिष्ट रिज़ॉल्यूशन के आधार पर आकार के आकार को घटाकर छवि को संपीड़ित करता है। वैकल्पिक रूप से, यह काटे गए क्षेत्रों को भी हटाता है। |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | आकार और निर्दिष्ट रिज़ॉल्यूशन के आधार पर आकार के आकार को घटाकर छवि को संपीड़ित करता है। वैकल्पिक रूप से, यह काटे गए क्षेत्रों को भी हटाता है। |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | भराव चित्र के काटे गए क्षेत्रों को हटाता है। |

### देखें

* इंटरफ़ेस [IFillParamSource](../ifillparamsource)
* नामस्थल [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->