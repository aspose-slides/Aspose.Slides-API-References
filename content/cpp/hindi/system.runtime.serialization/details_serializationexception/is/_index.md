---
title: Is()
second_title: Aspose.Slides for C++ API संदर्भ
description: 
type: docs
weight: 27
url: /hi/system.runtime.serialization/details_serializationexception/is/
---
## Details_SerializationException::Is(const System::TypeInfo\&) const मेथड

```cpp
bool System::Runtime::Serialization::Details_SerializationException::Is(const System::TypeInfo &target) const override
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) संरचना जो उस प्रकार को वर्णित करती है जिसका परीक्षण वर्तमान ऑब्जेक्ट के विरुद्ध किया जाता है। |

### वापसी मान

यदि ऑब्जेक्ट टैग किए गए प्रकार या उसकी सबक्लास का है तो true, अन्यथा false.

## टिप्पणी

जाँचें कि क्या ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक इंस्टेंस प्रतिनिधित्व करता है। C# 'is' ऑपरेटर का समान।

## संबंधित देखें

* क्लास [TypeInfo](../../../system/typeinfo/)
* क्लास [Details_SerializationException](../)
* नेमस्पेस [System::Runtime::Serialization](../../)
* लाइब्रेरी [Aspose.Slides](../../../)