---
title: save method
second_title: Aspose.Slides Python के लिए .NET के माध्यम से API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ipresentation/save/
weight: 90
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
एक प्रस्तुति की सभी स्लाइड्स को XAML मार्कअप का प्रतिनिधित्व करने वाली फाइलों के सेट में सहेजता है।


```python
def save(self, options):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/hi/aspose.slides.export.xaml/ixamloptions) | XAML फ़ॉर्मेट विकल्प। |


## save(self, fname, format) {#str-asposeslidesexportsaveformat}
एक प्रस्तुति की सभी स्लाइड्स को निर्दिष्ट प्रारूप वाली फ़ाइल में सहेजता है।


```python
def save(self, fname, format):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| fname | **str** | बनाई गई फ़ाइल का पथ। |
| format | [`SaveFormat`](/slides/python-net/hi/aspose.slides.export/saveformat) | निर्यात किए गए डेटा का फ़ॉर्मेट। |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
एक प्रस्तुति की सभी स्लाइड्स को निर्दिष्ट प्रारूप में एक स्ट्रीम में सहेजता है।


```python
def save(self, stream, format):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream | **io.RawIOBase** | आउटपुट स्ट्रीम। |
| format | [`SaveFormat`](/slides/python-net/hi/aspose.slides.export/saveformat) | निर्यात किए गए डेटा का फ़ॉर्मेट। |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
एक प्रस्तुति की सभी स्लाइड्स को निर्दिष्ट प्रारूप और अतिरिक्त विकल्पों के साथ फ़ाइल में सहेजता है।


```python
def save(self, fname, format, options):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| fname | **str** | बनाई गई फ़ाइल का पथ। |
| format | [`SaveFormat`](/slides/python-net/hi/aspose.slides.export/saveformat) | निर्यात किए गए डेटा का फ़ॉर्मेट। |
| options | [`ISaveOptions`](/slides/python-net/hi/aspose.slides.export/isaveoptions) | अतिरिक्त फ़ॉर्मेट विकल्प। |


## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
एक प्रस्तुति की सभी स्लाइड्स को निर्दिष्ट प्रारूप और अतिरिक्त विकल्पों के साथ स्ट्रीम में सहेजता है।


```python
def save(self, stream, format, options):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream | **io.RawIOBase** | आउटपुट स्ट्रीम। |
| format | [`SaveFormat`](/slides/python-net/hi/aspose.slides.export/saveformat) | निर्यात किए गए डेटा का फ़ॉर्मेट। |
| options | [`ISaveOptions`](/slides/python-net/hi/aspose.slides.export/isaveoptions) | अतिरिक्त फ़ॉर्मेट विकल्प। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | यदि आप एन्क्रिप्टेड फ़ाइल को <br/>            Office 2007-2010 के अलावा किसी भी फ़ॉर्मेट में सहेजने का प्रयास करते हैं। |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
एक प्रस्तुति की निर्दिष्ट स्लाइड्स को निर्दिष्ट प्रारूप वाली फ़ाइल में सहेजता है।


```python
def save(self, fname, slides, format):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| fname | **str** | बनाई गई फ़ाइल का पथ। |
| slides | **List[int]** | स्लाइड स्थितियों की सरणी, 1 से शुरू। |
| format | [`SaveFormat`](/slides/python-net/hi/aspose.slides.export/saveformat) | निर्यात किए गए डेटा का फ़ॉर्मेट। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | जब stream या slides पैरामीटर None होता है। |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | जब slides पैरामीटर में गलत पृष्ठ संख्या होती है। |
| **RuntimeError(Proxy error(InvalidOperationException))** | जब असमर्थित SaveFormat का उपयोग किया जाता है, उदाहरण के लिए PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP। |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
एक प्रस्तुति की निर्दिष्ट स्लाइड्स को निर्दिष्ट प्रारूप में स्ट्रीम में सहेजता है।


```python
def save(self, stream, slides, format):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream | **io.RawIOBase** | आउटपुट स्ट्रीम। |
| slides | **List[int]** | स्लाइड स्थितियों की सरणी, 1 से शुरू। |
| format | [`SaveFormat`](/slides/python-net/hi/aspose.slides.export/saveformat) | निर्यात किए गए डेटा का फ़ॉर्मेट। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | जब stream या slides पैरामीटर None होता है। |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | जब slides पैरामीटर में गलत पृष्ठ संख्या होती है। |
| **RuntimeError(Proxy error(InvalidOperationException))** | जब असमर्थित SaveFormat का उपयोग किया जाता है, उदाहरण के लिए PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP। |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
एक प्रस्तुति की निर्दिष्ट स्लाइड्स को निर्दिष्ट प्रारूप और अतिरिक्त विकल्पों के साथ फ़ाइल में सहेजता है।


```python
def save(self, fname, slides, format, options):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| fname | **str** | बनाई गई फ़ाइल का पथ। |
| slides | **List[int]** | स्लाइड स्थितियों की सरणी, 1 से शुरू। |
| format | [`SaveFormat`](/slides/python-net/hi/aspose.slides.export/saveformat) | निर्यात किए गए डेटा का फ़ॉर्मेट। |
| options | [`ISaveOptions`](/slides/python-net/hi/aspose.slides.export/isaveoptions) | अतिरिक्त फ़ॉर्मेट विकल्प। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | जब stream या slides पैरामीटर None होता है। |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | जब slides पैरामीटर में गलत पृष्ठ संख्या होती है। |
| **RuntimeError(Proxy error(InvalidOperationException))** | जब असमर्थित SaveFormat का उपयोग किया जाता है, उदाहरण के लिए PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP। |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
एक प्रस्तुति की निर्दिष्ट स्लाइड्स को निर्दिष्ट प्रारूप और अतिरिक्त विकल्पों के साथ स्ट्रीम में सहेजता है।


```python
def save(self, stream, slides, format, options):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream | **io.RawIOBase** | आउटपुट स्ट्रीम। |
| slides | **List[int]** | स्लाइड स्थितियों की सरणी, 1 से शुरू। |
| format | [`SaveFormat`](/slides/python-net/hi/aspose.slides.export/saveformat) | निर्यात किए गए डेटा का फ़ॉर्मेट। |
| options | [`ISaveOptions`](/slides/python-net/hi/aspose.slides.export/isaveoptions) | अतिरिक्त फ़ॉर्मेट विकल्प। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | जब stream या slides पैरामीटर None होता है। |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | जब slides पैरामीटर में गलत पृष्ठ संख्या होती है। |
| **RuntimeError(Proxy error(InvalidOperationException))** | जब असमर्थित SaveFormat का उपयोग किया जाता है, उदाहरण के लिए PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP। |



### देखें
* क्लास [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation)
* क्लास [`ISaveOptions`](/slides/python-net/hi/aspose.slides.export/isaveoptions)
* क्लास [`IXamlOptions`](/slides/python-net/hi/aspose.slides.export.xaml/ixamloptions)
* एन्यूमरेशन [`SaveFormat`](/slides/python-net/hi/aspose.slides.export/saveformat)
* मोड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)