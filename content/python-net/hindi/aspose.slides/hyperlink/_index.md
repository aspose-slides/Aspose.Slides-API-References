---
title: Hyperlink class
second_title: Aspose.Slides for Python द्वारा .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/hyperlink/
---
## Hyperlink क्लास

एक हाइपरलिंक का प्रतिनिधित्व करता है।

**विरासत:**[`Hyperlink`](/slides/python-net/hi/aspose.slides/hyperlink) → [`PVIObject`](/slides/python-net/hi/aspose.slides/pviobject)

Hyperlink प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| :- | :- |
| [`__init__(self, url)`](/slides/python-net/hi/aspose.slides/hyperlink/__init__/#str) | एक हाइपरलिंक का एक उदाहरण बनाता है। |
| [`__init__(self, slide)`](/slides/python-net/hi/aspose.slides/hyperlink/__init__/#islide) | एक हाइपरलिंक का एक उदाहरण बनाता है जो विशिष्ट स्लाइड की ओर संकेत करता है.<br/>            नोट: बनाए गए हाइपरलिंक को उसी प्रस्तुति के किसी वस्तु के साथ असाइन किया जाना चाहिए, अन्यथा लिंक NoAction के रूप में सहेजा जाएगा। |
| [`__init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click)`](/slides/python-net/hi/aspose.slides/hyperlink/__init__/#hyperlink-str-str-bool-bool-bool) | एक अन्य हाइपरलिंक को स्रोत के रूप में उपयोग करके हाइपरलिंक का एक उदाहरण बनाता है, द्वितीयक गुणों को ओवरराइड करता है। |

## प्रॉपर्टीज

| गुण | विवरण |
| :- | :- |
| [`no_action`](/slides/python-net/hi/aspose.slides/hyperlink/no_action/) | एक विशेष "do nothing" हाइपरलिंक लौटाता है.<br/>            केवल पढ़ने योग्य [`Hyperlink`](/slides/python-net/hi/aspose.slides/hyperlink). |
| [`media`](/slides/python-net/hi/aspose.slides/hyperlink/media/) | एक विशेष "play mediafile" हाइपरलिंक लौटाता है। AudioFrame और VideoFrame में उपयोग किया जाता है.<br/>            केवल पढ़ने योग्य [`Hyperlink`](/slides/python-net/hi/aspose.slides/hyperlink). |
| [`next_slide`](/slides/python-net/hi/aspose.slides/hyperlink/next_slide/) | अगली स्लाइड के लिए एक हाइपरलिंक लौटाता है.<br/>            केवल पढ़ने योग्य [`Hyperlink`](/slides/python-net/hi/aspose.slides/hyperlink). |
| [`previous_slide`](/slides/python-net/hi/aspose.slides/hyperlink/previous_slide/) | पिछली स्लाइड के लिए एक हाइपरलिंक लौटाता है.<br/>            केवल पढ़ने योग्य [`Hyperlink`](/slides/python-net/hi/aspose.slides/hyperlink). |
| [`first_slide`](/slides/python-net/hi/aspose.slides/hyperlink/first_slide/) | प्रस्तुति की पहली स्लाइड के लिए एक हाइपरलिंक लौटाता है.<br/>            केवल पढ़ने योग्य [`Hyperlink`](/slides/python-net/hi/aspose.slides/hyperlink). |
| [`last_slide`](/slides/python-net/hi/aspose.slides/hyperlink/last_slide/) | प्रस्तुति की आखिरी स्लाइड के लिए एक हाइपरलिंक लौटाता है.<br/>            केवल पढ़ने योग्य [`Hyperlink`](/slides/python-net/hi/aspose.slides/hyperlink). |
| [`last_vieved_slide`](/slides/python-net/hi/aspose.slides/hyperlink/last_vieved_slide/) | अंतिम देखी गई स्लाइड के लिए एक हाइपरलिंक लौटाता है.<br/>            केवल पढ़ने योग्य [`Hyperlink`](/slides/python-net/hi/aspose.slides/hyperlink). |
| [`end_show`](/slides/python-net/hi/aspose.slides/hyperlink/end_show/) | एक हाइपरलिंक लौटाता है जो शो को समाप्त करता है.<br/>            केवल पढ़ने योग्य [`Hyperlink`](/slides/python-net/hi/aspose.slides/hyperlink). |
| [`action_type`](/slides/python-net/hi/aspose.slides/hyperlink/action_type/) | हाइपरलिंक की कार्रवाई का प्रकार लौटाता है.<br/>            केवल पढ़ने योग्य [`HyperlinkActionType`](/slides/python-net/hi/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/hi/aspose.slides/hyperlink/external_url/) | बाहरी URL निर्दिष्ट करता है.<br/>            केवल पढ़ने योग्य **str**. |
| [`target_slide`](/slides/python-net/hi/aspose.slides/hyperlink/target_slide/) | यदि हाइपरलिंक विशिष्ट स्लाइड को लक्षित करता है तो यह स्लाइड लौटाता है.<br/>            केवल पढ़ने योग्य [`ISlide`](/slides/python-net/hi/aspose.slides/islide). |
| [`external_url_original`](/slides/python-net/hi/aspose.slides/hyperlink/external_url_original/) | एक हाइपरलिंक को दर्शाता है जो इस भाग के लिए सेट किया गया है बिना भाग की वास्तविक सामग्री को देखे।<br/>            <br/>            PowerPoint भाग में लिंक और उनके संबंधित टेक्स्ट के लिए विशेष व्यवहार करता है। यह हाइपरलिंक के लिए टेक्स्ट बनाना संभव बनाता है<br/>            वैध URL के रूप में, जो लिंक के वास्तविक पते से अलग होता है। इस मामले में, जब आप एडिट विंडो में लिंक देखते हैं, तो यह<br/>            टेक्स्ट भाग से मेल खाने के लिए बदला जाएगा। यह प्रॉपर्टी हाइपरलिंक के मूल मान को दर्शाती है। |
| [`target_frame`](/slides/python-net/hi/aspose.slides/hyperlink/target_frame/) | जब मौजूद हो, तो पैरेंट हाइपरलिंक के लक्ष्य के लिए पैरेंट HTML फ्रेमसेट के भीतर फ्रेम लौटाता है।<br/>            पढ़ने/लिखने योग्य **str**. |
| [`tooltip`](/slides/python-net/hi/aspose.slides/hyperlink/tooltip/) | एक स्ट्रिंग लौटाता है जो उपयोगकर्ता इंटरफ़ेस में दिख सकती है<br/>            पैरेंट हाइपरलिंक के साथ संबद्ध के रूप में।<br/>            पढ़ने/लिखने योग्य **str**. |
| [`history`](/slides/python-net/hi/aspose.slides/hyperlink/history/) | निर्धारित करता है कि क्या पैरेंट हाइपरलिंक का लक्ष्य लिंक को सक्रिय करने पर देखे गए हाइपरलिंक्स की सूची में जोड़ा जाएगा.<br/>            पढ़ने/लिखने योग्य **bool**. |
| [`highlight_click`](/slides/python-net/hi/aspose.slides/hyperlink/highlight_click/) | निर्धारित करता है कि क्या हाइपरलिंक पर क्लिक करने पर उसे हाइलाइट किया जाना चाहिए.<br/>            पढ़ने/लिखने योग्य **bool**. |
| [`stop_sound_on_click`](/slides/python-net/hi/aspose.slides/hyperlink/stop_sound_on_click/) | निर्धारित करता है कि क्या हाइपरलिंक क्लिक पर ध्वनि को रोकना चाहिए.<br/>            पढ़ने/लिखने योग्य **bool**. |
| [`sound`](/slides/python-net/hi/aspose.slides/hyperlink/sound/) | हाइपरलिंक की चल रही ध्वनि को दर्शाता है.<br/>            पढ़ने/लिखने योग्य [`IAudio`](/slides/python-net/hi/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/hi/aspose.slides/hyperlink/color_source/) | हाइपरलिंक रंग का स्रोत दर्शाता है - या तो स्टाइल या भाग फ़ॉर्मेट.<br/>            पढ़ने/लिखने योग्य [`HyperlinkColorSource`](/slides/python-net/hi/aspose.slides/hyperlinkcolorsource). |
| [`slide`](/slides/python-net/hi/aspose.slides/hyperlink/slide/) |  |
| [`presentation`](/slides/python-net/hi/aspose.slides/hyperlink/presentation/) |  |

## मेथड्स

| मेथड | विवरण |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/hi/aspose.slides/hyperlink/equals/#ihyperlink) | निर्धारित करता है कि क्या दो हाइपरलिंक इंस्टेंस समान हैं। |

### देखें भी
* क्लास [`Hyperlink`](/slides/python-net/hi/aspose.slides/hyperlink)
* क्लास [`PVIObject`](/slides/python-net/hi/aspose.slides/pviobject)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)