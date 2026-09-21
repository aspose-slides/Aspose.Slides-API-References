---
title: add_chart method
second_title: Aspose.Slides for Python द्वारा .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/shapecollection/add_chart/
weight: 50
---
## add_chart(self, type, x, y, width, height) {#asposeslideschartscharttype-float-float-float-float}
एक नया chart बनाता है, इसे सैंपल सीरीज़ डेटा और सेटिंग्स के साथ प्रारंभ करता है, और इसे shape collection के अंत में जोड़ता है।

### रिटर्न
नया बनाया गया [`IChart`](/slides/python-net/hi/aspose.slides.charts/ichart)।

```python
def add_chart(self, type, x, y, width, height):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/hi/aspose.slides.charts/charttype) | chart जोड़ने का प्रकार। |
| x | **float** | नए chart का x-निर्देशांक, पॉइंट में। |
| y | **float** | नए chart का y-निर्देशांक, पॉइंट में। |
| width | **float** | chart की चौडाई, पॉइंट में। |
| height | **float** | chart की ऊँचाई, पॉइंट में। |

## add_chart(self, type, x, y, width, height, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-bool}
एक नया chart बनाता है, इसे सैंपल सीरीज़ डेटा और सेटिंग्स के साथ प्रारंभ करता है, और इसे shape collection के अंत में जोड़ता है।

### रिटर्न
नया बनाया गया [`IChart`](/slides/python-net/hi/aspose.slides.charts/ichart)।

```python
def add_chart(self, type, x, y, width, height, init_with_sample):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/hi/aspose.slides.charts/charttype) | chart जोड़ने का प्रकार। |
| x | **float** | नए chart का x-निर्देशांक, पॉइंट में। |
| y | **float** | नए chart का y-निर्देशांक, पॉइंट में। |
| width | **float** | chart की चौडाई, पॉइंट में। |
| height | **float** | chart की ऊँचाई, पॉइंट में। |
| init_with_sample | **bool** | नया chart को सैंपल सीरीज़ डेटा और सेटिंग्स के साथ प्रारंभ करने के लिए true; <br/><br/>            chart को बिना सीरीज़ के और केवल न्यूनतम सेटिंग्स के साथ बनाने के लिए false, जिससे निर्माण तेज़ होता है। |

### देखें
* एन्यूमेरेशन [`ChartType`](/slides/python-net/hi/aspose.slides.charts/charttype)
* क्लास [`IChart`](/slides/python-net/hi/aspose.slides.charts/ichart)
* क्लास [`ShapeCollection`](/slides/python-net/hi/aspose.slides/shapecollection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)