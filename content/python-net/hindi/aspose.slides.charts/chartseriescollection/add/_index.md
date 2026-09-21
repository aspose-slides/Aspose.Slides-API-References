---
title: add method
second_title: Aspose.Slides Python के लिये .NET API संदर्भ के माध्यम से
description: 
type: docs
url: /hi/aspose.slides.charts/chartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
नया चार्ट सीरीज़ बनाता है और इसे संग्रह में जोड़ता है।

### रिटर्न
नया चार्ट सीरीज़।

```python
def add(self, type):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/hi/aspose.slides.charts/charttype) | सीरीज़ का प्रकार |

## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
[`ChartDataCell`](/slides/python-net/hi/aspose.slides.charts/chartdatacell) से नया चार्ट सीरीज़ बनाता है और इसे संग्रह में जोड़ता है।

### रिटर्न
जोड़ दिया गया चार्ट सीरीज़ या वह सीरीज़ जो पहले से ही संग्रह में मौजूद है।

```python
def add(self, cell_with_series_name, type):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/hi/aspose.slides.charts/ichartdatacell) | सेल जिसमें सीरीज़ नाम होता है। |
| type | [`ChartType`](/slides/python-net/hi/aspose.slides.charts/charttype) | सीरीज़ के प्रकार को सेट करने वाला प्रकार |

### टिप्पणी
यदि समान सेल से बना चार्ट सीरीज़ पहले से ही संग्रह में है, तो विधि कुछ नहीं जोड़ती और इसका इंडेक्स वापस करती है।

## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
[`ChartCellCollection`](/slides/python-net/hi/aspose.slides.charts/chartcellcollection) से नया चार्ट सीरीज़ बनाता है और इसे संग्रह में जोड़ता है।

### रिटर्न
जोड़ दिया गया चार्ट सीरीज़ या वह सीरीज़ जो पहले से ही संग्रह में मौजूद है।

```python
def add(self, cells_with_series_name, type):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/hi/aspose.slides.charts/ichartcellcollection) | सेल्स जिनमें सीरीज़ नाम होता है। |
| type | [`ChartType`](/slides/python-net/hi/aspose.slides.charts/charttype) | सीरीज़ के प्रकार को सेट करने वाला प्रकार |

### टिप्पणी
यदि समान सेल से बना चार्ट सीरीज़ पहले से ही संग्रह में है, तो विधि कुछ नहीं जोड़ती और इसका इंडेक्स वापस करती है।

## add(self, name, type) {#str-charttype}
मान से नया चार्ट सीरीज़ बनाता है और इसे संग्रह में जोड़ता है।

### रिटर्न
जोड़ दिया गया चार्ट सीरीज़।

```python
def add(self, name, type):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| name | **str** | सीरीज़ का नाम। |
| type | [`ChartType`](/slides/python-net/hi/aspose.slides.charts/charttype) | सीरीज़ के प्रकार को सेट करने वाला प्रकार |

### संबंधित देखें
* वर्ग [`ChartCellCollection`](/slides/python-net/hi/aspose.slides.charts/chartcellcollection)
* वर्ग [`ChartDataCell`](/slides/python-net/hi/aspose.slides.charts/chartdatacell)
* वर्ग [`ChartSeriesCollection`](/slides/python-net/hi/aspose.slides.charts/chartseriescollection)
* एन्यूमरेशन [`ChartType`](/slides/python-net/hi/aspose.slides.charts/charttype)
* वर्ग [`IChartCellCollection`](/slides/python-net/hi/aspose.slides.charts/ichartcellcollection)
* वर्ग [`IChartDataCell`](/slides/python-net/hi/aspose.slides.charts/ichartdatacell)
* वर्ग [`IChartSeries`](/slides/python-net/hi/aspose.slides.charts/ichartseries)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)