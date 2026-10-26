---
title: ToString()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए GUID को उसकी स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है।
type: docs
weight: 79
url: /hi/system/guid/tostring/
---
## Guid::ToString() const विधि

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए GUID को उसकी स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है।

```cpp
String System::Guid::ToString() const
```

## Guid::ToString(const String\&) const विधि

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए GUID को निर्दिष्ट स्ट्रिंग फ़ॉर्मेट का उपयोग करके उसकी स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है।

```cpp
String System::Guid::ToString(const String &format) const
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| format | const [String](../../string/)\& | उपयोग करने हेतु फ़ॉर्मेट |

### वापसी मान

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए GUID मान की स्ट्रिंग प्रतिनिधित्व

## Guid::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const विधि

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए GUID को निर्दिष्ट स्ट्रिंग फ़ॉर्मेट और कल्चर का उपयोग करके उसकी स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है।

```cpp
String System::Guid::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| format | const [String](../../string/)\& | उपयोग करने हेतु फ़ॉर्मेट |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | उपयोग करने हेतु कल्चर |

### वापसी मान

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए GUID मान की स्ट्रिंग प्रतिनिधित्व

## देखें

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Guid](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)