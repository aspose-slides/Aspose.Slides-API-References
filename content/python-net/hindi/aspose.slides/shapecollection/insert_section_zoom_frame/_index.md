---
title: insert_section_zoom_frame method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/shapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
नया Section Zoom फ्रेम बनाता है और उसे निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है।

### रिटर्न वैल्यू

नया बनाया गया [`ISectionZoomFrame`](/slides/python-net/hi/aspose.slides/isectionzoomframe).

```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | शून्य-आधारित इंडेक्स जहाँ Section Zoom फ्रेम को सम्मिलित किया जाना है। |
| x | **float** | नए Section Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए Section Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए Section Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए Section Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |
| section | [`ISection`](/slides/python-net/hi/aspose.slides/isection) | Section Zoom फ्रेम द्वारा संदर्भित [`ISection`](/slides/python-net/hi/aspose.slides/isection);<br/><br/> यह इस प्रस्तुति का हिस्सा होना चाहिए और कम से कम एक स्लाइड शामिल करनी चाहिए। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | यदि संदर्भित सेक्शन वर्तमान प्रस्तुति का हिस्सा नहीं है या उसमें कोई स्लाइड नहीं है तो यह फेंका जाता है। |

## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
पूर्वनिर्धारित छवि के साथ नया Section Zoom फ्रेम बनाता है और उसे निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है।

### रिटर्न वैल्यू

नया बनाया गया [`ISectionZoomFrame`](/slides/python-net/hi/aspose.slides/isectionzoomframe).

```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | शून्य-आधारित इंडेक्स जहाँ Section Zoom फ्रेम को सम्मिलित किया जाना है। |
| x | **float** | नए Section Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए Section Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए Section Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए Section Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |
| section | [`ISection`](/slides/python-net/hi/aspose.slides/isection) | Section Zoom फ्रेम द्वारा संदर्भित [`ISection`](/slides/python-net/hi/aspose.slides/isection); <br/><br/> यह इस प्रस्तुति का हिस्सा होना चाहिए और कम से कम एक स्लाइड शामिल करनी चाहिए। |
| image | [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage) | Section Zoom फ्रेम के भीतर प्रदर्शित करने के लिए छवि। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | यदि संदर्भित सेक्शन वर्तमान प्रस्तुति का हिस्सा नहीं है या उसमें कोई स्लाइड नहीं है तो यह फेंका जाता है। |

### देखें

* क्लास [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage)
* क्लास [`ISection`](/slides/python-net/hi/aspose.slides/isection)
* क्लास [`ISectionZoomFrame`](/slides/python-net/hi/aspose.slides/isectionzoomframe)
* क्लास [`ShapeCollection`](/slides/python-net/hi/aspose.slides/shapecollection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)