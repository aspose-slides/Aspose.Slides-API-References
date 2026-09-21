---
title: insert_auto_shape method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/shapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
एक नया auto shape बनाता है और इसे निर्दिष्ट इंडेक्स पर shape collection में डालता है, डिफ़ॉल्ट टेम्प्लेट फ़ॉर्मेटिंग लागू करता है।

### Returns

नया बनाया गया [`IAutoShape`](/slides/python-net/hi/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | नई auto shape को डालने के लिए शून्य-आधारित इंडेक्स। |
| shape_type | [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype) | डालने के लिए auto shape का [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype)। |
| x | **float** | shape के फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | shape के फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | shape के फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | shape के फ्रेम की ऊँचाई, पॉइंट्स में। |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
एक नया auto shape बनाता है और इसे निर्दिष्ट इंडेक्स पर shape collection में डालता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग के साथ प्रारंभ करता है।

### Returns

नया बनाया गया [`IAutoShape`](/slides/python-net/hi/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | auto shape को डालने के लिए शून्य-आधारित इंडेक्स। |
| shape_type | [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype) | डालने के लिए auto shape का [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype)। |
| x | **float** | shape के फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | shape के फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | shape के फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | shape के फ्रेम की ऊँचाई, पॉइंट्स में। |
| create_from_template | **bool** | डिफ़ॉल्ट टेम्प्लेट स्टाइलिंग लागू करने के लिए True (जिसमें गैर-खाली नाम, सरल स्टाइल, और केंद्रित टेक्स्ट शामिल है); <br/><br/>false सभी प्रॉपर्टीज़ को डिफ़ॉल्ट पर सेट करके shape बनाने के लिए। |



### See Also
* क्लास [`IAutoShape`](/slides/python-net/hi/aspose.slides/iautoshape)
* क्लास [`ShapeCollection`](/slides/python-net/hi/aspose.slides/shapecollection)
* एन्यूमरेशन [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)