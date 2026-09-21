---
title: insert_from_html method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/slidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
HTML पाठ से स्लाइड बनाता है और निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

### Returns

जोड़ी गई स्लाइड्स



```python
def insert_from_html(self, index, html_text):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | सम्मिलित करने की स्थिति। |
| html_text | **str** | जोड़ने के लिये Html। |


## insert_from_html(self, index, html_stream) {#int-iorawiobase}
HTML पाठ से स्लाइड बनाता है और निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

### Returns

जोड़ी गई स्लाइड्स



```python
def insert_from_html(self, index, html_stream):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | सम्मिलित करने की स्थिति। |
| html_stream | **io.RawIOBase** | एक स्ट्रीम ऑब्जेक्ट जो HTML फ़ाइल का स्रोत बनाने के लिये उपयोग किया जाएगा। |


## insert_from_html(self, index, html_text, use_slide_with_index_as_start) {#int-str-bool}
HTML पाठ से स्लाइड बनाता है और निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

### Returns

जोड़ी गई स्लाइड्स



```python
def insert_from_html(self, index, html_text, use_slide_with_index_as_start):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | सम्मिलित करने की स्थिति। |
| html_text | **str** | जोड़ने के लिये Html। |
| use_slide_with_index_as_start | **bool** | यह फ़्लैग यह निर्धारित करता है कि सम्मिलन कैसे शुरू किया जाए: नई स्लाइड से या निर्दिष्ट इंडेक्स वाली स्लाइड से।<br/><br/>If **true** , then data insertion will start from an empty space on the slide with the specified index.<br/><br/>If **false** , then data will be added to the created slides. |


## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
HTML पाठ से स्लाइड बनाता है और निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

### Returns

जोड़ी गई स्लाइड्स



```python
def insert_from_html(self, index, html_stream, use_slide_with_index_as_start):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | सम्मिलित करने की स्थिति। |
| html_stream | **io.RawIOBase** | एक स्ट्रीम ऑब्जेक्ट जो HTML फ़ाइल का स्रोत बनाने के लिये उपयोग किया जाएगा। |
| use_slide_with_index_as_start | **bool** | यह फ़्लैग यह निर्धारित करता है कि सम्मिलन कैसे शुरू किया जाए: नई स्लाइड से या निर्दिष्ट इंडेक्स वाली स्लाइड से।<br/><br/>If **true** , then data insertion will start from an empty space on the slide with the specified index.<br/><br/>If **false** , then data will be added to the created slides. |


## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
HTML पाठ से स्लाइड बनाता है और निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

### Returns

जोड़ी गई स्लाइड्स.



```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | सम्मिलित करने की स्थिति। |
| html_text | **str** | जोड़ने के लिये Html। |
| resolver | [`IExternalResourceResolver`](/slides/python-net/hi/aspose.slides.importing/iexternalresourceresolver) | बाहरी ऑब्जेक्ट्स लाने के लिये उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर None है तो सभी बाहरी ऑब्जेक्ट्स को अनदेखा किया जाएगा। |
| uri | **str** | निर्दिष्ट HTML का URI। सापेक्ष लिंक हल करने के लिये उपयोग किया जाता है। |


## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
HTML पाठ से स्लाइड बनाता है और निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

### Returns

जोड़ी गई स्लाइड्स.



```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | सम्मिलित करने की स्थिति। |
| html_stream | **io.RawIOBase** | एक स्ट्रीम ऑब्जेक्ट जो HTML फ़ाइल का स्रोत बनाने के लिये उपयोग किया जाएगा। |
| resolver | [`IExternalResourceResolver`](/slides/python-net/hi/aspose.slides.importing/iexternalresourceresolver) | बाहरी ऑब्जेक्ट्स लाने के लिये उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर None है तो सभी बाहरी ऑब्जेक्ट्स को अनदेखा किया जाएगा। |
| uri | **str** | निर्दिष्ट HTML का URI। सापेक्ष लिंक हल करने के लिये उपयोग किया जाता है। |


## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
HTML पाठ से स्लाइड बनाता है और निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

### Returns

जोड़ी गई स्लाइड्स.



```python
def insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | सम्मिलित करने की स्थिति। |
| html_text | **str** | जोड़ने के लिये Html। |
| resolver | [`IExternalResourceResolver`](/slides/python-net/hi/aspose.slides.importing/iexternalresourceresolver) | बाहरी ऑब्जेक्ट्स लाने के लिये उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर None है तो सभी बाहरी ऑब्जेक्ट्स को अनदेखा किया जाएगा। |
| uri | **str** | निर्दिष्ट HTML का URI। सापेक्ष लिंक हल करने के लिये उपयोग किया जाता है। |
| use_slide_with_index_as_start | **bool** | यह फ़्लैग यह निर्धारित करता है कि सम्मिलन कैसे शुरू किया जाए: नई स्लाइड से या निर्दिष्ट इंडेक्स वाली स्लाइड से।<br/><br/>If **true** , then data insertion will start from an empty space on the slide with the specified index.<br/><br/>If **false** , then data will be added to the created slides. |


## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
HTML पाठ से स्लाइड बनाता है और निर्दिष्ट स्थिति पर संग्रह में सम्मिलित करता है।

### Returns

जोड़ी गई स्लाइड्स.



```python
def insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | सम्मिलित करने की स्थिति। |
| html_stream | **io.RawIOBase** | एक स्ट्रीम ऑब्जेक्ट जो HTML फ़ाइल का स्रोत बनाने के लिये उपयोग किया जाएगा। |
| resolver | [`IExternalResourceResolver`](/slides/python-net/hi/aspose.slides.importing/iexternalresourceresolver) | बाहरी ऑब्जेक्ट्स लाने के लिये उपयोग किया जाने वाला कॉलबैक ऑब्जेक्ट। यदि यह पैरामीटर None है तो सभी बाहरी ऑब्जेक्ट्स को अनदेखा किया जाएगा। |
| uri | **str** | निर्दिष्ट HTML का URI। सापेक्ष लिंक हल करने के लिये उपयोग किया जाता है। |
| use_slide_with_index_as_start | **bool** | यह फ़्लैग यह निर्धारित करता है कि सम्मिलन कैसे शुरू किया जाए: नई स्लाइड से या निर्दिष्ट इंडेक्स वाली स्लाइड से।<br/><br/>If **true** , then data insertion will start from an empty space on the slide with the specified index.<br/><br/>If **false** , then data will be added to the created slides. |



### See Also
* क्लास [`IExternalResourceResolver`](/slides/python-net/hi/aspose.slides.importing/iexternalresourceresolver)
* क्लास [`SlideCollection`](/slides/python-net/hi/aspose.slides/slidecollection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)