---
title: add_zoom_frame method
second_title: Aspose.Slides for Python द्वारा .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ishapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
एक नया Zoom फ्रेम बनाता है और इसे शेप संग्रह के अंत में जोड़ता है।

### वापसी

नया बनाया गया [`IZoomFrame`](/slides/python-net/hi/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | **float** | नए Zoom फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | **float** | नए Zoom फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | **float** | नए Zoom फ्रेम की चौड़ाई, पॉइंट में। |
| height | **float** | नए Zoom फ्रेम की ऊँचाई, पॉइंट में। |
| slide | [`ISlide`](/slides/python-net/hi/aspose.slides/islide) | Zoom फ्रेम द्वारा संदर्भित [`ISlide`](/slides/python-net/hi/aspose.slides/islide);<br/><br/>यह वर्तमान प्रस्तुति से संबंधित होना चाहिए। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | यदि संदर्भित स्लाइड वर्तमान प्रस्तुति से संबंधित नहीं है तो फेंका जाता है। |


## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
एक नया Zoom फ्रेम बनाता है और इसे शेप संग्रह के अंत में जोड़ता है।

### वापसी

नया बनाया गया [`IZoomFrame`](/slides/python-net/hi/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | **float** | नए Zoom फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | **float** | नए Zoom फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | **float** | नए Zoom फ्रेम की चौड़ाई, पॉइंट में। |
| height | **float** | नए Zoom फ्रेम की ऊँचाई, पॉइंट में। |
| slide | [`ISlide`](/slides/python-net/hi/aspose.slides/islide) | Zoom फ्रेम द्वारा संदर्भित [`ISlide`](/slides/python-net/hi/aspose.slides/islide);<br/><br/>यह वर्तमान प्रस्तुति से संबंधित होना चाहिए। |
| image | [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage) | संदर्भित स्लाइड [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage) के लिए छवि। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | यदि संदर्भित स्लाइड वर्तमान प्रस्तुति से संबंधित नहीं है तो फेंका जाता है। |



### संबंधित देखें
* क्लास [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage)
* क्लास [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection)
* क्लास [`ISlide`](/slides/python-net/hi/aspose.slides/islide)
* क्लास [`IZoomFrame`](/slides/python-net/hi/aspose.slides/izoomframe)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)