---
title: translate method
second_title: Aspose.Slides for Python द्वारा .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.ai/slidesaiagent/translate/
weight: 30
---
## translate(self, presentation, language) {#ipresentation-str}
AI (सिंक्रोनस संस्करण) का उपयोग करके presentation को निर्दिष्ट भाषा में अनुवाद करता है।


```python
def translate(self, presentation, language):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation) | Target presentation |
| language | **str** | Target language |

### टिप्पणियाँ
The example below uses the default [`AsposeAIWebClient`](/slides/python-net/hi/aspose.slides.ai/asposeaiwebclient), which is created by the
             पैरामीटररहित **SlidesAIAgent.#ctor** कन्स्ट्रक्टर द्वारा बनाया गया है और Aspose के अपने LLM से जुड़ता है।
             विभिन्न AI प्रदाता का उपयोग करने के लिए, अपना स्वयं का LLM प्रदान करें, या कनेक्शन को कस्टमाइज़ करें
             (उदाहरण के लिए, अपना `HttpClient` प्रदान करके), एक [`IAIWebClient`](/slides/python-net/hi/aspose.slides.ai/iaiwebclient) पास करें
             इम्प्लीमेंटेशन को **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** कन्स्ट्रक्टर को पास करें। उपलब्ध
             इम्प्लीमेंटेशन में शामिल हैं:
* [`AsposeAIWebClient`](/slides/python-net/hi/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/hi/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/hi/aspose.slides.ai/openaicompatiblewebclient)

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Presentation इंस्टेंस प्रदान नहीं किया गया है |
| **RuntimeError(Proxy error(ArgumentException))** | Language मान None या खाली नहीं हो सकता |



### संबंधित देखें
* क्लास [`AsposeAIWebClient`](/slides/python-net/hi/aspose.slides.ai/asposeaiwebclient)
* क्लास [`IAIWebClient`](/slides/python-net/hi/aspose.slides.ai/iaiwebclient)
* क्लास [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation)
* क्लास [`OpenAICompatibleWebClient`](/slides/python-net/hi/aspose.slides.ai/openaicompatiblewebclient)
* क्लास [`OpenAIWebClient`](/slides/python-net/hi/aspose.slides.ai/openaiwebclient)
* क्लास [`SlidesAIAgent`](/slides/python-net/hi/aspose.slides.ai/slidesaiagent)
* मॉड्यूल [`aspose.slides.ai`](/slides/python-net/hi/aspose.slides.ai)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)