---
title: generate_presentation method
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.ai/slidesaiagent/generate_presentation/
weight: 20
---
## generate_presentation(self, description, presentation_content_amount) {#str-presentationcontentamounttype}
एक टेक्स्ट विवरण से प्रस्तुति का उदाहरण उत्पन्न करता है। आवश्यक भाषा में एक विषय, विचार, उद्धरण, या टेक्स्ट स्निपेट प्रदान करें।

```python
def generate_presentation(self, description, presentation_content_amount):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| description | **str** | The topic, ideas, quotes, or text snippets. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/hi/aspose.slides.ai/presentationcontentamounttype) | The amount of content in the resulting presentation. |

### टिप्पणी
नीचे दिया गया उदाहरण डिफॉल्ट [`AsposeAIWebClient`](/slides/python-net/hi/aspose.slides.ai/asposeaiwebclient) का उपयोग करता है, जिसे बिना पैरामीटर वाले **SlidesAIAgent.#ctor** कंस्ट्रक्टर द्वारा बनाया गया है और यह Aspose के अपने LLM से जुड़ता है। अलग AI प्रदाता का उपयोग करने के लिए, अपना स्वयं का LLM प्रदान करें, या कनेक्शन को अनुकूलित करें (उदाहरण के लिए, अपना `HttpClient` प्रदान करके), **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** कंस्ट्रक्टर को एक [`IAIWebClient`](/slides/python-net/hi/aspose.slides.ai/iaiwebclient) इम्प्लीमेंटेशन पास करें। उपलब्ध इम्प्लीमेंटेशन में शामिल हैं:
             
* [`AsposeAIWebClient`](/slides/python-net/hi/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/hi/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/hi/aspose.slides.ai/openaicompatiblewebclient)

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | AI चैट निर्देश None या खाली नहीं हो सकता। |


## generate_presentation(self, description, presentation_content_amount, presentation_template) {#str-presentationcontentamounttype-ipresentation}
एक टेक्स्ट विवरण से प्रस्तुति का उदाहरण उत्पन्न करता है। आवश्यक भाषा में एक विषय, विचार, उद्धरण, या टेक्स्ट स्निपेट प्रदान करें।

```python
def generate_presentation(self, description, presentation_content_amount, presentation_template):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| description | **str** | The topic, ideas, quotes, or text snippets. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/hi/aspose.slides.ai/presentationcontentamounttype) | The amount of content in the resulting presentation. |
| presentation_template | [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation) | A presentation to use as a template for layout and design, replacing the default template. |

### टिप्पणी
नीचे दिया गया उदाहरण डिफॉल्ट [`AsposeAIWebClient`](/slides/python-net/hi/aspose.slides.ai/asposeaiwebclient) का उपयोग करता है, जिसे बिना पैरामीटर वाले **SlidesAIAgent.#ctor** कंस्ट्रक्टर द्वारा बनाया गया है और यह Aspose के अपने LLM से जुड़ता है। अलग AI प्रदाता का उपयोग करने के लिए, अपना स्वयं का LLM प्रदान करें, या कनेक्शन को अनुकूलित करें (उदाहरण के लिए, अपना `HttpClient` प्रदान करके), **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** कंस्ट्रक्टर को एक [`IAIWebClient`](/slides/python-net/hi/aspose.slides.ai/iaiwebclient) इम्प्लीमेंटेशन पास करें। उपलब्ध इम्प्लीमेंटेशन में शामिल हैं:
            
* [`AsposeAIWebClient`](/slides/python-net/hi/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/hi/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/hi/aspose.slides.ai/openaicompatiblewebclient)

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | प्रस्तुति टेम्पलेट प्रदान नहीं किया गया है। |
| **RuntimeError(Proxy error(ArgumentException))** | AI चैट निर्देश None या खाली नहीं हो सकता। |



### संबंधित देखें
* क्लास [`AsposeAIWebClient`](/slides/python-net/hi/aspose.slides.ai/asposeaiwebclient)
* क्लास [`IAIWebClient`](/slides/python-net/hi/aspose.slides.ai/iaiwebclient)
* क्लास [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation)
* क्लास [`OpenAICompatibleWebClient`](/slides/python-net/hi/aspose.slides.ai/openaicompatiblewebclient)
* क्लास [`OpenAIWebClient`](/slides/python-net/hi/aspose.slides.ai/openaiwebclient)
* एन्यूमरेशन [`PresentationContentAmountType`](/slides/python-net/hi/aspose.slides.ai/presentationcontentamounttype)
* क्लास [`SlidesAIAgent`](/slides/python-net/hi/aspose.slides.ai/slidesaiagent)
* मॉड्यूल [`aspose.slides.ai`](/slides/python-net/hi/aspose.slides.ai)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)