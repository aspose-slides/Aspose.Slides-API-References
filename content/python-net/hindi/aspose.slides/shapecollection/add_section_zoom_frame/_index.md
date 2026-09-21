---
title: add_section_zoom_frame method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/shapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
नए Section Zoom फ्रेम को बनाता है और इसे shape संग्रह के अंत में जोड़ता है।

### Returns
नया बनाया गया [`ISectionZoomFrame`](/slides/python-net/hi/aspose.slides/isectionzoomframe)।

```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| x | **float** | नए Section Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए Section Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए Section Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए Section Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |
| section | [`ISection`](/slides/python-net/hi/aspose.slides/isection) | Section Zoom फ्रेम द्वारा संदर्भित [`ISection`](/slides/python-net/hi/aspose.slides/isection); यह प्रस्तुति से संबंधित होना चाहिए और कम से कम एक स्लाइड शामिल करनी चाहिए। |

### Exceptions
| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | यदि संदर्भित सेक्शन वर्तमान प्रस्तुतीकरण से संबंधित नहीं है या इसमें कोई स्लाइड नहीं है तो थ्रो किया जाता है। |

## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
प्रीडिफाइंड इमेज के साथ नया Section Zoom फ्रेम बनाता है और इसे shape संग्रह के अंत में जोड़ता है।

### Returns
नया बनाया गया [`ISectionZoomFrame`](/slides/python-net/hi/aspose.slides/isectionzoomframe)।

```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| x | **float** | नए Section Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए Section Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए Section Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए Section Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |
| section | [`ISection`](/slides/python-net/hi/aspose.slides/isection) | Section Zoom फ्रेम द्वारा संदर्भित [`ISection`](/slides/python-net/hi/aspose.slides/isection); यह प्रस्तुति से संबंधित होना चाहिए और कम से कम एक स्लाइड शामिल करनी चाहिए। |
| image | [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage) | Section Zoom फ्रेम के भीतर प्रदर्शित करने के लिए [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage)। |

### Exceptions
| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | यदि संदर्भित सेक्शन वर्तमान प्रस्तुतीकरण से संबंधित नहीं है या इसमें कोई स्लाइड नहीं है तो थ्रो किया जाता है। |

### See Also
* क्लास [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage)
* क्लास [`ISection`](/slides/python-net/hi/aspose.slides/isection)
* क्लास [`ISectionZoomFrame`](/slides/python-net/hi/aspose.slides/isectionzoomframe)
* क्लास [`ShapeCollection`](/slides/python-net/hi/aspose.slides/shapecollection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)