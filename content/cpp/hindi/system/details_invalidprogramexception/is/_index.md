---
title: Is()
second_title: Aspose.Slides for C++ API संदर्भ
description: 
type: docs
weight: 27
url: /hi/system/details_invalidprogramexception/is/
---
## विवरण_InvalidProgramException::Is(const System::TypeInfo\&) const विधि

```cpp
bool System::Details_InvalidProgramException::Is(const System::TypeInfo &target) const override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) संरचना जो उस प्रकार का वर्णन करती है जिसका परीक्षण वर्तमान वस्तु के विरुद्ध किया जाता है। |

### रिटर्न वैल्यू

यदि वस्तु टैग किए गए प्रकार या उसकी उप-क्लास की है तो सही, अन्यथा गलत।

## टिप्पणी

जाँचें कि वस्तु targetType द्वारा वर्णित प्रकार का एक उदाहरण दर्शाता है या नहीं। C# के 'is' ऑपरेटर का समानांतर।

## देखें

* क्लास [TypeInfo](../../typeinfo/)
* क्लास [Details_InvalidProgramException](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)