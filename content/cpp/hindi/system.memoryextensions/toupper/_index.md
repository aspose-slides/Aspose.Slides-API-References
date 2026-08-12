---
title: ToUpper()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट संस्कृति का उपयोग करके अक्षरों को बड़े अक्षरों में बदलता है।
type: docs
weight: 469
url: /hi/system.memoryextensions/toupper/
---
## System::MemoryExtensions::ToUpper(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) फ़ंक्शन

निर्दिष्ट संस्कृति का उपयोग करके अक्षरों को बड़े अक्षरों में बदलता है।

```cpp
int32_t System::MemoryExtensions::ToUpper(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | परिवर्तित करने के लिए स्रोत अक्षर स्पैन |
| destination | [Span](../../system/span/)\<char16_t\>\& | परिवर्तित अक्षरों को संग्रहीत करने के लिए गंतव्य स्पैन |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | रूपांतरण के लिए उपयोग करने वाली संस्कृति (वर्तमान संस्कृति के लिए nullptr) |

### वापसी मान

परिवर्तित अक्षरों की संख्या, या -1 यदि गंतव्य बहुत छोटा है।

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../system/sharedptr/)
* क्लास [ReadOnlySpan](../../system/readonlyspan/)
* क्लास [Span](../../system/span/)
* क्लास [CultureInfo](../../system.globalization/cultureinfo/)
* नामस्थान [System::MemoryExtensions](../)
* लाइब्रेरी [Aspose.Slides](../../)