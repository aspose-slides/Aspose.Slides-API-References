---
title: add method
second_title: Aspose.Slides के लिए Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/ichartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
नई चार्ट सीरीज़ बनाता है और इसे संग्रह में जोड़ता है।

### रिटर्न
नई चार्ट सीरीज़।

```python
def add(self, type):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/hi/aspose.slides.charts/charttype) | सीरीज़ का प्रकार |

## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
[`IChartDataCell`](/slides/python-net/hi/aspose.slides.charts/ichartdatacell) से नई चार्ट सीरीज़ बनाता है और इसे संग्रह में जोड़ता है।

### रिटर्न
जोड़ाई गई चार्ट सीरीज़ या पहले से संग्रह में मौजूद सीरीज़।

```python
def add(self, cell_with_series_name, type):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/hi/aspose.slides.charts/ichartdatacell) | वह सेल जिसमें सीरीज़ नाम है। |
| type | [`ChartType`](/slides/python-net/hi/aspose.slides.charts/charttype) | सेट किया गया सीरीज़ का प्रकार |

### टिप्पणियाँ
यदि समान सेल से बनाई गई चार्ट सीरीज़ पहले से संग्रह में है 
            तो यह मेथड कुछ नहीं जोड़ता और इसका सूचकांक वापस करता है।

## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
[`IChartCellCollection`](/slides/python-net/hi/aspose.slides.charts/ichartcellcollection) से नई चार्ट सीरीज़ बनाता है और इसे संग्रह में जोड़ता है।

### रिटर्न
जोड़ाई गई चार्ट सीरीज़ या पहले से संग्रह में मौजूद सीरीज़।

```python
def add(self, cells_with_series_name, type):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/hi/aspose.slides.charts/ichartcellcollection) | वे सेल जिनमें सीरीज़ नाम है। |
| type | [`ChartType`](/slides/python-net/hi/aspose.slides.charts/charttype) | सेट किया गया सीरीज़ का प्रकार |

### टिप्पणियाँ
यदि समान सेल से बनाई गई चार्ट सीरीज़ पहले से संग्रह में है 
            तो यह मेथड कुछ नहीं जोड़ता और इसका सूचकांक वापस करता है।

## add(self, name, type) {#str-charttype}
मान से नई चार्ट सीरीज़ बनाता है और इसे संग्रह में जोड़ता है।

### रिटर्न
जोड़ाई गई चार्ट सीरीज़।

```python
def add(self, name, type):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| name | **str** | सीरीज़ का नाम। |
| type | [`ChartType`](/slides/python-net/hi/aspose.slides.charts/charttype) | सेट किया गया सीरीज़ का प्रकार |

### संबंधित देखें
* enumeration [`ChartType`](/slides/python-net/hi/aspose.slides.charts/charttype)
* class [`IChartCellCollection`](/slides/python-net/hi/aspose.slides.charts/ichartcellcollection)
* class [`IChartDataCell`](/slides/python-net/hi/aspose.slides.charts/ichartdatacell)
* class [`IChartSeries`](/slides/python-net/hi/aspose.slides.charts/ichartseries)
* class [`IChartSeriesCollection`](/slides/python-net/hi/aspose.slides.charts/ichartseriescollection)
* module [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)