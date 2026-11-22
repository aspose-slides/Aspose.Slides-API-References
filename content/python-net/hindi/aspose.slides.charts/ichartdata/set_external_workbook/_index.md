---
title: set_external_workbook method
second_title: Aspose.Slides Python के लिए .NET के माध्यम से API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/ichartdata/set_external_workbook/
weight: 40
---
## set_external_workbook(self, workbook_path) {#str}
चार्ट के लिए बाहरी वर्कबुक को डेटा स्रोत के रूप में सेट करता है। चार्ट डेटा लक्ष्य वर्कबुक से अपडेट होगा।


```python
def set_external_workbook(self, workbook_path):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| workbook_path | **str** | लक्ष्य वर्कबुक का पथ |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | बाहरी वर्कबुक उपलब्ध नहीं है या लोड नहीं किया जा सकता। |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
चार्ट के लिए बाहरी वर्कबुक को डेटा स्रोत के रूप में सेट करता है।


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| workbook_path | **str** | लक्ष्य वर्कबुक का पथ |
| update_chart_data | **bool** | यदि मान false है तो केवल वर्कबुक पथ अपडेट होगा। <br/><br/>             चार्ट डेटा लोड नहीं होगा और लक्ष्य वर्कबुक से अपडेट नहीं होगा। इसे तब उपयोग किया जा सकता है जब लक्ष्य वर्कबुक मौजूद न हो या उपलब्ध न हो।<br/><br/>             यदि मान true है तो चार्ट डेटा लक्ष्य वर्कबुक से अपडेट होगा। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | बाहरी वर्कबुक उपलब्ध नहीं है या लोड नहीं किया जा सकता। |



### देखें भी
* क्लास [`IChartData`](/slides/python-net/hi/aspose.slides.charts/ichartdata)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)