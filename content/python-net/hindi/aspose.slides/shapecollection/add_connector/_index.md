---
title: add_connector method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/shapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
डिफ़ॉल्ट टेम्पलेट स्टाइलिंग के साथ एक नया कनेक्टर आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है।

### Returns
नव निर्मित [`IConnector`](/slides/python-net/hi/aspose.slides/iconnector)।

```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype) | जोड़ने के लिए कनेक्टर आकार का [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype)। |
| x | **float** | कनेक्टर के फ़्रेम का x-निर्देशांक, बिंदुओं में। |
| y | **float** | कनेक्टर के फ़्रेम का y-निर्देशांक, बिंदुओं में। |
| width | **float** | कनेक्टर के फ़्रेम की चौड़ाई, बिंदुओं में। |
| height | **float** | कनेक्टर के फ़्रेम की ऊँचाई, बिंदुओं में। |

## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
एक नया कनेक्टर आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्पलेट स्टाइलिंग लागू करता है।

### Returns
नव निर्मित [`IConnector`](/slides/python-net/hi/aspose.slides/iconnector)।

```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype) | बनाने के लिए कनेक्टर आकार का [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype)। |
| x | **float** | कनेक्टर के फ़्रेम का x-निर्देशांक, बिंदुओं में। |
| y | **float** | कनेक्टर के फ़्रेम का y-निर्देशांक, बिंदुओं में। |
| width | **float** | कनेक्टर के फ़्रेम की चौड़ाई, बिंदुओं में। |
| height | **float** | कनेक्टर के फ़्रेम की ऊँचाई, बिंदुओं में। |
| create_from_template | **bool** | True डिफ़ॉल्ट टेम्पलेट स्टाइलिंग (खाली न होने वाला नाम, सरल शैली) लागू करने के लिए; <br/><br/> false कनेक्टर को डिफ़ॉल्ट प्रॉपर्टी मानों के साथ बनाने के लिए। |

### See Also
* क्लास [`IConnector`](/slides/python-net/hi/aspose.slides/iconnector)
* क्लास [`ShapeCollection`](/slides/python-net/hi/aspose.slides/shapecollection)
* एन्यूमरेशन [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)