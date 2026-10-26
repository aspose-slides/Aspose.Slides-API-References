---
title: add_connector method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ishapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
डिफ़ॉल्ट टेम्पलेट स्टाइलिंग के साथ एक नया कनेक्टर शेप बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है।

### रिटर्न
नया निर्मित [`IConnector`](/slides/python-net/hi/aspose.slides/iconnector)।

```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype) | जोड़ने के लिए कनेक्टर शेप का [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype)। |
| x | **float** | कनेक्टर के फ्रेम का x-कोऑर्डिनेट, पॉइंट्स में। |
| y | **float** | कनेक्टर के फ्रेम का y-कोऑर्डिनेट, पॉइंट्स में। |
| width | **float** | कनेक्टर के फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | कनेक्टर के फ्रेम की ऊँचाई, पॉइंट्स में। |

## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
एक नया कनेक्टर शेप बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है, वैकल्पिक रूप से डिफ़ॉल्ट टेम्पलेट स्टाइलिंग लागू करता है।

### रिटर्न
नया निर्मित [`IConnector`](/slides/python-net/hi/aspose.slides/iconnector)।

```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype) | बनाने के लिए कनेक्टर शेप का [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype)। |
| x | **float** | कनेक्टर के फ्रेम का x-कोऑर्डिनेट, पॉइंट्स में। |
| y | **float** | कनेक्टर के फ्रेम का y-कोऑर्डिनेट, पॉइंट्स में। |
| width | **float** | कनेक्टर के फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | कनेक्टर के फ्रेम की ऊँचाई, पॉइंट्स में। |
| create_from_template | **bool** | डिफ़ॉल्ट टेम्पलेट स्टाइलिंग लागू करने के लिए true (खाली नहीं नाम, साधारण स्टाइल); <br/><br/>            डिफ़ॉल्ट प्रॉपर्टी मानों के साथ कनेक्टर बनाने के लिए false। |

### देखें भी
* क्लास [`IConnector`](/slides/python-net/hi/aspose.slides/iconnector)
* क्लास [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection)
* enumeration [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)