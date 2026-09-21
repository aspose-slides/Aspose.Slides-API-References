---
title: set_embedded_data method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ioleobjectframe/set_embedded_data/
weight: 50
---
## set_embedded_data(self, embedded_data) {#ioleembeddeddatainfo}
OLE एम्बेडेड डेटा के बारे में जानकारी सेट करता है।

```python
def set_embedded_data(self, embedded_data):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| embedded_data | [`IOleEmbeddedDataInfo`](/slides/python-net/hi/aspose.slides/ioleembeddeddatainfo) | एम्बेडेड डेटा [`IOleEmbeddedDataInfo`](/slides/python-net/hi/aspose.slides/ioleembeddeddatainfo) |

### टिप्पणी

यह मेथड ऑब्जेक्ट की प्रॉपर्टीज़ को नए डेटा को दर्शाने के लिए बदलता है और IsObjectLink फ़्लैग को false सेट करता है, यह दर्शाते हुए कि OLE ऑब्जेक्ट एम्बेडेड है।

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | जब embeddedData पैरामीटर None हो। |

### संबंधित देखें
* क्लास [`IOleEmbeddedDataInfo`](/slides/python-net/hi/aspose.slides/ioleembeddeddatainfo)
* क्लास [`IOleObjectFrame`](/slides/python-net/hi/aspose.slides/ioleobjectframe)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)