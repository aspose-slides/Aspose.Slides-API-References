---
title: to_png method
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.lowcode/convert/to_png/
weight: 40
---
## to_png(pres, output_file_name) {#presentation-str}
इनपुट प्रस्तुति को PNG फ़ॉर्मेट छवियों के सेट में परिवर्तित करता है।  
यदि आउटपुट फ़ाइल नाम "myPath/myFilename.png" दिया गया हो, तो परिणाम "myPath/myFilename_N.png" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड संख्या है।

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

## to_png(pres, output_file_name, image_size) {#presentation-str-asposeslidessize}
इनपुट प्रस्तुति को PNG फ़ॉर्मेट छवियों के सेट में परिवर्तित करता है।  
यदि आउटपुट फ़ाइल नाम "myPath/myFilename.png" दिया गया हो, तो परिणाम "myPath/myFilename_N.png" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड संख्या है।

```python
@staticmethod
def to_png(pres, output_file_name, image_size):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/hi/aspose.slides/presentation) | इनपुट प्रस्तुति |
| output_file_name | **str** | आउटपुट फ़ाइल नाम। |
| image_size | [`Size`](/slides/python-net/hi/aspose.slides/size) | प्रत्येक उत्पन्न छवि का आकार। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

## to_png(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
इनपुट प्रस्तुति को PNG फ़ॉर्मेट छवियों के सेट में परिवर्तित करता है।  
यदि आउटपुट फ़ाइल नाम "myPath/myFilename.png" दिया गया हो, तो परिणाम "myPath/myFilename_N.png" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड संख्या है।

```python
@staticmethod
def to_png(pres, output_file_name, scale, options):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/hi/aspose.slides/presentation) | इनपुट प्रस्तुति। |
| output_file_name | **str** | आउटपुट फ़ाइल नाम। |
| scale | **float** | मूल स्लाइड आकार के सापेक्ष आउटपुट छवियों पर लागू स्केलिंग फैक्टर। |
| options | [`IRenderingOptions`](/slides/python-net/hi/aspose.slides.export/irenderingoptions) | रेंडरिंग विकल्प। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

### देखें भी
* कक्षा [`Convert`](/slides/python-net/hi/aspose.slides.lowcode/convert)
* कक्षा [`IRenderingOptions`](/slides/python-net/hi/aspose.slides.export/irenderingoptions)
* कक्षा [`Presentation`](/slides/python-net/hi/aspose.slides/presentation)
* कक्षा [`Size`](/slides/python-net/hi/aspose.slides/size)
* मॉड्यूल [`aspose.slides.lowcode`](/slides/python-net/hi/aspose.slides.lowcode)
* library [`Aspose.Slides`](/slides/python-net)