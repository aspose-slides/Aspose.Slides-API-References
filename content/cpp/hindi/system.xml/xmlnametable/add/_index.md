---
title: Add()
second_title: Aspose.Slides for C++ API संदर्भ
description: जब एक व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो निर्दिष्ट स्ट्रिंग को एटॉमिक किया जाता है और उसे XmlNameTable में जोड़ा जाता है।
type: docs
weight: 14
url: /hi/system.xml/xmlnametable/add/
---
## XmlNameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) विधि

जब एक व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो निर्दिष्ट स्ट्रिंग को एटॉमिक किया जाता है और उसे [XmlNameTable](../) में जोड़ा जाता है।

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | जोड़ने के लिए नाम वाले कैरेक्टर एरे। |
| offset | **int32_t** | एरे में उस पहले कैरेक्टर का शून्य-आधारित इंडेक्स जो नाम का हिस्सा है। |
| length | **int32_t** | नाम में कैरेक्टरों की संख्या। |

### रिटर्न वैल्यू

नया एटॉमिक किया गया स्ट्रिंग या मौजूदा स्ट्रिंग यदि वह पहले से मौजूद है। यदि length शून्य है, तो [String::Empty](../../../system/string/empty/) लौटाया जाता है।

## XmlNameTable::Add(const String\&) विधि

जब एक व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो निर्दिष्ट स्ट्रिंग को एटॉमिक किया जाता है और उसे [XmlNameTable](../) में जोड़ा जाता है।

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const String &array)=0
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | जोड़ने के लिए नाम। |

### रिटर्न वैल्यू

नया एटॉमिक किया गया स्ट्रिंग या मौजूदा स्ट्रिंग यदि वह पहले से मौजूद है।

## देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [String](../../../system/string/)
* क्लास [XmlNameTable](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)