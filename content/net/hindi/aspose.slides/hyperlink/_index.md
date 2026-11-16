---
title: Hyperlink
second_title: Aspose.Sildes for .NET API संदर्भ
description: हाइपरलिंक को दर्शाता है।
type: docs
weight: 5140
url: /hi/aspose.slides/hyperlink/
---
## Hyperlink वर्ग

Represents a hyperlink.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## निर्माता

| Name | Description |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | हाइपरलिंक का एक उदाहरण बनाता है जो विशिष्ट स्लाइड की ओर इशारा करता है। नोट: बनाया गया हाइपरलिंक उसी प्रस्तुति के किसी वस्तु को सौंपा जाना चाहिए, अन्यथा लिंक को NoAction के रूप में सहेजा जाएगा। |
| [Hyperlink](hyperlink#constructor_2)(string) | हाइपरलिंक का एक उदाहरण बनाता है। |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | एक अन्य हाइपरलिंक को स्रोत के रूप में उपयोग करके, द्वितीयक गुणों को अधिलेखित करते हुए, हाइपरलिंक का एक उदाहरण बनाता है। |

## गुण

| Name | Description |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | एक हाइपरलिंक लौटाता है जो शो को समाप्त करता है। केवल- पढ़ने योग्य [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | प्रस्तुति की पहली स्लाइड की ओर हाइपरलिंक लौटाता है। केवल- पढ़ने योग्य [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | प्रस्तुति की अंतिम स्लाइड की ओर हाइपरलिंक लौटाता है। केवल- पढ़ने योग्य [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | अंतिम देखी गई स्लाइड की ओर हाइपरलिंक लौटाता है। केवल- पढ़ने योग्य [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | एक विशेष "play mediafile" हाइपरलिंक लौटाता है। AudioFrame और VideoFrame में उपयोग किया जाता है। केवल- पढ़ने योग्य [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | अगली स्लाइड की ओर हाइपरलिंक लौटाता है। केवल- पढ़ने योग्य [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | एक विशेष "do nothing" हाइपरलिंक लौटाता है। केवल- पढ़ने योग्य [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | पिछली स्लाइड की ओर हाइपरलिंक लौटाता है। केवल- पढ़ने योग्य [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | हाइपरलिंक की क्रिया का प्रकार लौटाता है। केवल- पढ़ने योग्य [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | बेस IPresentationComponent इंटरफ़ेस को प्राप्त करने की अनुमति देता है। केवल- पढ़ने योग्य [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | हाइपरलिंक रंग के स्रोत को दर्शाता है - या तो शैलियों या भाग स्वरूप। पढ़ें/लिखें [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | बाहरी URL निर्दिष्ट करता है। केवल- पढ़ने योग्य String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | इस भाग के लिए सेट किया गया एक हाइपरलिंक दर्शाता है, जिसमें भाग की वास्तविक सामग्री की परवाह नहीं की जाती। PowerPoint लिंक और उनके संबंधित पाठ के लिए विशेष रूप से व्यवहार करता है। यह एक मान्य URL के रूप में हाइपरलिंक के लिए पाठ बनाने की अनुमति देता है, जो लिंक के वास्तविक पते से अलग होता है। इस मामले में, जब आप संपादन विंडो में लिंक देखते हैं, तो यह पाठ भाग से मेल खाने के लिए बदल दिया जाएगा। यह गुण हाइपरलिंक के मूल मान को दर्शाता है। |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | निर्धारित करता है कि क्लिक पर हाइपरलिंक को हाइलाइट किया जाना चाहिए या नहीं। पढ़ें/लिखें Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | निर्धारित करता है कि मूल हाइपरलिंक का लक्ष्य जब सक्रिय हो तो देखे गए हाइपरलिंक्स की सूची में जोड़ा जाएगा या नहीं। पढ़ें/लिखें Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | हाइपरलिंक की चल रही आवाज़ को दर्शाता है। पढ़ें/लিখें [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | निर्धारित करता है कि हाइपरलिंक क्लिक पर आवाज़ को रोकना चाहिए या नहीं। पढ़ें/लिखें Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | जब मौजूद हो, तो मूल HTML फ्रेमसेट में मूल हाइपरलिंक के लक्ष्य के लिए फ्रेम लौटाता है। पढ़ें/लिखें String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | यदि हाइपरलिंक विशिष्ट स्लाइड को लक्ष्य बनाता है तो वह स्लाइड लौटाता है। केवल- पढ़ने योग्य [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | एक स्ट्रिंग लौटाता है जिसे उपयोगकर्ता इंटरफ़ेस में मूल हाइपरलिंक से संबंधित रूप में दिखाया जा सकता है। पढ़ें/लिखें String. |

## विधियां

| Name | Description |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | निर्धारित करता है कि दो Hyperlink उदाहरण समान हैं या नहीं। |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | निर्धारित करता है कि दो Hyperlink उदाहरण समान हैं या नहीं। |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | किसी विशिष्ट प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है, जो हैशिंग एल्गोरिदम और हैश टेबल जैसी डेटा संरचनाओं में उपयोग के लिए उपयुक्त है। |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | दो हाइपरलिंक की समानता का परीक्षण करता है। |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | दो हाइपरलिंक की असमानता का परीक्षण करता है। |

### देखते रहें

* वर्ग [PVIObject](../pviobject)
* इंटरफ़ेस [IHyperlink](../ihyperlink)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->