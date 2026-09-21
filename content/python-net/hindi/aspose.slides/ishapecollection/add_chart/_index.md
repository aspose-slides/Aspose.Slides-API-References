---
title: add_chart method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ishapecollection/add_chart/
weight: 50
---
## add_chart(self, type, x, y, width, height) {#asposeslideschartscharttype-float-float-float-float}
एक नया चार्ट बनाता है, इसे नमूना सीरीज़ डेटा और सेटिंग्स के साथ इनिशियलाइज़ करता है, और इसे शेप कलेक्शन के अंत में जोड़ता है।

### Returns

नया बनाया गया [`IChart`](/slides/python-net/hi/aspose.slides.charts/ichart).



```python
def add_chart(self, type, x, y, width, height):
    ...
```


| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/hi/aspose.slides.charts/charttype) | जोड़ने के लिए चार्ट का प्रकार। |
| x | **float** | नए चार्ट का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए चार्ट का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | चार्ट की चौड़ाई, पॉइंट्स में। |
| height | **float** | चार्ट की ऊँचाई, पॉइंट्स में। |


## add_chart(self, type, x, y, width, height, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-bool}
एक नया चार्ट बनाता है, इसे नमूना सीरीज़ डेटा और सेटिंग्स के साथ इनिशियलाइज़ करता है, और इसे शेप कलेक्शन के अंत में जोड़ता है।

### Returns

नया बनाया गया [`IChart`](/slides/python-net/hi/aspose.slides.charts/ichart).



```python
def add_chart(self, type, x, y, width, height, init_with_sample):
    ...
```


| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/hi/aspose.slides.charts/charttype) | जोड़ने के लिए चार्ट का प्रकार। |
| x | **float** | नए चार्ट का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए चार्ट का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | चार्ट की चौड़ाई, पॉइंट्स में। |
| height | **float** | चार्ट की ऊँचाई, पॉइंट्स में। |
| init_with_sample | **bool** | नया चार्ट नमूना सीरीज़ डेटा और सेटिंग्स के साथ इनिशियलाइज़ करने के लिए True; बिना सीरीज़ के और केवल न्यूनतम सेटिंग्स के साथ चार्ट बनाने के लिए false, जिससे निर्माण तेज़ हो जाता है। |



### See Also
* enumeration [`ChartType`](/slides/python-net/hi/aspose.slides.charts/charttype)
* class [`IChart`](/slides/python-net/hi/aspose.slides.charts/ichart)
* class [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)