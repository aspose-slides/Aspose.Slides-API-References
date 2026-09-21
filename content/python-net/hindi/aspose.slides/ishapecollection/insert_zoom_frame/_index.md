---
title: insert_zoom_frame method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ishapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
एक नया Zoom फ्रेम बनाता है और उसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है।

### Returns

नया बनाया गया [`IZoomFrame`](/slides/python-net/hi/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | शून्य-आधारित सूचकांक जहाँ Zoom फ्रेम सम्मिलित किया जाना है। |
| x | **float** | नए Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |
| slide | [`ISlide`](/slides/python-net/hi/aspose.slides/islide) | Zoom फ्रेम द्वारा संदर्भित [`ISlide`](/slides/python-net/hi/aspose.slides/islide)। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | यदि संदर्भित स्लाइड वर्तमान प्रस्तुति का हिस्सा नहीं है तो फेंका जाता है। |


## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
एक पूर्वनिर्धारित छवि के साथ नया Zoom फ्रेम बनाता है और उसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है।

### Returns

नया बनाया गया [`IZoomFrame`](/slides/python-net/hi/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | शून्य-आधारित सूचकांक जहाँ Zoom फ्रेम सम्मिलित किया जाना है। |
| x | **float** | नए Zoom फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए Zoom फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए Zoom फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए Zoom फ्रेम की ऊँचाई, पॉइंट्स में। |
| slide | [`ISlide`](/slides/python-net/hi/aspose.slides/islide) | Zoom फ्रेम द्वारा संदर्भित [`ISlide`](/slides/python-net/hi/aspose.slides/islide)। |
| image | [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage) | संदर्भित स्लाइड [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage) के लिए छवि। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | यदि संदर्भित स्लाइड वर्तमान प्रस्तुति का हिस्सा नहीं है तो फेंका जाता है। |



### संबंधित देखें
* क्लास [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage)
* क्लास [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection)
* क्लास [`ISlide`](/slides/python-net/hi/aspose.slides/islide)
* क्लास [`IZoomFrame`](/slides/python-net/hi/aspose.slides/izoomframe)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)