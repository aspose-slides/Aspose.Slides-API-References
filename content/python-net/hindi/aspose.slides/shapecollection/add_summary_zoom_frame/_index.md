---
title: add_summary_zoom_frame method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/shapecollection/add_summary_zoom_frame/
weight: 140
---
## add_summary_zoom_frame(self, x, y, width, height) {#float-float-float-float}
एक नया Summary Zoom फ्रेम बनाता है और इसे shape संग्रह के अंत में जोड़ता है।

### रिटर्न
नया बनाया गया [`ISummaryZoomFrame`](/slides/python-net/hi/aspose.slides/isummaryzoomframe)।

```python
def add_summary_zoom_frame(self, x, y, width, height):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | **float** | नया Summary Zoom फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | **float** | नया Summary Zoom फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | **float** | नया Summary Zoom फ्रेम की चौड़ाई, पॉइंट में। |
| height | **float** | नया Summary Zoom फ्रेम की ऊँचाई, पॉइंट में। |

### टिप्पणियाँ
यह मेथड एक नया Summary Zoom बनाता है और इस प्रस्तुति के सभी सेक्शन के लिए उसमें ऑब्जेक्ट्स का संग्रह रखता है।

### अपवाद
| अपवाद | विवरण |
| :- | :- |
| [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception) | यदि प्रस्तुति में कोई सेक्शन नहीं है, या लक्ष्य स्लाइड किसी भी सेक्शन से संबंधित नहीं है, तो थ्रो किया जाता है। |

### संबंधित देखें
* वर्ग [`ISummaryZoomFrame`](/slides/python-net/hi/aspose.slides/isummaryzoomframe)
* वर्ग [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception)
* वर्ग [`ShapeCollection`](/slides/python-net/hi/aspose.slides/shapecollection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)