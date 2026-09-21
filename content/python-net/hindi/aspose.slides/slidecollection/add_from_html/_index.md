---
title: add_from_html method
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/slidecollection/add_from_html/
weight: 30
---
## add_from_html(self, html_text) {#str}
HTML पाठ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

### रिटर्न्स

जोड़े गए स्लाइड्स



```python
def add_from_html(self, html_text):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| html_text | **str** | जोड़ने के लिए Html. |


## add_from_html(self, html_stream) {#iorawiobase}
HTML पाठ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

### रिटर्न्स

जोड़े गए स्लाइड्स



```python
def add_from_html(self, html_stream):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | एक Stream ऑब्जेक्ट जो HTML फ़ाइल के स्रोत के रूप में उपयोग किया जाएगा। |


## add_from_html(self, html_text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
HTML पाठ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

### रिटर्न्स

जोड़े गए स्लाइड्स।



```python
def add_from_html(self, html_text, resolver, uri):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| html_text | **str** | जोड़ने के लिए Html. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/hi/aspose.slides.importing/iexternalresourceresolver) | बाहरी ऑब्जेक्ट्स को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर None है तो सभी बाहरी ऑब्जेक्ट्स को अनदेखा किया जाएगा। |
| uri | **str** | निर्दिष्ट HTML का URI। रिलेटिव लिंक को हल करने के लिए उपयोग किया जाता है। |


## add_from_html(self, html_stream, resolver, uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
HTML पाठ से स्लाइड्स बनाता है और उन्हें संग्रह के अंत में जोड़ता है।

### रिटर्न्स

जोड़े गए स्लाइड्स।



```python
def add_from_html(self, html_stream, resolver, uri):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | एक Stream ऑब्जेक्ट जो HTML फ़ाइल के स्रोत के रूप में उपयोग किया जाएगा। |
| resolver | [`IExternalResourceResolver`](/slides/python-net/hi/aspose.slides.importing/iexternalresourceresolver) | बाहरी ऑब्जेक्ट्स को प्राप्त करने के लिए उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर None है तो सभी बाहरी ऑब्जेक्ट्स को अनदेखा किया जाएगा। |
| uri | **str** | निर्दिष्ट HTML का URI। रिलेटिव लिंक को हल करने के लिए उपयोग किया जाता है। |



### देखें भी
* क्लास [`IExternalResourceResolver`](/slides/python-net/hi/aspose.slides.importing/iexternalresourceresolver)
* क्लास [`SlideCollection`](/slides/python-net/hi/aspose.slides/slidecollection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)