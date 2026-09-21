---
title: check_write_protection method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/presentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
जाँचता है कि संशोधित करने के लिये पासवर्ड लिखा संरक्षित प्रस्तुति के लिये सही है या नहीं।

### रिटर्न
True यदि प्रस्तुति लिखा संरक्षित है और पासवर्ड सही है। अन्यथा False।

```python
def check_write_protection(self, password):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| password | **str** | जांच की जाने वाली पासवर्ड। |

### टिप्पणियाँ
1. आपको इस मेथड को कॉल करने से पहले [`PresentationInfo.is_write_protected`](/slides/python-net/hi/aspose.slides/presentationinfo/is_write_protected) प्रॉपर्टी की जाँच करनी चाहिए।
2. जब पासवर्ड None या खाली हो, यह मेथड false लौटाता है।

### अपवाद
| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |

### देखें
* क्लास [`PresentationInfo`](/slides/python-net/hi/aspose.slides/presentationinfo)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)