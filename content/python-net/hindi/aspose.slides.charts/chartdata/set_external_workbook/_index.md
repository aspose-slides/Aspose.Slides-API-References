---
title: set_external_workbook method
second_title: Aspose.Slides for Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/chartdata/set_external_workbook/
weight: 30
---
## set_external_workbook(self, workbook_path) {#str}
बाहरी कार्यपत्रक को चार्ट के डेटा स्रोत के रूप में सेट करता है। चार्ट डेटा लक्ष्य कार्यपत्रक से अपडेट किया जाएगा।


```python
def set_external_workbook(self, workbook_path):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| workbook_path | **str** | लक्ष्य कार्यपत्रक का पथ |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | बाहरी कार्यपत्रक उपलब्ध नहीं है या लोड नहीं किया जा सकता। |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
बाहरी कार्यपत्रक को चार्ट के डेटा स्रोत के रूप में सेट करता है।


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| workbook_path | **str** | लक्ष्य कार्यपत्रक का पथ |
| update_chart_data | **bool** | यदि मान false है तो केवल कार्यपत्रक पथ अपडेट किया जाएगा। <br/><br/>             चार्ट डेटा लक्ष्य कार्यपत्रक से लोड और अपडेट नहीं किया जाएगा। इसका उपयोग तब किया जा सकता है जब लक्ष्य कार्यपत्रक मौजूद न हो या उपलब्ध न हो।<br/><br/>             यदि मान true है तो चार्ट डेटा लक्ष्य कार्यपत्रक से अपडेट किया जाएगा। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | बाहरी कार्यपत्रक उपलब्ध नहीं है या लोड नहीं किया जा सकता। |



### और देखें
* क्लास [`ChartData`](/slides/python-net/hi/aspose.slides.charts/chartdata)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)