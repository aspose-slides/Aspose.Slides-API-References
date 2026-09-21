---
title: check_password method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/presentationinfo/check_password/
weight: 10
---
## check_password(self, password) {#str}
जाँचता है कि क्या पासवर्ड सही है एक प्रस्तुति के लिए जो ओपन पासवर्ड द्वारा संरक्षित है।

### रिटर्न वैल्यू

True यदि प्रस्तुति ओपन पासवर्ड द्वारा संरक्षित है और पासवर्ड सही है और अन्यथा false।

```python
def check_password(self, password):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| password | **str** | जांचने के लिए पासवर्ड। |

### टिप्पणी

जब पासवर्ड None या खाली हो, यह मेथड false लौटाता है।

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |
| **RuntimeError(Proxy error(NotSupportedException))** |  |

### देखें
* क्लास [`PresentationInfo`](/slides/python-net/hi/aspose.slides/presentationinfo)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)