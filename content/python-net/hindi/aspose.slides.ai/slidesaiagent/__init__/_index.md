---
title: SlidesAIAgent constructor
second_title: Aspose.Slides Python के लिए .NET API संदर्भ के माध्यम से
description: 
type: docs
url: /hi/aspose.slides.ai/slidesaiagent/__init__/
weight: 10
---
## __init__(self) {#}
एक नया उदाहरण प्रारम्भ करता है [`SlidesAIAgent`](/slides/python-net/hi/aspose.slides.ai/slidesaiagent) का उपयोग करके निर्मित
            [`AsposeAIWebClient`](/slides/python-net/hi/aspose.slides.ai/asposeaiwebclient) अपने डिफ़ॉल्ट विन्यास के साथ। क्लाइंट जुड़ता है Aspose के अपने LLM से और अतिरिक्त विन्यास की आवश्यकता नहीं है।
            एक अलग AI क्लाइंट का उपयोग करने के लिए, **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** ओवरलोड का उपयोग करें।


```python
def __init__(self):
    ...
```



## __init__(self, ai_client) {#iaiwebclient}
एक नया उदाहरण प्रारम्भ करता है [`SlidesAIAgent`](/slides/python-net/hi/aspose.slides.ai/slidesaiagent) को एक कस्टम AI क्लाइंट के साथ।
            इस ओवरलोड का उपयोग AI प्रदाता निर्दिष्ट करने, अपना स्वयं का LLM प्रदान करने, या कस्टमाइज़ करने के लिए करें।
            कनेक्शन (उदाहरण के लिए, अपना स्वयं का `HttpClient` प्रदान करके)।
            किसी भी [`IAIWebClient`](/slides/python-net/hi/aspose.slides.ai/iaiwebclient) कार्यान्वयन का उपयोग किया जा सकता है, जिसमें शामिल हैं:
* [`AsposeAIWebClient`](/slides/python-net/hi/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/hi/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/hi/aspose.slides.ai/openaicompatiblewebclient)


            निर्मित [`AsposeAIWebClient`](/slides/python-net/hi/aspose.slides.ai/asposeaiwebclient) को उसके डिफ़ॉल्ट विन्यास के साथ उपयोग करने के लिए,
            **SlidesAIAgent.#ctor** ओवरलोड का उपयोग करें।


```python
def __init__(self, ai_client):
    ...
```


| परामीटर | प्रकार | विवरण |
| :- | :- | :- |
| ai_client | [`IAIWebClient`](/slides/python-net/hi/aspose.slides.ai/iaiwebclient) | AI क्लाइंट इन्स्टेंस। कोई भी [`IAIWebClient`](/slides/python-net/hi/aspose.slides.ai/iaiwebclient) कार्यान्वयन का उपयोग किया जा सकता है। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | AI क्लाइंट इन्स्टेंस प्रदान नहीं किया गया है। |



### संबंधित देखें
* क्लास [`AsposeAIWebClient`](/slides/python-net/hi/aspose.slides.ai/asposeaiwebclient)
* क्लास [`IAIWebClient`](/slides/python-net/hi/aspose.slides.ai/iaiwebclient)
* क्लास [`OpenAICompatibleWebClient`](/slides/python-net/hi/aspose.slides.ai/openaicompatiblewebclient)
* क्लास [`OpenAIWebClient`](/slides/python-net/hi/aspose.slides.ai/openaiwebclient)
* क्लास [`SlidesAIAgent`](/slides/python-net/hi/aspose.slides.ai/slidesaiagent)
* मॉड्यूल [`aspose.slides.ai`](/slides/python-net/hi/aspose.slides.ai)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)