---
title: add method
second_title: Aspose.Slides के लिये Python via .NET एपीआई संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/chartcellcollection/add/
weight: 10
---
## add(self, cell) {#ichartdatacell}
संग्रह में नया सेल जोड़ें।


```python
def add(self, cell):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| cell | [`IChartDataCell`](/slides/python-net/hi/aspose.slides.charts/ichartdatacell) | जोड़ने के लिए नया सेल। |


## add(self, value) {#any}
निर्दिष्ट मान से [`ChartDataCell`](/slides/python-net/hi/aspose.slides.charts/chartdatacell) बनाता है और उसे संग्रह में जोड़ता है।


```python
def add(self, value):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| value | **any** | वह मान। |

### टिप्पणी

यह विधि AUTO_DATA नाम की कार्यपत्रिका जोड़ती है और सभी मान वहाँ जोड़ती है।  यदि आप [`ChartDataWorkbook`](/slides/python-net/hi/aspose.slides.charts/chartdataworkbook) का उपयोग करके Cell मान जोड़ते या संपादित करते हैं, तो सुनिश्चित करें कि आप इस कार्यपत्रिका का उपयोग न करें
            इस विधि का उपयोग करके जोड़े गए मानों की अधिकतम संख्या 16711680 से अधिक नहीं होनी चाहिए।

### अपवाद

| अपवर्जन | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | यदि सीमा अधिक हो गई |



### देखें
* क्लास [`ChartCellCollection`](/slides/python-net/hi/aspose.slides.charts/chartcellcollection)
* क्लास [`ChartDataCell`](/slides/python-net/hi/aspose.slides.charts/chartdatacell)
* क्लास [`ChartDataWorkbook`](/slides/python-net/hi/aspose.slides.charts/chartdataworkbook)
* क्लास [`IChartDataCell`](/slides/python-net/hi/aspose.slides.charts/ichartdatacell)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)