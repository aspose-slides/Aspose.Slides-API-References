---
title: insert_summary_zoom_frame method
second_title: Aspose.Slides Python के लिए .NET के जरिए API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/shapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
एक नया Summary Zoom फ़्रेम बनाता है और इसे निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है।

### रिटर्न वैल्यू

नया बनाया गया [`ISummaryZoomFrame`](/slides/python-net/hi/aspose.slides/isummaryzoomframe).



```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | शून्य-आधारित इंडेक्स जहाँ Summary Zoom फ़्रेम सम्मिलित किया जाता है। |
| x | **float** | नए Summary Zoom फ़्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए Summary Zoom फ़्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए Summary Zoom फ़्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए Summary Zoom फ़्रेम की ऊँचाई, पॉइंट्स में। |

### टिप्पणियाँ

यह मेथड एक Summary Zoom फ़्रेम बनाता है जो प्रस्तुति के सभी सेक्शन के लिए सारांश लिंक को एकत्रित करता है।

### अपवाद

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception) | यदि प्रस्तुति में कोई सेक्शन नहीं है, या लक्ष्य स्लाइड किसी भी सेक्शन से संबंधित नहीं है, तो यह फेंका जाता है। |



### संबंधित देखें
* क्लास [`ISummaryZoomFrame`](/slides/python-net/hi/aspose.slides/isummaryzoomframe)
* क्लास [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception)
* क्लास [`ShapeCollection`](/slides/python-net/hi/aspose.slides/shapecollection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)