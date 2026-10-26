---
title: ToByteArray()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: स्ट्रिंग या सबस्ट्रिंग को बाइट्स की सरणी में बदलता है।
type: docs
weight: 508
url: /hi/system/string/tobytearray/
---
## String::ToByteArray(int32_t, int32_t, bool) const विधि

स्ट्रिंग या सबस्ट्रिंग को बाइट्स की सरणी में बदलता है।

```cpp
ArrayPtr<uint8_t> System::String::ToByteArray(int32_t startIndex=0, int32_t length=INT32_MAX, bool LE=1) const
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startIndex | **int32_t** | सबस्ट्रिंग की प्रारंभिक इंडेक्स। |
| length | **int32_t** | सबस्ट्रिंग की लंबाई। |
| LE | **bool** | यदि true है, तो छोटे एंडियन के साथ अक्षरों को एन्कोड करता है; अन्यथा बड़े एंडियन का उपयोग करता है। |

### रिटर्न मान

[Array](../../array/) स्ट्रिंग के अक्षरों को दर्शाने वाले बाइट्स को शामिल करता है।

## देखें

* टाइपडेफ़ [ArrayPtr](../../arrayptr/)
* क्लास [String](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)