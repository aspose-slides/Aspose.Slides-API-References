---
title: AsposeAIWebClient constructor
second_title: Python के लिए Aspose.Slides .NET API संदर्भ के माध्यम से
description: 
type: docs
url: /hi/aspose.slides.ai/asposeaiwebclient/__init__/
weight: 10
---
## __init__(self) {#}
Aspose AI वेब क्लाइंट का एक इंस्टेंस बनाता है जो डिफ़ॉल्ट Aspose LLM एंडपॉइंट से कनेक्ट होता है।  
यह क्लाइंट पैरामीटर-रहित **SlidesAIAgent.#ctor** कन्स्ट्रक्टर द्वारा उपयोग किया जाता है, इसलिए इसे स्पष्ट रूप से बनाना तभी आवश्यक होता है जब क्लाइंट को सीधे **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** कन्स्ट्रक्टर को पास किया जाए।


```python
def __init__(self):
    ...
```



## __init__(self, url) {#str}
Aspose AI वेब क्लाइंट का एक इंस्टेंस बनाता है जो कस्टम एंडपॉइंट URL से कनेक्ट होता है। इस ओवरलोड का उपयोग तब करें जब आपके पास Aspose.Slides टीम द्वारा प्रदान किया गया URL हो; अन्यथा, डिफ़ॉल्ट URL के साथ **AsposeAIWebClient.#ctor** ओवरलोड का उपयोग करें।


```python
def __init__(self, url):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| url | **str** | Aspose LLM का एन्डपॉइंट URL, जो Aspose.Slides टीम द्वारा प्रदान किया गया है। |


### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | URL None या खाली नहीं हो सकता। |



### संबंधित देखें
* क्लास [`AsposeAIWebClient`](/slides/python-net/hi/aspose.slides.ai/asposeaiwebclient)
* मॉड्यूल [`aspose.slides.ai`](/slides/python-net/hi/aspose.slides.ai)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)