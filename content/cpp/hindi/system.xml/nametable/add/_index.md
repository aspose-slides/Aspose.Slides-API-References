---
title: Add()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट स्ट्रिंग को एटोमीकृत करता है और इसे NameTable में जोड़ता है।
type: docs
weight: 14
url: /hi/system.xml/nametable/add/
---
## NameTable::Add(const String\&) विधि

निर्दिष्ट स्ट्रिंग को एटोमीकृत करता है और इसे [NameTable](../) में जोड़ता है।

```cpp
const String & System::Xml::NameTable::Add(const String &key) override
```

### आर्ग्यूमेंट्स

| परामिटर | प्रकार | विवरण |
| --- | --- | --- |
| key | const [String](../../../system/string/)\& | जोड़ने के लिए स्ट्रिंग। |

### रिटर्न मान

एटोमीकृत स्ट्रिंग या मौजूदा स्ट्रिंग, यदि यह पहले से [NameTable](../) में मौजूद है।

## NameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) विधि

निर्दिष्ट स्ट्रिंग को एटोमीकृत करता है और इसे [NameTable](../) में जोड़ता है।

```cpp
const String & System::Xml::NameTable::Add(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```

### आर्ग्यूमेंट्स

| परामिटर | प्रकार | विवरण |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | जोड़ने के लिए स्ट्रिंग वाला कैरेक्टर ऐरे। |
| start | **int32_t** | स्ट्रिंग के पहले कैरेक्टर को निर्दिष्ट करने वाला शून्य-आधारित इंडेक्स। |
| len | **int32_t** | स्ट्रिंग में कैरेक्टरों की संख्या। |

### रिटर्न मान

एटोमीकृत स्ट्रिंग या मौजूदा स्ट्रिंग, यदि यह पहले से [NameTable](../) में मौजूद है। यदि **len** शून्य है, तो [String::Empty](../../../system/string/empty/) लौटाया जाता है।

## संबंधित देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [String](../../../system/string/)
* क्लास [NameTable](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)