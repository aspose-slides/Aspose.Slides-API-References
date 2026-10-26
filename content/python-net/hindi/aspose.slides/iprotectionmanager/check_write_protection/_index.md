---
title: check_write_protection method
second_title: Aspose.Slides Python के लिये .NET API रेफ़रेंस के द्वारा
description: 
type: docs
url: /hi/aspose.slides/iprotectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
निर्धारित करता है कि क्या एक प्रस्तुति संशोधित करने के लिए पासवर्ड-प्रोटेक्टेड है।

### रिटर्न
यदि पासवर्ड मान्य है तो True; अन्यथा false।

```python
def check_write_protection(self, password):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| password | **str** | जाँच के लिए पासवर्ड। |

### टिप्पणियाँ
1. आपको इस मेथड को कॉल करने से पहले [`IProtectionManager.is_write_protected`](/slides/python-net/hi/aspose.slides/iprotectionmanager/is_write_protected) प्रॉपर्टी की जाँच करनी चाहिए।
2. जब पासवर्ड None या ख़ाली हो, तो यह मेथड false लौटाता है।

### देखें
* क्लास [`IProtectionManager`](/slides/python-net/hi/aspose.slides/iprotectionmanager)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)