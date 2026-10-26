---
title: add_zoom_frame method
second_title: Aspose.Slides के लिए Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/shapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
एक नया Zoom फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है।

### वापसी
नया बनाया गया [`IZoomFrame`](/slides/python-net/hi/aspose.slides/izoomframe)।

```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | नए Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |
| slide | [`ISlide`](/slides/python-net/hi/aspose.slides/islide) | Zoom फ्रेम द्वारा संदर्भित [`ISlide`](/slides/python-net/hi/aspose.slides/islide); <br/><br/> यह प्रस्तुति का हिस्सा होना चाहिए। |

### अपवाद

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | यदि संदर्भित स्लाइड वर्तमान प्रस्तुति का हिस्सा नहीं है तो फेंका जाता है। |

## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
एक नया Zoom फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है।

### वापसी
नया बनाया गया [`IZoomFrame`](/slides/python-net/hi/aspose.slides/izoomframe)।

```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | नए Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |
| slide | [`ISlide`](/slides/python-net/hi/aspose.slides/islide) | Zoom फ्रेम द्वारा संदर्भित [`ISlide`](/slides/python-net/hi/aspose.slides/islide); <br/><br/> यह प्रस्तुति का हिस्सा होना चाहिए। |
| image | [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage) | संदर्भित स्लाइड [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage) के लिए चित्र। |

### अपवाद

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | यदि संदर्भित स्लाइड वर्तमान प्रस्तुति का हिस्सा नहीं है तो फेंका जाता है। |

### देखें

* वर्ग [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage)
* वर्ग [`ISlide`](/slides/python-net/hi/aspose.slides/islide)
* वर्ग [`IZoomFrame`](/slides/python-net/hi/aspose.slides/izoomframe)
* वर्ग [`ShapeCollection`](/slides/python-net/hi/aspose.slides/shapecollection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)