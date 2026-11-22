---
title: refresh_data method
second_title: Aspose.Slides Python के लिए .NET API संदर्भ के माध्यम से
description: 
type: docs
url: /hi/aspose.slides.charts/ichartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
चार्ट डेटा को स्रोत वर्कबुक से पुनः लोड करके रीफ़्रेश करता है।

```python
def refresh_data(self):
    ...
```

### टिप्पणियाँ
यदि चार्ट बाहरी वर्कबुक का उपयोग करता है, तो कॉल के समय वर्कबुक सुलभ होना चाहिए।

### अपवाद
| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | जब वर्कबुक फ़ॉर्मेट समर्थित नहीं होता है, या जब [`IChartData.data_source_type`](/slides/python-net/hi/aspose.slides.charts/ichartdata/data_source_type) है<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/hi/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) और बाहरी वर्कबुक को एक्सेस या लोड नहीं किया जा सकता। |

### संबंधित देखें
* वर्ग [`IChartData`](/slides/python-net/hi/aspose.slides.charts/ichartdata)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)