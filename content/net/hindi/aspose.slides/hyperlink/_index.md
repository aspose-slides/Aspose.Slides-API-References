---
title: Hyperlink
second_title: Aspose.Sildes for .NET API संदर्भ
description: हाइपरलिंक का प्रतिनिधित्व करता है।
type: docs
weight: 5120
url: /hi/aspose.slides/hyperlink/
---
## Hyperlink क्लास

हाइपरलिंक को दर्शाता है।

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | एक हाइपरलिंक का उदाहरण बनाता है जो विशिष्ट स्लाइड की ओर संकेत करता है। नोट: बनाया गया हाइपरलिंक समान प्रस्तुति के किसी वस्तु को सौंपा जाना चाहिए, अन्यथा लिंक NoAction के रूप में सहेजा जाएगा। |
| [Hyperlink](hyperlink#constructor_2)(string) | एक हाइपरलिंक का उदाहरण बनाता है। |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | एक हाइपरलिंक का उदाहरण बनाता है, जिसमें स्रोत के रूप में अन्य हाइपरलिंक का उपयोग किया जाता है, और द्वितीयक गुणों को ओवरराइड किया जाता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | एक हाइपरलिंक लौटाता है जो शो को समाप्त करता है। केवल पढ़ने योग्य [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | प्रस्तुति की पहली स्लाइड की ओर एक हाइपरलिंक लौटाता है। केवल पढ़ने योग्य [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | प्रस्तुति की अंतिम स्लाइड की ओर एक हाइपरलिंक लौटाता है। केवल पढ़ने योग्य [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | अंतिम देखी गई स्लाइड की ओर एक हाइपरलिंक लौटाता है। केवल पढ़ने योग्य [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | एक विशेष "play mediafile" हाइपरलिंक लौटाता है। AudioFrame और VideoFrame में उपयोग किया जाता है। केवल पढ़ने योग्य [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | अगली स्लाइड की ओर एक हाइपरलिंक लौटाता है। केवल पढ़ने योग्य [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | एक विशेष "do nothing" हाइपरलिंक लौटाता है। केवल पढ़ने योग्य [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | पिछली स्लाइड की ओर एक हाइपरलिंक लौटाता है। केवल पढ़ने योग्य [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | हाइपरलिंक की क्रिया प्रकार लौटाता है। केवल पढ़ने योग्य [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | बेस IPresentationComponent इंटरफ़ेस प्राप्त करने की अनुमति देता है। केवल पढ़ने योग्य [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | हाइपरलिंक रंग के स्रोत को दर्शाता है - या तो शैली या भाग स्वरूप। पढ़ने/लिखने योग्य [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | बाहरी URL निर्दिष्ट करता है। केवल पढ़ने योग्य String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | इस भाग के लिए सेट किया गया हाइपरलिंक दर्शाता है, भाग की वास्तविक सामग्री की परवाह किए बिना। PowerPoint लिंक और उनके संबंधित भाग के पाठ के लिए विशिष्ट व्यवहार करता है। यह एक मान्य URL के रूप में हाइपरलिंक के लिए पाठ बनाने की अनुमति देता है, जो लिंक के वास्तविक पते से अलग होता है। इस स्थिति में, जब आप संपादन विंडो में लिंक देखते हैं, तो यह पाठ भाग के साथ मेल खाने के लिए बदल दिया जाता है। यह प्रॉपर्टी हाइपरलिंक का मूल मान दर्शाती है। |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | निर्धारित करता है कि हाइपरलिंक पर क्लिक करने पर उसे हाइलाइट किया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | निर्धारित करता है कि पैरेंट हाइपरलिंक का लक्ष्य बुलाए जाने पर देखी गई हाइपरलिंक की सूची में जोड़ा जाना चाहिए या नहीं। पढ़ने/लिखने योग्य Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | हाइपरलिंक की चल रही ध्वनि को दर्शाता है। पढ़ने/लिखने योग्य [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | निर्धारित करता है कि हाइपरलिंक क्लिक पर ध्वनि को रोकना चाहिए या नहीं। पढ़ने/लिखने योग्य Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | पैरेंट HTML फ्रेमसेट में लक्ष्य के लिए फ्रेम लौटाता है, यदि मौजूद हो। पढ़ने/लिखने योग्य String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | यदि हाइपरलिंक विशिष्ट स्लाइड को लक्ष्य बनाता है तो यह स्लाइड लौटाता है। केवल पढ़ने योग्य [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | एक स्ट्रिंग लौटाता है जो उपयोगकर्ता इंटरफ़ेस में पैरेंट हाइपरलिंक से संबंधित दर्शाई जा सकती है। पढ़ने/लिखने योग्य String. |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | निर्धारित करता है कि दो हाइपरलिंक इंस्टेंस बराबर हैं या नहीं। |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | निर्धारित करता है कि दो हाइपरलिंक इंस्टेंस बराबर हैं या नहीं। |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | विशिष्ट प्रकार के लिए एक हैश फ़ंक्शन के रूप में कार्य करता है, जो हैशिंग एल्गोरिदम और डेटा संरचनाओं जैसे हैश टेबल में उपयोग के योग्य है। |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | दो हाइपरलिंक की समानता का परीक्षण करता है। |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | दो हाइपरलिंक की असमानता का परीक्षण करता है। |

### संबंधित देखें

* क्लास [PVIObject](../pviobject)
* इंटरफ़ेस [IHyperlink](../ihyperlink)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->