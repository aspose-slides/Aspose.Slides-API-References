---
title: Get()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट मान के साथ एटमीकृत स्ट्रिंग लौटाता है।
type: docs
weight: 27
url: /hi/system.xml/nametable/get/
---
## NameTable::Get(const String\&) मेथड


निर्दिष्ट मान के साथ एटमीकृत स्ट्रिंग लौटाता है।

```cpp
const String & System::Xml::NameTable::Get(const String &value) override
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | खोजने के लिये नाम। |

### रिटर्न वैल्यू

एटमीकृत स्ट्रिंग ऑब्जेक्ट या **nullptr** यदि स्ट्रिंग पहले से एटमीकृत नहीं हुई है।

## NameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) मेथड


दिए गए एरे में निर्दिष्ट कैरेक्टर रेंज के समान कैरेक्टर वाली एटमीकृत स्ट्रिंग लौटाता है।

```cpp
const String & System::Xml::NameTable::Get(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | खोजने के लिये नाम वाले कैरेक्टर एरे। |
| start | **int32_t** | एरे में उस पहले कैरेक्टर का शून्य-आधारित इंडेक्स जो नाम की शुरुआत दर्शाता है। |
| len | **int32_t** | नाम में कैरेक्टर की संख्या। |

### रिटर्न वैल्यू

एटमीकृत स्ट्रिंग या **nullptr** यदि स्ट्रिंग पहले से एटमीकृत नहीं हुई है। यदि **len** शून्य है, तो [String::Empty](../../../system/string/empty/) लौटाया जाता है।

## देखें भी

* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [String](../../../system/string/)
* क्लास [NameTable](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)