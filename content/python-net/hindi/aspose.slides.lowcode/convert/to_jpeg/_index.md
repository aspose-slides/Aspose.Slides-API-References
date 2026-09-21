---
title: to_jpeg method
second_title: Aspose.Slides for Python द्वारा .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.lowcode/convert/to_jpeg/
weight: 20
---
## to_jpeg(pres, output_file_name) {#presentation-str}
इनपुट प्रस्तुतिकरण को JPEG फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है।  
यदि आउटपुट फ़ाइल नाम "myPath/myFilename.jpeg" के रूप में दिया जाता है, तो परिणाम "myPath/myFilename_N.jpeg" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड संख्या है।


```python
@staticmethod
def to_jpeg(pres, output_file_name):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/hi/aspose.slides/presentation) | इनपुट प्रस्तुतिकरण। |
| output_file_name | **str** | आउटपुट फ़ाइल नाम। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, image_size) {#presentation-str-asposepydrawingsize}
इनपुट प्रस्तुतिकरण को JPEG फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है।  
यदि आउटपुट फ़ाइल नाम "myPath/myFilename.jpeg" के रूप में दिया जाता है, तो परिणाम "myPath/myFilename_N.jpeg" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड संख्या है।


```python
@staticmethod
def to_jpeg(pres, output_file_name, image_size):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/hi/aspose.slides/presentation) | इनपुट प्रस्तुतिकरण |
| output_file_name | **str** | आउटपुट फ़ाइल नाम। |
| image_size | **aspose.slides.Size** | प्रत्येक उत्पन्न छवि का आकार। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
इनपुट प्रस्तुतिकरण को JPEG फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है।  
यदि आउटपुट फ़ाइल नाम "myPath/myFilename.jpeg" के रूप में दिया जाता है, तो परिणाम "myPath/myFilename_N.jpeg" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड संख्या है।


```python
@staticmethod
def to_jpeg(pres, output_file_name, scale, options):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/hi/aspose.slides/presentation) | इनपुट प्रस्तुतिकरण। |
| output_file_name | **str** | आउटपुट फ़ाइल नाम। |
| scale | **float** | मूल स्लाइड आकार की तुलना में आउटपुट छवियों पर लागू स्केलिंग फ़ैक्टर। |
| options | [`IRenderingOptions`](/slides/python-net/hi/aspose.slides.export/irenderingoptions) | रेंडरिंग विकल्प। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### संबंधित देखें
* क्लास [`Convert`](/slides/python-net/hi/aspose.slides.lowcode/convert)
* क्लास [`IRenderingOptions`](/slides/python-net/hi/aspose.slides.export/irenderingoptions)
* क्लास [`Presentation`](/slides/python-net/hi/aspose.slides/presentation)
* मॉड्यूल [`aspose.slides.lowcode`](/slides/python-net/hi/aspose.slides.lowcode)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)