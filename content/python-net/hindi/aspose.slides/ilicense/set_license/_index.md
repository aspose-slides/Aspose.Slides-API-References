---
title: set_license method
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ilicense/set_license/
weight: 30
---
## set_license(self, license_name) {#str}
घटक को लाइसेंस देता है।


```python
def set_license(self, license_name):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| license_name | **str** | पूर्ण या संक्षिप्त फ़ाइल नाम या एम्बेडेड रिसोर्स का नाम हो सकता है।<br/><br/>खाली स्ट्रिंग का उपयोग करके इवैल्युएशन मोड में बदलें। |

### टिप्पणियाँ

लाइसेंस को निम्नलिखित स्थानों में खोजता है:


1. निर्दिष्ट पथ।


2. घटक असेंबली का फोल्डर।


3. क्लाइंट की कॉलिंग असेंबली का फोल्डर।


4. एंट्री असेंबली का फोल्डर।


5. क्लाइंट की कॉलिंग असेंबली में एक एम्बेडेड रिसोर्स।


**ध्यान दें:** .NET कॉम्पैक्ट फ्रेमवर्क पर, लाइसेंस को केवल इन स्थानों में खोजता है:


1. निर्दिष्ट पथ।


2. क्लाइंट की कॉलिंग असेंबली में एक एम्बेडेड रिसोर्स।


## set_license(self, stream) {#iorawiobase}
घटक को लाइसेंस देता है।


```python
def set_license(self, stream):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream | **io.RawIOBase** | वह स्ट्रीम जिसमें लाइसेंस हो। |

### टिप्पणियाँ

स्ट्रीम से लाइसेंस लोड करने के लिए इस मेथड का उपयोग करें।



### देखें
* क्लास [`ILicense`](/slides/python-net/hi/aspose.slides/ilicense)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)