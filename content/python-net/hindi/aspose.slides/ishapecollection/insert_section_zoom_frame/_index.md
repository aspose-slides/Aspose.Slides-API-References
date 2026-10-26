---
title: insert_section_zoom_frame method
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ishapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
एक नया Section Zoom फ्रेम बनाता है और इसे निर्दिष्ट इंडेक्स पर shape संग्रह में जोड़ता है।

### रिटर्न्स

नया बनाया गया [`ISectionZoomFrame`](/slides/python-net/hi/aspose.slides/isectionzoomframe)।

```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | वह शून्य-आधारित इंडेक्स जहाँ Section Zoom फ्रेम को सम्मिलित किया जाना है। |
| x | **float** | नए Section Zoom फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | **float** | नए Section Zoom फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | **float** | नए Section Zoom फ्रेम की चौड़ाई, पॉइंट में। |
| height | **float** | नए Section Zoom फ्रेम की ऊँचाई, पॉइंट में। |
| section | [`ISection`](/slides/python-net/hi/aspose.slides/isection) | Section Zoom फ्रेम द्वारा संदर्भित [`ISection`](/slides/python-net/hi/aspose.slides/isection);<br/><br/> यह इस प्रस्तुति का हिस्सा होना चाहिए और कम से कम एक स्लाइड होना आवश्यक है। |

### अपवाद

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | यदि संदर्भित सेक्शन वर्तमान प्रस्तुति का हिस्सा नहीं है या उसमें कोई स्लाइड नहीं है तो फेंका जाता है। |

## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
पूर्वनिर्धारित छवि के साथ एक नया Section Zoom फ्रेम बनाता है और इसे निर्दिष्ट इंडेक्स पर shape संग्रह में जोड़ता है।

### रिटर्न्स

नया बनाया गया [`ISectionZoomFrame`](/slides/python-net/hi/aspose.slides/isectionzoomframe)।

```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | वह शून्य-आधारित इंडेक्स जहाँ Section Zoom फ्रेम को सम्मिलित किया जाना है। |
| x | **float** | नए Section Zoom फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | **float** | नए Section Zoom फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | **float** | नए Section Zoom फ्रेम की चौड़ाई, पॉइंट में। |
| height | **float** | नए Section Zoom फ्रेम की ऊँचाई, पॉइंट में। |
| section | [`ISection`](/slides/python-net/hi/aspose.slides/isection) | Section Zoom फ्रेम द्वारा संदर्भित [`ISection`](/slides/python-net/hi/aspose.slides/isection);<br/><br/> यह इस प्रस्तुति का हिस्सा होना चाहिए और कम से कम एक स्लाइड होना आवश्यक है। |
| image | [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage) | Section Zoom फ्रेम के भीतर प्रदर्शित की जाने वाली छवि। |

### अपवाद

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | यदि संदर्भित सेक्शन वर्तमान प्रस्तुति का हिस्सा नहीं है या उसमें कोई स्लाइड नहीं है तो फेंका जाता है। |

### संबंधित देखें
* क्लास [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage)
* क्लास [`ISection`](/slides/python-net/hi/aspose.slides/isection)
* क्लास [`ISectionZoomFrame`](/slides/python-net/hi/aspose.slides/isectionzoomframe)
* क्लास [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)