---
title: insert_chart method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/shapecollection/insert_chart/
weight: 240
---
## insert_chart(self, type, x, y, width, height, index) {#asposeslideschartscharttype-float-float-float-float-int}
एक नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स के साथ प्रारंभ करता है, और निर्दिष्ट अनुक्रमांक पर शेप संग्रह में सम्मिलित करता है।

### Returns

नया निर्मित [`IChart`](/slides/python-net/hi/aspose.slides.charts/ichart).



```python
def insert_chart(self, type, x, y, width, height, index):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/hi/aspose.slides.charts/charttype) | बनाए जाने वाले चार्ट का प्रकार। |
| x | **float** | नए चार्ट का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए चार्ट का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए चार्ट की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए चार्ट की ऊँचाई, पॉइंट्स में। |
| index | **int** | शेप संग्रह में नए चार्ट को सम्मिलित करने का शून्य-आधारित अनुक्रमांक। |


## insert_chart(self, type, x, y, width, height, index, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-int-bool}
एक नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स के साथ प्रारंभ करता है, और निर्दिष्ट अनुक्रमांक पर शेप संग्रह में सम्मिलित करता है।

### Returns

नया निर्मित [`IChart`](/slides/python-net/hi/aspose.slides.charts/ichart).



```python
def insert_chart(self, type, x, y, width, height, index, init_with_sample):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/hi/aspose.slides.charts/charttype) | बनाए जाने वाले चार्ट का प्रकार। |
| x | **float** | नए चार्ट का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए चार्ट का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए चार्ट की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए चार्ट की ऊँचाई, पॉइंट्स में। |
| index | **int** | शेप संग्रह में नए चार्ट को सम्मिलित करने का शून्य-आधारित अनुक्रमांक। |
| init_with_sample | **bool** | True होने पर नया चार्ट नमूना श्रृंखला डेटा और सेटिंग्स के साथ प्रारंभ किया जाता है; <br/><br/>false होने पर कोई श्रृंखला नहीं और केवल न्यूनतम सेटिंग्स के साथ चार्ट बनाया जाता है, जिससे निर्माण तेज़ होता है। |



### See Also
* enumeration [`ChartType`](/slides/python-net/hi/aspose.slides.charts/charttype)
* class [`IChart`](/slides/python-net/hi/aspose.slides.charts/ichart)
* class [`ShapeCollection`](/slides/python-net/hi/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)