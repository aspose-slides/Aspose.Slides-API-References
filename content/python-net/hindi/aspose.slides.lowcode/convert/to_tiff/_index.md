---
title: to_tiff method
second_title: Aspose.Slides for Python के लिये .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.lowcode/convert/to_tiff/
weight: 60
---
## to_tiff(pres, output_file_name) {#presentation-str}
इनपुट प्रस्तुति को TIFF फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है।  
यदि आउटपुट फ़ाइल नाम "myPath/myFilename.tiff" के रूप में दिया जाता है, तो परिणाम "myPath/myFilename_N.tiff" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड संख्या है।

```python
@staticmethod
def to_tiff(pres, output_file_name):
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

## to_tiff(pres, output_file_name, options, multipage) {#presentation-str-asposeslidesexportitiffoptions-bool}
कस्टम विकल्पों के साथ इनपुट प्रस्तुति को TIFF फ़ॉर्मेट में परिवर्तित करता है।  
यदि आउटपुट फ़ाइल नाम "myPath/myFilename.tiff" के रूप में दिया जाता है और `multipage` `false` है, तो परिणाम "myPath/myFilename_N.tiff" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड संख्या है।  
अन्यथा, यदि `multipage` `true` है, तो परिणाम एक मल्टी-पेज "myPath/myFilename.tiff" दस्तावेज़ होगा।

```python
@staticmethod
def to_tiff(pres, output_file_name, options, multipage):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/hi/aspose.slides/presentation) | इनपुट प्रस्तुति। |
| output_file_name | **str** | आउटपुट फ़ाइल नाम। |
| options | [`ITiffOptions`](/slides/python-net/hi/aspose.slides.export/itiffoptions) | TIFF सहेजने के विकल्प। |
| multipage | **bool** | यह निर्दिष्ट करता है कि उत्पन्न TIFF दस्तावेज़ मल्टी-पेज होना चाहिए या नहीं। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

### और देखें
* वर्ग [`Convert`](/slides/python-net/hi/aspose.slides.lowcode/convert)
* वर्ग [`ITiffOptions`](/slides/python-net/hi/aspose.slides.export/itiffoptions)
* वर्ग [`Presentation`](/slides/python-net/hi/aspose.slides/presentation)
* मॉड्यूल [`aspose.slides.lowcode`](/slides/python-net/hi/aspose.slides.lowcode)
* पुस्तकालय [`Aspose.Slides`](/slides/python-net)