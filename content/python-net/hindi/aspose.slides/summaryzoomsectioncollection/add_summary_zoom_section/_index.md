---
title: add_summary_zoom_section method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/summaryzoomsectioncollection/add_summary_zoom_section/
weight: 10
---
## add_summary_zoom_section(self, section) {#isection}
नया Summary Zoom Section ऑब्जेक्ट बनाता है और इसे संग्रह में जोड़ता है

### Returns
जोड़ा गया [`ISummaryZoomFrame`](/slides/python-net/hi/aspose.slides/isummaryzoomframe) तत्व



```python
def add_summary_zoom_section(self, section):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| section | [`ISection`](/slides/python-net/hi/aspose.slides/isection) | नए Summary Zoom Section तत्व [`ISection`](/slides/python-net/hi/aspose.slides/isection) के लिए सेक्शन |

### Remarks
यदि इस सेक्शन के लिये संग्रह में पहले से कोई तत्व मौजूद है, तो मौजूदा तत्व लौटाया जाता है।

### Exceptions
| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | संदर्भित सेक्शन वर्तमान प्रस्तुति से संबंधित नहीं है या इसमें कोई स्लाइड नहीं है। |



### See Also
* वर्ग [`ISection`](/slides/python-net/hi/aspose.slides/isection)
* वर्ग [`ISummaryZoomFrame`](/slides/python-net/hi/aspose.slides/isummaryzoomframe)
* वर्ग [`ISummaryZoomSection`](/slides/python-net/hi/aspose.slides/isummaryzoomsection)
* वर्ग [`SummaryZoomSectionCollection`](/slides/python-net/hi/aspose.slides/summaryzoomsectioncollection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)