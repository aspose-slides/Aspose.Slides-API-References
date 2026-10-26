---
title: insert_from_html method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/islidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

### रिटर्न

जोडी गई स्लाइड्स



```python
def insert_from_html(self, index, html_text):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | इन्सर्ट करने की स्थिति। |
| html_text | **str** | जोड़ने के लिए Html। |


## insert_from_html(self, index, html_stream) {#int-iorawiobase}
HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

### रिटर्न

जोडी गई स्लाइड्स



```python
def insert_from_html(self, index, html_stream):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | इन्सर्ट करने की स्थिति। |
| html_stream | **io.RawIOBase** | एक Stream ऑब्जेक्ट जो HTML फ़ाइल के स्रोत के रूप में उपयोग किया जाएगा। |


## insert_from_html(self, index, html_text, use_slide_with_index_as_start) {#int-str-bool}
HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

### रिटर्न

जोडी गई स्लाइड्स



```python
def insert_from_html(self, index, html_text, use_slide_with_index_as_start):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | इन्सर्ट करने की स्थिति। |
| html_text | **str** | जोड़ने के लिए Html। |
| use_slide_with_index_as_start | **bool** | यह फ़्लैग निर्धारित करता है कि सम्मिलन कैसे शुरू किया जाए: नई स्लाइड से या निर्दिष्ट इंडेक्स वाली स्लाइड से।<br/><br/>            यदि **true** , तो डेटा का सम्मिलन निर्दिष्ट इंडेक्स वाली स्लाइड पर खाली स्थान से शुरू होगा।<br/><br/>            यदि **false** , तो डेटा बनाए गए स्लाइड्स में जोड़ा जाएगा। |


## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

### रिटर्न

जोडी गई स्लाइड्स



```python
def insert_from_html(self, index, html_stream, use_slide_with_index_as_start):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | इन्सर्ट करने की स्थिति। |
| html_stream | **io.RawIOBase** | एक Stream ऑब्जेक्ट जो HTML फ़ाइल के स्रोत के रूप में उपयोग किया जाएगा। |
| use_slide_with_index_as_start | **bool** | यह फ़्लैग निर्धारित करता है कि सम्मिलन कैसे शुरू किया जाए: नई स्लाइड से या निर्दिष्ट इंडेक्स वाली स्लाइड से।<br/><br/>            यदि **true** , तो डेटा का सम्मिलन निर्दिष्ट इंडेक्स वाली स्लाइड पर खाली स्थान से शुरू होगा।<br/><br/>            यदि **false** , तो डेटा बनाए गए स्लाइड्स में जोड़ा जाएगा। |


## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

### रिटर्न

जोडी गई स्लाइड्स.



```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | इन्सर्ट करने की स्थिति। |
| html_text | **str** | जोड़ने के लिए Html। |
| resolver | [`IExternalResourceResolver`](/slides/python-net/hi/aspose.slides.importing/iexternalresourceresolver) | एक कॉलबैक ऑब्जेक्ट जो बाहरी ऑब्जेक्ट्स को प्राप्त करने के लिये उपयोग किया जाता है। यदि यह पैरामीटर None है तो सभी बाहरी ऑब्जेक्ट्स को अनदेखा किया जाएगा। |
| uri | **str** | निर्दिष्ट HTML का URI। सापेक्ष लिंक को हल करने के लिये उपयोग किया जाता है। |


## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

### रिटर्न

जोडी गई स्लाइड्स.



```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | इन्सर्ट करने की स्थिति। |
| html_stream | **io.RawIOBase** | एक Stream ऑब्जेक्ट जो HTML फ़ाइल के स्रोत के रूप में उपयोग किया जाएगा। |
| resolver | [`IExternalResourceResolver`](/slides/python-net/hi/aspose.slides.importing/iexternalresourceresolver) | एक कॉलबैक ऑब्जेक्ट जो बाहरी ऑब्जेक्ट्स को प्राप्त करने के लिये उपयोग किया जाता है। यदि यह पैरामीटर None है तो सभी बाहरी ऑब्जेक्ट्स को अनदेखा किया जाएगा। |
| uri | **str** | निर्दिष्ट HTML का URI। सापेक्ष लिंक को हल करने के लिये उपयोग किया जाता है। |


## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

### रिटर्न

जोडी गई स्लाइड्स.



```python
def insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | इन्सर्ट करने की स्थिति। |
| html_text | **str** | जोड़ने के लिए Html। |
| resolver | [`IExternalResourceResolver`](/slides/python-net/hi/aspose.slides.importing/iexternalresourceresolver) | एक कॉलबैक ऑब्जेक्ट जो बाहरी ऑब्जेक्ट्स को प्राप्त करने के लिये उपयोग किया जाता है। यदि यह पैरामीटर None है तो सभी बाहरी ऑब्जेक्ट्स को अनदेखा किया जाएगा। |
| uri | **str** | निर्दिष्ट HTML का URI। सापेक्ष लिंक को हल करने के लिये उपयोग किया जाता है। |
| use_slide_with_index_as_start | **bool** | यह फ़्लैग निर्धारित करता है कि सम्मिलन कैसे शुरू किया जाए: नई स्लाइड से या निर्दिष्ट इंडेक्स वाली स्लाइड से।<br/><br/>            यदि **true** , तो डेटा का सम्मिलन निर्दिष्ट इंडेक्स वाली स्लाइड पर खाली स्थान से शुरू होगा।<br/><br/>            यदि **false** , तो डेटा बनाए गए स्लाइड्स में जोड़ा जाएगा। |


## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
HTML टेक्स्ट से स्लाइड्स बनाता है और उन्हें निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

### रिटर्न

जोडी गई स्लाइड्स.



```python
def insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | इन्सर्ट करने की स्थिति। |
| html_stream | **io.RawIOBase** | एक Stream ऑब्जेक्ट जो HTML फ़ाइल के स्रोत के रूप में उपयोग किया जाएगा। |
| resolver | [`IExternalResourceResolver`](/slides/python-net/hi/aspose.slides.importing/iexternalresourceresolver) | एक कॉलबैक ऑब्जेक्ट जो बाहरी ऑब्जेक्ट्स को प्राप्त करने के लिये उपयोग किया जाता है। यदि यह पैरामीटर None है तो सभी बाहरी ऑब्जेक्ट्स को अनदेखा किया जाएगा। |
| uri | **str** | निर्दिष्ट HTML का URI। सापेक्ष लिंक को हल करने के लिये उपयोग किया जाता है। |
| use_slide_with_index_as_start | **bool** | यह फ़्लैग निर्धारित करता है कि सम्मिलन कैसे शुरू किया जाए: नई स्लाइड से या निर्दिष्ट इंडेक्स वाली स्लाइड से।<br/><br/>            यदि **true** , तो डेटा का सम्मिलन निर्दिष्ट इंडेक्स वाली स्लाइड पर खाली स्थान से शुरू होगा।<br/><br/>            यदि **false** , तो डेटा बनाए गए स्लाइड्स में जोड़ा जाएगा। |



### देखें
* क्लास [`IExternalResourceResolver`](/slides/python-net/hi/aspose.slides.importing/iexternalresourceresolver)
* क्लास [`ISlideCollection`](/slides/python-net/hi/aspose.slides/islidecollection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)