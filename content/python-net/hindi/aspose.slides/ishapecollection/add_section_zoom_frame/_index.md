---
title: add_section_zoom_frame method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ishapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
एक नया Section Zoom फ्रेम बनाता है और उसे shape संग्रह के अंत में जोड़ता है।

### रिटर्न

नया बनाया गया [`ISectionZoomFrame`](/slides/python-net/hi/aspose.slides/isectionzoomframe)।

```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | **float** | नए Section Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए Section Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए Section Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए Section Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |
| section | [`ISection`](/slides/python-net/hi/aspose.slides/isection) | Section Zoom फ्रेम द्वारा संदर्भित [`ISection`](/slides/python-net/hi/aspose.slides/isection); <br/><br/>must belong to this presentation and contain at least one slide. |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | यदि संदर्भित सेक्शन वर्तमान प्रस्तुति से संबंधित नहीं है या उसमें कोई स्लाइड नहीं है तो यह अपवाद फेंका जाता है। |


## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
एक पूर्वनिर्धारित इमेज के साथ नया Section Zoom फ्रेम बनाता है और उसे shape संग्रह के अंत में जोड़ता है।

### रिटर्न

नया बनाया गया [`ISectionZoomFrame`](/slides/python-net/hi/aspose.slides/isectionzoomframe)।

```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | **float** | नए Section Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए Section Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए Section Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए Section Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |
| section | [`ISection`](/slides/python-net/hi/aspose.slides/isection) | Section Zoom फ्रेम द्वारा संदर्भित [`ISection`](/slides/python-net/hi/aspose.slides/isection); <br/><br/>must belong to this presentation and contain at least one slide. |
| image | [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage) | Section Zoom फ्रेम के भीतर प्रदर्शित करने के लिए [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage)। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | यदि संदर्भित सेक्शन वर्तमान प्रस्तुति से संबंधित नहीं है या उसमें कोई स्लाइड नहीं है तो यह अपवाद फेंका जाता है। |



### देखें
* क्लास [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage)
* क्लास [`ISection`](/slides/python-net/hi/aspose.slides/isection)
* क्लास [`ISectionZoomFrame`](/slides/python-net/hi/aspose.slides/isectionzoomframe)
* क्लास [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)