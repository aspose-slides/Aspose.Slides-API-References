---
title: insert_auto_shape method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ishapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
एक नया ऑटो शेप बनाता है और इसे निर्दिष्ट इंडेक्स पर शेप संग्रह में सम्मिलित करता है, डिफ़ॉल्ट टेम्प्लेट फ़ॉर्मेटिंग लागू करता है।

### Returns
नया बनाया गया [`IAutoShape`](/slides/python-net/hi/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | शून्य-आधारित इंडेक्स जहाँ नया ऑटो शेप सम्मिलित किया जाएगा। |
| shape_type | [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype) | इसे सम्मिलित करने वाले ऑटो शेप का [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype)। |
| x | **float** | आकार के फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | आकार के फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | आकार के फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | आकार के फ्रेम की ऊँचाई, पॉइंट्स में। |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
एक नया ऑटो शेप बनाता है और इसे निर्दिष्ट इंडेक्स पर शेप संग्रह में सम्मिलित करता है, वैकल्पिक रूप से इसे डिफ़ॉल्ट टेम्प्लेट शैली के साथ प्रारंभित करता है।

### Returns
नया बनाया गया [`IAutoShape`](/slides/python-net/hi/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | शून्य-आधारित इंडेक्स जहाँ ऑटो शेप सम्मिलित किया जाएगा। |
| shape_type | [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype) | इसे सम्मिलित करने वाले ऑटो शेप का [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype)। |
| x | **float** | आकार के फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | आकार के फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | आकार के फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | आकार के फ्रेम की ऊँचाई, पॉइंट्स में। |
| create_from_template | **bool** | True to apply default template styling (including a non-empty name, simple style, and centered text); <br/><br/>false to create the shape with all properties set to their defaults. |



### See Also
* क्लास [`IAutoShape`](/slides/python-net/hi/aspose.slides/iautoshape)
* क्लास [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection)
* एन्यूमरेशन [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)