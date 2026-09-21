---
title: add_auto_shape method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ishapecollection/add_auto_shape/
weight: 40
---
## add_auto_shape(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
डिफ़ॉल्ट फ़ॉर्मेटिंग के साथ एक नया ऑटो शेप बनाता है और इसे शेप संग्रह के अंत में जोड़ता है।

### वापसी
नया बनाया गया [`IAutoShape`](/slides/python-net/hi/aspose.slides/iautoshape).

```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype) | जोड़ने के लिए ऑटो शेप का [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype)। |
| x | **float** | शेप के फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | **float** | शेप के फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | **float** | शेप के फ्रेम की चौड़ाई, पॉइंट में। |
| height | **float** | शेप के फ्रेम की ऊँचाई, पॉइंट में। |

## add_auto_shape(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
एक नया ऑटो शेप बनाता है और इसे शेप संग्रह के अंत में जोड़ता है, वैकल्पिक रूप से इसे डिफ़ॉल्ट टेम्प्लेट फ़ॉर्मेटिंग के साथ प्रारंभ करता है।

### वापसी
नया बनाया गया [`IAutoShape`](/slides/python-net/hi/aspose.slides/iautoshape).

```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype) | जोड़ने के लिए ऑटो शेप का [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype)। |
| x | **float** | शेप के फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | **float** | शेप के फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | **float** | शेप के फ्रेम की चौड़ाई, पॉइंट में। |
| height | **float** | शेप के फ्रेम की ऊँचाई, पॉइंट में। |
| create_from_template | **bool** | True to apply default template styling (simple style, centered text, and non-empty name)<br/><br/>नए शेप पर डिफ़ॉल्ट टेम्प्लेट शैली (सरल शैली, केंद्रित पाठ, और गैर-रिक्त नाम) को लागू करने के लिए; false सभी गुणों को डिफ़ॉल्ट मानों पर सेट करके शेप बनाने के लिए. |

### और देखें
* वर्ग [`IAutoShape`](/slides/python-net/hi/aspose.slides/iautoshape)
* वर्ग [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection)
* एन्‍युमरेशन [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)