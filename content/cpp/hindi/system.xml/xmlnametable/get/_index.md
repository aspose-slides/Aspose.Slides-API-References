---
title: Get()
second_title: Aspose.Slides for C++ API संदर्भ
description: जब किसी व्युत्पन्न वर्ग में इसे ओवरराइड किया जाता है, तो यह निर्दिष्ट एरे में दिए गए वर्णों की रेंज के समान वर्णों वाले एटमाइज़्ड स्ट्रिंग को प्राप्त करता है।
type: docs
weight: 1
url: /hi/system.xml/xmlnametable/get/
---
## XmlNameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) विधि

जब किसी व्युत्पन्न वर्ग में इसे ओवरराइड किया जाता है, तो यह निर्दिष्ट एरे में दिए गए वर्णों की रेंज के समान वर्णों वाले एटमाइज़्ड स्ट्रिंग को प्राप्त करता है।

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | नाम को खोजने के लिए वर्ण एरे। |
| offset | **int32_t** | एरे में शून्य-आधारित इंडेक्स जो नाम के पहले वर्ण को निर्दिष्ट करता है। |
| length | **int32_t** | नाम में वर्णों की संख्या। |

### वापसी मान

एटमाइज़्ड स्ट्रिंग या **nullptr** यदि स्ट्रिंग पहले से एटमाइज़ नहीं हुई है। यदि **length** शून्य है, [String::Empty](../../../system/string/empty/) लौटाया जाता है।

## XmlNameTable::Get(const String\&) विधि

जब किसी व्युत्पन्न वर्ग में इसे ओवरराइड किया जाता है, तो यह निर्दिष्ट स्ट्रिंग के समान मान वाले एटमाइज़्ड स्ट्रिंग को प्राप्त करता है।

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const String &array)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | खोजने हेतु नाम। |

### वापसी मान

एटमाइज़्ड स्ट्रिंग या **nullptr** यदि स्ट्रिंग पहले से एटमाइज़ नहीं हुई है।

## और देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [String](../../../system/string/)
* क्लास [XmlNameTable](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)