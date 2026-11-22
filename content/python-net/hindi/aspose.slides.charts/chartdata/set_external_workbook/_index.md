---
title: set_external_workbook method
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/chartdata/set_external_workbook/
weight: 40
---
## set_external_workbook(self, workbook_path) {#str}
बाहरी वर्कबुक को चार्ट के डेटा स्रोत के रूप में सेट करता है। चार्ट डेटा लक्ष्य वर्कबुक से अपडेट किया जाएगा।


```python
def set_external_workbook(self, workbook_path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| workbook_path | **str** | लक्ष्य वर्कबुक का पथ |

### अपवाद

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | बाहरी वर्कबुक उपलब्ध नहीं है या लोड नहीं किया जा सकता। |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
बाहरी वर्कबुक को चार्ट के डेटा स्रोत के रूप में सेट करता है।


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| workbook_path | **str** | लक्ष्य वर्कबुक का पथ |
| update_chart_data | **bool** | यदि मान false है तो केवल वर्कबुक पथ अपडेट किया जाएगा। <br/><br/>             चार्ट डेटा लक्ष्य वर्कबुक से लोड या अपडेट नहीं किया जाएगा। यह तब उपयोग किया जा सकता है जब लक्ष्य वर्कबुक मौजूद नहीं हो या उपलब्ध न हो।<br/><br/>             यदि मान true है तो चार्ट डेटा लक्ष्य वर्कबुक से अपडेट किया जाएगा। |

### अपवाद

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | बाहरी वर्कबुक उपलब्ध नहीं है या लोड नहीं किया जा सकता। |



### संबंधित देखें
* क्लास [`ChartData`](/slides/python-net/hi/aspose.slides.charts/chartdata)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)