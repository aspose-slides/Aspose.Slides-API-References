---
title: Hyperlink
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: एक हाइपरलिंक का प्रतिनिधित्व करता है।
type: docs
weight: 5120
url: /hi/aspose.slides/hyperlink/
---
## Hyperlink क्लास

Represents a hyperlink.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## निर्माता

| Name | Description |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | हाइपरलिंक का एक इंस्टेंस बनाता है जो विशिष्ट स्लाइड की ओर इशारा करता है। नोट: बनाया गया हाइपरलिंक उसी प्रस्तुति के किसी वस्तु को असाइन किया जाना चाहिए, अन्यथा लिंक NoAction के रूप में सहेजा जाएगा। |
| [Hyperlink](hyperlink#constructor_2)(string) | हाइपरलिंक का एक इंस्टेंस बनाता है। |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | एक हाइपरलिंक का इंस्टेंस बनाता है जो दूसरे हाइपरलिंक को स्रोत के रूप में उपयोग करता है, द्वितीयक गुणों को ओवरराइड करता है। |

## गुण

| Name | Description |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | एक हाइपरलिंक लौटाता है जो शो को समाप्त करता है। केवल- पढ़ने योग्य [`Hyperlink`](../hyperlink)। |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | प्रस्तुति की पहली स्लाइड के लिए एक हाइपरलिंक लौटाता है। केवल- पढ़ने योग्य [`Hyperlink`](../hyperlink)। |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | प्रस्तुति की अंतिम स्लाइड के लिए एक हाइपरलिंक लौटाता है। केवल- पढ़ने योग्य [`Hyperlink`](../hyperlink)। |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | अंतिम देखी गई स्लाइड के लिए एक हाइपरलिंक लौटाता है। केवल- पढ़ने योग्य [`Hyperlink`](../hyperlink)। |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | एक विशेष "play mediafile" हाइपरलिंक लौटाता है। AudioFrame और VideoFrame में उपयोग किया जाता है। केवल- पढ़ने योग्य [`Hyperlink`](../hyperlink)। |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | अगली स्लाइड के लिए एक हाइपरलिंक लौटाता है। केवल- पढ़ने योग्य [`Hyperlink`](../hyperlink)। |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | एक विशेष "do nothing" हाइपरलिंक लौटाता है। केवल- पढ़ने योग्य [`Hyperlink`](../hyperlink)। |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | पिछली स्लाइड के लिए एक हाइपरलिंक लौटाता है। केवल- पढ़ने योग्य [`Hyperlink`](../hyperlink)। |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | हाइपरलिंक की कार्रवाई का प्रकार लौटाता है। केवल- पढ़ने योग्य [`HyperlinkActionType`](../hyperlinkactiontype)। |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | आधार IPresentationComponent इंटरफ़ेस प्राप्त करने की अनुमति देता है। केवल- पढ़ने योग्य [`IPresentationComponent`](../ipresentationcomponent)। |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | हाइपरलिंक रंग के स्रोत का प्रतिनिधित्व करता है - शैली या भाग स्वरूप। पढ़ने/लिखने योग्य [`HyperlinkColorSource`](../hyperlinkcolorsource)। |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | बाहरी URL निर्धारित करता है। केवल- पढ़ने योग्य स्ट्रिंग। |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | एक हाइपरलिंक का प्रतिनिधित्व करता है जो इस भाग के लिए सेट किया गया है, भाग की वास्तविक सामग्री की परवाह किए बिना। PowerPoint लिंक और उनके संबंधित पाठ के लिए विशेष व्यवहार करता है। यह एक वैध URL के रूप में हाइपरलिंक के लिए पाठ बनाने की अनुमति देता है, जो लिंक के वास्तविक पते से अलग होता है। इस स्थिति में, जब आप संपादन विंडो में लिंक देखते हैं, तो यह पाठ भाग से मेल खाने के लिए बदल दिया जाता है। यह गुण हाइपरलिंक का मूल मान दर्शाता है। |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | निर्धारित करता है कि क्लिक पर हाइपरलिंक को हाइलाइट किया जाए या नहीं। पढ़ने/लिखने योग्य बूलियन। |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | निर्धारित करता है कि पैरेंट हाइपरलिंक के लक्ष्य को जब बुलाया जाए तो देखा गया हाइपरलिंक सूची में जोड़ा जाए या नहीं। पढ़ने/लिखने योग्य बूलियन। |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | हाइपरलिंक की आवाज़ प्ले करने का प्रतिनिधित्व करता है। पढ़ने/लिखने योग्य [`IAudio`](../iaudio)। |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | निर्धारित करता है कि हाइपरलिंक क्लिक पर ध्वनि को रोक दिया जाए या नहीं। पढ़ने/लिखने योग्य बूलियन। |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | पैरेंट हाइपरलिंक के लक्ष्य के लिए पैरेंट HTML फ्रेमसेट के भीतर फ्रेम लौटाता है जब यह मौजूद हो। पढ़ने/लिखने योग्य स्ट्रिंग। |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | यदि हाइपरलिंक विशिष्ट स्लाइड को लक्षित करता है तो वह स्लाइड लौटाता है। केवल- पढ़ने योग्य [`ISlide`](../islide)। |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | एक स्ट्रिंग लौटाता है जिसे उपयोगकर्ता इंटरफ़ेस में पैरेंट हाइपरलिंक के साथ संबंधित के रूप में प्रदर्शित किया जा सकता है। पढ़ने/लिखने योग्य स्ट्रिंग। |

## विधियाँ

| Name | Description |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | निर्धारित करता है कि दो हाइपरलिंक इंस्टेंस बराबर हैं या नहीं। |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | निर्धारित करता है कि दो हाइपरलिंक इंस्टेंस बराबर हैं या नहीं। |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | एक विशिष्ट प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है, जो हैशिंग एल्गोरिदम और हैश टेबल जैसे डेटा स्ट्रक्चर में उपयोग के लिए उपयुक्त है। |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | दो हाइपरलिंक की समानता की जाँच करता है। |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | दो हाइपरलिंक की असमानता की जाँच करता है। |

### संबंधित देखें

* क्लास [PVIObject](../pviobject)
* इंटरफ़ेस [IHyperlink](../ihyperlink)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->