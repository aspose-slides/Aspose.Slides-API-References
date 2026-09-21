---
title: set_license method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/license/set_license/
weight: 40
---
## set_license(self, license_name) {#str}
Licenses the component.


```python
def set_license(self, license_name):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| license_name | **str** | पूर्ण या छोटा फ़ाइल नाम या एम्बेडेड रिसोर्स का नाम हो सकता है।<br/><br/>            मूल्यांकन मोड में स्विच करने के लिए खाली स्ट्रिंग उपयोग करें। |

### टिप्पणी

लाइसेंस को निम्नलिखित स्थानों में खोजने का प्रयास करता है:


1. स्पष्ट पथ।


2. घटक असेंबली का फ़ोल्डर।


3. क्लाइंट की कॉलिंग असेंबली का फ़ोल्डर।


4. एंट्री असेंबली का फ़ोल्डर।


5. क्लाइंट की कॉलिंग असेंबली में एम्बेडेड रिसोर्स।


**Note:** .NET Compact Framework पर, लाइसेंस को केवल इन स्थानों में खोजता है:


1. स्पष्ट पथ।


2. क्लाइंट की कॉलिंग असेंबली में एम्बेडेड रिसोर्स।


## set_license(self, stream) {#iorawiobase}
Licenses the component.


```python
def set_license(self, stream):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream | **io.RawIOBase** | एक स्ट्रीम जिसमें लाइसेंस शामिल है। |

### टिप्पणी

स्ट्रीम से लाइसेंस लोड करने के लिए इस मेथड का उपयोग करें।



### देखें
* क्लास [`License`](/slides/python-net/hi/aspose.slides/license)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)