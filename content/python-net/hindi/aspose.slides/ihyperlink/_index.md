---
title: IHyperlink class
second_title: Aspose.Slides Python के लिए .NET के माध्यम से API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ihyperlink/
---
## IHyperlink क्लास

Represents a hyperlink.

The IHyperlink type exposes the following members:

## गुण

| Property | Description |
| :- | :- |
| [`action_type`](/slides/python-net/hi/aspose.slides/ihyperlink/action_type/) | HyperLinkEx की क्रिया का प्रकार लौटाता है।<br/>            केवल पढ़ने योग्य [`HyperlinkActionType`](/slides/python-net/hi/aspose.slides/hyperlinkactiontype)। |
| [`external_url`](/slides/python-net/hi/aspose.slides/ihyperlink/external_url/) | बाहरी URL निर्दिष्ट करता है<br/>            यदि यह गुण None नहीं रहता है तो TargetSlide गुण None हो जाता है।<br/>            केवल पढ़ने योग्य **str**। |
| [`external_url_original`](/slides/python-net/hi/aspose.slides/ihyperlink/external_url_original/) | इस भाग के वास्तविक सामग्री को परहेज करते हुए इस भाग के लिए सेट किए गए हाइपरलिंक का प्रतिनिधित्व करता है।<br/>            <br/>            PowerPoint लिंक और उनके संबंधित पाठ के लिए इस भाग में विशिष्ट रूप से व्यवहार करता है। यह हाइपरलिंक के लिए पाठ बनाने की अनुमति देता है<br/>            मान्य URL के रूप में, जो लिंक के वास्तविक पते से अलग है। इस केस में, जब आप संपादन विंडो में लिंक देखते हैं, तो यह<br/>            पाठ भाग से मेल खाने के लिए बदल दिया जाता है। यह गुण हाइपरलिंक के मूल मान का प्रतिनिधित्व करता है। |
| [`target_slide`](/slides/python-net/hi/aspose.slides/ihyperlink/target_slide/) | यदि HyperlinkEx विशेष स्लाइड को लक्षित करता है तो यह स्लाइड लौटाता है।<br/>            यदि यह गुण None नहीं रहता है तो ExternalUrl गुण None हो जाता है।<br/>            केवल पढ़ने योग्य [`ISlide`](/slides/python-net/hi/aspose.slides/islide)। |
| [`target_frame`](/slides/python-net/hi/aspose.slides/ihyperlink/target_frame/) | जब मौजूद हो, पैरेंट हाइपरलिंक के लक्ष्य के लिए पैरेंट HTML फ्रेमसेट के भीतर फ्रेम लौटाता है।<br/>            पढ़ने/लिखने योग्य **str**। |
| [`tooltip`](/slides/python-net/hi/aspose.slides/ihyperlink/tooltip/) | पैरेंट हाइपरलिंक से संबंधित उपयोगकर्ता इंटरफ़ेस में प्रदर्शित हो सकने वाली स्ट्रिंग लौटाता है।<br/>            पढ़ने/लिखने योग्य **str**। |
| [`history`](/slides/python-net/hi/aspose.slides/ihyperlink/history/) | निर्धारित करता है कि पैरेंट हाइपरलिंक का लक्ष्य जब बुलाया जाए तो देखे गए हाइपरलिंक की सूची में जोड़ा जाना चाहिए या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`highlight_click`](/slides/python-net/hi/aspose.slides/ihyperlink/highlight_click/) | निर्धारित करता है कि क्लिक पर हाइपरलिंक को हाइलाइट किया जाना चाहिए या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`stop_sound_on_click`](/slides/python-net/hi/aspose.slides/ihyperlink/stop_sound_on_click/) | निर्धारित करता है कि हाइपरलिंक क्लिक पर ध्वनि को रोकना चाहिए या नहीं।<br/>            पढ़ने/लिखने योग्य **bool**। |
| [`sound`](/slides/python-net/hi/aspose.slides/ihyperlink/sound/) | हाइपरलिंक की चल रही ध्वनि का प्रतिनिधित्व करता है।<br/>            पढ़ने/लिखने योग्य [`IAudio`](/slides/python-net/hi/aspose.slides/iaudio)। |
| [`color_source`](/slides/python-net/hi/aspose.slides/ihyperlink/color_source/) | हाइ퍼लिंक रंग के स्रोत का प्रतिनिधित्व करता है - या तो शैलियों या भाग प्रारूप द्वारा।<br/>            पढ़ने/लिखने योग्य [`HyperlinkColorSource`](/slides/python-net/hi/aspose.slides/hyperlinkcolorsource)। |

## विधियाँ

| Method | Description |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/hi/aspose.slides/ihyperlink/equals/#ihyperlink) | निर्धारित करता है कि दो Hyperlink उदाहरण समान हैं या नहीं। |

### सम्बंधित देखें
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)