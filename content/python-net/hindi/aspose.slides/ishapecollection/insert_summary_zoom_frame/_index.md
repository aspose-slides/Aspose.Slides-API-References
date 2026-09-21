---
title: insert_summary_zoom_frame method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ishapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
एक नया Summary Zoom फ्रेम बनाता है और इसे निर्दिष्ट सूचकांक पर shape संग्रह में सम्मिलित करता है।

### रिटर्न
नया निर्मित [`ISummaryZoomFrame`](/slides/python-net/hi/aspose.slides/isummaryzoomframe)।

```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | शून्य-आधारित सूचकांक जहाँ Summary Zoom फ्रेम को सम्मिलित किया जाता है। |
| x | **float** | नए Summary Zoom फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | **float** | नए Summary Zoom फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | **float** | नए Summary Zoom फ्रेम की चौड़ाई, पॉइंट में। |
| height | **float** | नए Summary Zoom फ्रेम की ऊँचाई, पॉइंट में। |

### टिप्पणी
यह मेथड एक Summary Zoom फ्रेम बनाता है जो प्रस्तुति में सभी अनुभागों के सारांश लिंक को समेकित करता है।

### अपवाद
| अपवाद | विवरण |
| :- | :- |
| [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception) | यदि प्रस्तुति में कोई अनुभाग नहीं है, या लक्ष्य स्लाइड किसी भी अनुभाग से संबंधित नहीं है, तो फेंका जाता है। |

### देखें
* क्लास [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection)
* क्लास [`ISummaryZoomFrame`](/slides/python-net/hi/aspose.slides/isummaryzoomframe)
* क्लास [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)