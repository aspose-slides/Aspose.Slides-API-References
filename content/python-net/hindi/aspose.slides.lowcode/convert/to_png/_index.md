---
title: to_png method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.lowcode/convert/to_png/
weight: 40
---
## to_png(pres, output_file_name) {#presentation-str}
इनपुट प्रस्तुति को PNG फ़ॉर्मेट छवियों के सेट में बदलता है।  
            यदि आउटपुट फ़ाइल नाम को "myPath/myFilename.png" दिया जाता है, 
            तो परिणाम "myPath/myFilename_N.png" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड संख्या है।


```python
@staticmethod
def to_png(pres, output_file_name):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/hi/aspose.slides/presentation) | इनपुट प्रस्तुति। |
| output_file_name | **str** | आउटपुट फ़ाइल नाम। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, image_size) {#presentation-str-asposepydrawingsize}
इनपुट प्रस्तुति को PNG फ़ॉर्मेट छवियों के सेट में बदलता है।  
            यदि आउटपुट फ़ाइल नाम को "myPath/myFilename.png" दिया जाता है, 
            तो परिणाम "myPath/myFilename_N.png" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड संख्या है।


```python
@staticmethod
def to_png(pres, output_file_name, image_size):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/hi/aspose.slides/presentation) | इनपुट प्रस्तुति |
| output_file_name | **str** | आउटपुट फ़ाइल नाम। |
| image_size | **aspose.slides.Size** | प्रत्येक उत्पन्न छवि का आकार। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
इनपुट प्रस्तुति को PNG फ़ॉर्मेट छवियों के सेट में बदलता है।  
            यदि आउटपुट फ़ाइल नाम को "myPath/myFilename.png" दिया जाता है, 
            तो परिणाम "myPath/myFilename_N.png" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड संख्या है।


```python
@staticmethod
def to_png(pres, output_file_name, scale, options):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/hi/aspose.slides/presentation) | इनपुट प्रस्तुति। |
| output_file_name | **str** | आउटपुट फ़ाइल नाम। |
| scale | **float** | मूल स्लाइड आकार के सापेक्ष आउटपुट छवियों पर लागू स्केलिंग कारक। |
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
* library [`Aspose.Slides`](/slides/python-net)