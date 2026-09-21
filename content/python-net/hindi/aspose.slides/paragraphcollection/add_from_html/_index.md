---
title: add_from_html method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/paragraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
निर्दिष्ट html स्ट्रिंग से टेक्स्ट को संग्रह में जोड़ता है।


```python
def add_from_html(self, text):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| text | **str** | HTML टेक्स्ट। |


## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
निर्दिष्ट html स्ट्रिंग से टेक्स्ट को संग्रह में जोड़ता है।


```python
def add_from_html(self, text, resolver, uri):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| text | **str** | HTML टेक्स्ट। |
| resolver | [`IExternalResourceResolver`](/slides/python-net/hi/aspose.slides.importing/iexternalresourceresolver) | Resolver कॉलबैक ऑब्जेक्ट जो URIs को हल करता है और संदर्भित वस्तुओं को प्राप्त करता है। |
| uri | **str** | HTML दस्तावेज़ जोड़ने के लिए URI। सापेक्ष लिंक को हल करने के लिए उपयोग किया जाता है। |

### टिप्पणी

Resolver निर्दिष्ट करना संभावित रूप से एक सुरक्षा कमजोरी पैदा कर सकता है। सावधानी से उपयोग करें।



### देखें
* क्लास [`IExternalResourceResolver`](/slides/python-net/hi/aspose.slides.importing/iexternalresourceresolver)
* क्लास [`ParagraphCollection`](/slides/python-net/hi/aspose.slides/paragraphcollection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)