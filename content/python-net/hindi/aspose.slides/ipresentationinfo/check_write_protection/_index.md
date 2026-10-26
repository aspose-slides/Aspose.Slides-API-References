---
title: check_write_protection method
second_title: Aspose.Slides Python के लिए .NET के माध्यम से API Reference
description: 
type: docs
url: /hi/aspose.slides/ipresentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
जाँचता है कि संशोधित करने के लिये दिया गया पासवर्ड लिखने-रक्षित प्रस्तुति के लिये सही है या नहीं।

### रिटर्न वैल्यू

True यदि प्रस्तुति लिखित-रक्षित है और पासवर्ड सही है। अन्यथा False।

```python
def check_write_protection(self, password):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| password | **str** | जाँचने के लिये पासवर्ड। |

### टिप्पणियाँ

1. आपको इस मेथड को कॉल करने से पहले [`IPresentationInfo.is_write_protected`](/slides/python-net/hi/aspose.slides/ipresentationinfo/is_write_protected) प्रॉपर्टी को जांचना चाहिए।
2. जब पासवर्ड None या खाली हो, तो यह मेथड false लौटाता है।

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |

### देखें

* क्लास [`IPresentationInfo`](/slides/python-net/hi/aspose.slides/ipresentationinfo)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)