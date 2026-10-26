---
title: add method
second_title: Aspose.Slides Python के लिए .NET API रेफ़रेंस
description: 
type: docs
url: /hi/aspose.slides.charts/ichartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
If category exists in collection, return it. Else creates new chart category from 
            [`IChartDataCell`](/slides/python-net/hi/aspose.slides.charts/ichartdatacell) and adds it to the collection.

### रिटर्न

Added or existing category.



```python
def add(self, chart_data_cell):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/hi/aspose.slides.charts/ichartdatacell) | चार्ट श्रेणी बनाने हेतु उपयोग किया गया सेल। |


## add(self, value) {#any}
Creates new [`IChartCategory`](/slides/python-net/hi/aspose.slides.charts/ichartcategory) from value and adds it to the collection.

### रिटर्न

Added [`IChartCategory`](/slides/python-net/hi/aspose.slides.charts/ichartcategory).



```python
def add(self, value):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| value | **any** | मूल्य। |

### टिप्पणी

यह विधि AUTO_DATA नामक कार्यपत्र को जोड़ती है और सभी मान वहां जोड़ती है। यदि आप [`IChartDataWorkbook`](/slides/python-net/hi/aspose.slides.charts/ichartdataworkbook) का उपयोग करके सेल मान जोड़ते या संपादित करते हैं, तो सुनिश्चित करें कि आप इस कार्यपत्र का उपयोग न करें। इस विधि का उपयोग करके जोड़े गए मानों की अधिकतम संख्या 16711680 से अधिक नहीं होनी चाहिए।

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | यदि सीमा पार हो जाए |



### देखें भी
* क्लास [`IChartCategory`](/slides/python-net/hi/aspose.slides.charts/ichartcategory)
* क्लास [`IChartCategoryCollection`](/slides/python-net/hi/aspose.slides.charts/ichartcategorycollection)
* क्लास [`IChartDataCell`](/slides/python-net/hi/aspose.slides.charts/ichartdatacell)
* क्लास [`IChartDataWorkbook`](/slides/python-net/hi/aspose.slides.charts/ichartdataworkbook)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)