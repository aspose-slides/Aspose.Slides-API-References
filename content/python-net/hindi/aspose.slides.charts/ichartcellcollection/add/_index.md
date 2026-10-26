---
title: add method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/ichartcellcollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
संग्रह में नया सेल जोड़ें।

```python
def add(self, chart_data_cell):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/hi/aspose.slides.charts/ichartdatacell) | जोड़ने के लिए नया सेल। |

## add(self, value) {#any}
निर्दिष्ट मान से [`IChartDataCell`](/slides/python-net/hi/aspose.slides.charts/ichartdatacell) बनाता है और इसे संग्रह में जोड़ता है।

```python
def add(self, value):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| value | **any** | मान। |

### टिप्पणियाँ
यह विधि AUTO_DATA नाम की कार्यपत्रिका जोड़ती है और सभी मान वहाँ जोड़ती है।  यदि आप [`IChartDataWorkbook`](/slides/python-net/hi/aspose.slides.charts/ichartdataworkbook) का उपयोग सेल मान जोड़ने या संपादित करने के लिए करते हैं, तो सुनिश्चित करें कि आप इस कार्यपत्रिका का उपयोग न करें
            इस विधि से जोड़े जा सकने वाले मानों की अधिकतम संख्या 16711680 से अधिक नहीं होनी चाहिए

### अपवाद
| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | यदि सीमा पार हो गई |

### संबंधित देखें
* क्लास [`IChartCellCollection`](/slides/python-net/hi/aspose.slides.charts/ichartcellcollection)
* क्लास [`IChartDataCell`](/slides/python-net/hi/aspose.slides.charts/ichartdatacell)
* क्लास [`IChartDataWorkbook`](/slides/python-net/hi/aspose.slides.charts/ichartdataworkbook)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)