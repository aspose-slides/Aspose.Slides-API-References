---
title: add method
second_title: Aspose.Slides Python के लिए .NET के माध्यम से API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/chartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
यदि संग्रह में श्रेणी मौजूद है, तो उसे लौटाएँ। अन्यथा [`IChartDataCell`](/slides/python-net/hi/aspose.slides.charts/ichartdatacell) से नई चार्ट श्रेणी बनाता है और इसे संग्रह में जोड़ता है।

### रिटर्न मान

जोड़ा गया या मौजूदा श्रेणी।



```python
def add(self, chart_data_cell):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/hi/aspose.slides.charts/ichartdatacell) | चार्ट श्रेणी बनाने के लिए उपयोग किया गया सेल। |


## add(self, value) {#any}
[`ChartCategory`](/slides/python-net/hi/aspose.slides.charts/chartcategory) को मान से बनाता है और इसे संग्रह में जोड़ता है।

### रिटर्न मान

जोड़ा गया [`IChartCategory`](/slides/python-net/hi/aspose.slides.charts/ichartcategory)।



```python
def add(self, value):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| value | **any** | मान। |

### टिप्पणी

यह विधि AUTO_DATA नाम की वर्कशीट जोड़ती है और सभी मान वहाँ जोड़ती है। यदि आप [`ChartDataWorkbook`](/slides/python-net/hi/aspose.slides.charts/chartdataworkbook) का उपयोग करके सेल मान जोड़ते या संपादित करते हैं, तो सुनिश्चित करें कि आप इस वर्कशीट का उपयोग नहीं करें। इस विधि का उपयोग करके जोड़े जा सकने वाले अधिकतम मानों की संख्या 16711680 से अधिक नहीं होनी चाहिए।

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | यदि सीमा पार हो गई |



### और देखें
* क्लास [`ChartCategory`](/slides/python-net/hi/aspose.slides.charts/chartcategory)
* क्लास [`ChartCategoryCollection`](/slides/python-net/hi/aspose.slides.charts/chartcategorycollection)
* क्लास [`ChartDataWorkbook`](/slides/python-net/hi/aspose.slides.charts/chartdataworkbook)
* क्लास [`IChartCategory`](/slides/python-net/hi/aspose.slides.charts/ichartcategory)
* क्लास [`IChartDataCell`](/slides/python-net/hi/aspose.slides.charts/ichartdatacell)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)