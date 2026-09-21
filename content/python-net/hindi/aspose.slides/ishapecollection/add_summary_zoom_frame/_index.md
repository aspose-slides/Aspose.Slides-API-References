---
title: add_summary_zoom_frame method
second_title: Aspose.Slides के लिए Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ishapecollection/add_summary_zoom_frame/
weight: 140
---
## add_summary_zoom_frame(self, x, y, width, height) {#float-float-float-float}
एक नया Summary Zoom फ़्रेम बनाता है और उसे shape संग्रह के अंत में जोड़ता है।

### Returns

नया बना हुआ [`ISummaryZoomFrame`](/slides/python-net/hi/aspose.slides/isummaryzoomframe).



```python
def add_summary_zoom_frame(self, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | नए Summary Zoom फ़्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए Summary Zoom फ़्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए Summary Zoom फ़्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए Summary Zoom फ़्रेम की ऊँचाई, पॉइंट्स में। |

### Remarks

यह मेथड एक Summary Zoom फ़्रेम बनाता है जो प्रस्तुति के सभी अनुभागों के सारांश लिंक को एकत्र करता है।

### Exceptions

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception) | यदि प्रस्तुति में कोई अनुभाग नहीं है, या लक्षित स्लाइड किसी भी अनुभाग से संबंधित नहीं है, तो यह फेंका जाता है। |



### See Also
* क्लास [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection)
* क्लास [`ISummaryZoomFrame`](/slides/python-net/hi/aspose.slides/isummaryzoomframe)
* क्लास [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)