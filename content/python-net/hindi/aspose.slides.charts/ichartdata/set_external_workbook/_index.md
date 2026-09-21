---
title: set_external_workbook method
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/ichartdata/set_external_workbook/
weight: 30
---
## set_external_workbook(self, workbook_path) {#str}
बाहरी वर्कबुक को चार्ट के डेटा स्रोत के रूप में सेट करता है। चार्ट डेटा लक्ष्य वर्कबुक से अपडेट किया जाएगा।


```python
def set_external_workbook(self, workbook_path):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| workbook_path | **str** | लक्ष्य वर्कबुक का पाथ |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | External workbook is not available or can't be loaded. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
बाहरी वर्कबुक को चार्ट के डेटा स्रोत के रूप में सेट करता है।


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| workbook_path | **str** | लक्ष्य वर्कबुक का पाथ |
| update_chart_data | **bool** | यदि मान false है तो केवल वर्कबुक पाथ अपडेट होगा। <br/><br/>             चार्ट डेटा लक्ष्य वर्कबुक से लोड या अपडेट नहीं होगा। इसे तब उपयोग किया जा सकता है जब लक्ष्य वर्कबुक मौजूद नहीं है या उपलब्ध नहीं है।<br/><br/>             यदि मान true है तो चार्ट डेटा लक्ष्य वर्कबुक से अपडेट किया जाएगा। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | External workbook is not available or can't be loaded. |



### संबंधित देखें
* क्लास [`IChartData`](/slides/python-net/hi/aspose.slides.charts/ichartdata)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लायब्ररी [`Aspose.Slides`](/slides/python-net)