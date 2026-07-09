---
title: PictureFillFormat
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: एक चित्र भराव शैली का प्रतिनिधित्व करता है।
type: docs
weight: 9390
url: /hi/aspose.slides/picturefillformat/
---
## PictureFillFormat क्लास

एक चित्र भराव शैली को दर्शाता है।

```csharp
public sealed class PictureFillFormat : PVIObject, IPictureFillFormat
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | आधार IPresentationComponent इंटरफ़ेस को प्राप्त करने की अनुमति देता है। केवल-पढ़ने योग्य [`IPresentationComponent`](../ipresentationcomponent). |
| [CropBottom](../../aspose.slides/picturefillformat/cropbottom) { get; set; } | चित्र के नीचे से काटे गए वास्तविक इमेज की ऊँचाई के प्रतिशत संख्या को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य Single. |
| [CropLeft](../../aspose.slides/picturefillformat/cropleft) { get; set; } | चित्र के बाएँ किनारे से काटे गए वास्तविक इमेज की चौड़ाई के प्रतिशत संख्या को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य Single. |
| [CropRight](../../aspose.slides/picturefillformat/cropright) { get; set; } | चित्र के दाएँ किनारे से काटे गए वास्तविक इमेज की चौड़ाई के प्रतिशत संख्या को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य Single. |
| [CropTop](../../aspose.slides/picturefillformat/croptop) { get; set; } | चित्र के ऊपर से काटे गए वास्तविक इमेज की ऊँचाई के प्रतिशत संख्या को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य Single. |
| [Dpi](../../aspose.slides/picturefillformat/dpi) { get; set; } | चित्र को भरने के लिए उपयोग किए जाने वाले DPI को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य Int32. |
| [Picture](../../aspose.slides/picturefillformat/picture) { get; } | चित्र को लौटाता है। केवल-पढ़ने योग्य [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/picturefillformat/picturefillmode) { get; set; } | चित्र भराव मोड को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/picturefillformat/stretchoffsetbottom) { get; set; } | शेप की बाउंडिंग बॉक्स के नीचे के किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित भराव आयत के निचले किनारे को लौटाता है या सेट करता है। सकारात्मक प्रतिशत एक इनसेट को दर्शाता है, जबकि नकारात्मक प्रतिशत एक आउटसेट को दर्शाता है। पढ़ने/लिखने योग्य Single. |
| [StretchOffsetLeft](../../aspose.slides/picturefillformat/stretchoffsetleft) { get; set; } | शेप की बाउंडिंग बॉक्स के बाएँ किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित भराव आयत के बाएँ किनारे को लौटाता है या सेट करता है। सकारात्मक प्रतिशत एक इनसेट को दर्शाता है, जबकि नकारात्मक प्रतिशत एक आउटसेट को दर्शाता है। पढ़ने/लिखने योग्य Single. |
| [StretchOffsetRight](../../aspose.slides/picturefillformat/stretchoffsetright) { get; set; } | शेप की बाउंडिंग बॉक्स के दाएँ किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित भराव आयत के दाएँ किनारे को लौटाता है या सेट करता है। सकारात्मक प्रतिशत एक इनसेट को दर्शाता है, जबकि नकारात्मक प्रतिशत एक आउटसेट को दर्शाता है। पढ़ने/लिखने योग्य Single. |
| [StretchOffsetTop](../../aspose.slides/picturefillformat/stretchoffsettop) { get; set; } | शेप की बाउंडिंग बॉक्स के ऊपर के किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित भराव आयत के ऊपर किनारे को लौटाता है या सेट करता है। सकारात्मक प्रतिशत एक इनसेट को दर्शाता है, जबकि नकारात्मक प्रतिशत एक आउटसेट को दर्शाता है। पढ़ने/लिखने योग्य Single. |
| [TileAlignment](../../aspose.slides/picturefillformat/tilealignment) { get; set; } | टेक्सचर को शेप के भीतर कैसे संरेखित किया जाता है, इसे लौटाता है या सेट करता है। यह सेटिंग टेक्सचर पैटर्न का प्रारंभ बिंदु और वह शेप में कैसे दोहराया जाता है, नियंत्रित करती है। पढ़ने/लिखने योग्य [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/picturefillformat/tileflip) { get; set; } | टेक्सचर टाइल को इसके क्षैतिज, लंबवत या दोनों अक्षों के बारे में उल्टा करता है। पढ़ने/लिखने योग्य [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/picturefillformat/tileoffsetx) { get; set; } | शेप के मूल बिंदु से पॉइंट में टेक्सचर के क्षैतिज ऑफ़सेट को लौटाता है या सेट करता है। सकारात्मक मान टेक्सचर को दाईं ओर ले जाता है, जबकि नकारात्मक मान इसे बाईं ओर ले जाता है। पढ़ने/लिखने योग्य Single. |
| [TileOffsetY](../../aspose.slides/picturefillformat/tileoffsety) { get; set; } | शेप के मूल बिंदु से पॉइंट में टेक्सचर के लंबवत ऑफ़सेट को लौटाता है या सेट करता है। सकारात्मक मान टेक्सचर को नीचे ले जाता है, जबकि नकारात्मक मान इसे ऊपर ले जाता है। पढ़ने/लिखने योग्य Single. |
| [TileScaleX](../../aspose.slides/picturefillformat/tilescalex) { get; set; } | टेक्सचर भराव के क्षैतिज स्केल को प्रतिशत के रूप में लौटाता है या सेट करता है। पढ़ने/लिखने योग्य Single. |
| [TileScaleY](../../aspose.slides/picturefillformat/tilescaley) { get; set; } | टेक्सचर भराव के लंबवत स्केल को प्रतिशत के रूप में लौटाता है या सेट करता है। पढ़ने/लिखने योग्य Single. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage_1)(bool, float) | शेप आकार और निर्दिष्ट रेज़ोल्यूशन के आधार पर इमेज का आकार घटाकर उसे संकुचित करता है। वैकल्पिक रूप से, यह क्रॉप किए गए क्षेत्रों को भी हटा देता है। |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage)(bool, PicturesCompression) | शेप आकार और निर्दिष्ट रेज़ोल्यूशन के आधार पर इमेज का आकार घटाकर उसे संकुचित करता है। वैकल्पिक रूप से, यह क्रॉप किए गए क्षेत्रों को भी हटा देता है। |
| [DeletePictureCroppedAreas](../../aspose.slides/picturefillformat/deletepicturecroppedareas)() | भराव चित्र के क्रॉप किए गए क्षेत्रों को हटाता है। |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | निर्दिष्ट ऑब्जेक्ट के साथ तुलना करता है। |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | हेश कोड लौटाता है। |

### संबंधित देखें

* क्लास [PVIObject](../pviobject)
* इंटरफ़ेस [IPictureFillFormat](../ipicturefillformat)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->