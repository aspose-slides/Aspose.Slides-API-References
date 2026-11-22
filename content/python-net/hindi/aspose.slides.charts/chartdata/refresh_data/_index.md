---
title: refresh_data method
second_title: Aspose.Slides for Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/chartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
चार्ट डेटा को स्रोत वर्कबुक से पुनः लोड करके रीफ़्रेश करता है।

```python
def refresh_data(self):
    ...
```

### टिप्पणी
यदि चार्ट एक बाहरी वर्कबुक का उपयोग करता है, तो कॉल के समय वर्कबुक सुलभ होना चाहिए।

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | जब वर्कबुक फ़ॉर्मेट समर्थित नहीं है, या जब [`ChartData.data_source_type`](/slides/python-net/hi/aspose.slides.charts/chartdata/data_source_type) है<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/hi/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) और बाहरी वर्कबुक तक पहुँच नहीं हो सकती या लोड नहीं किया जा सकता। |

### देखें
* क्लास [`ChartData`](/slides/python-net/hi/aspose.slides.charts/chartdata)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)