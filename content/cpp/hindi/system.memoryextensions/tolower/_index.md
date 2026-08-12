---
title: ToLower()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट संस्कृति का उपयोग करके अक्षरों को छोटे अक्षर में बदलता है।
type: docs
weight: 443
url: /hi/system.memoryextensions/tolower/
---
## System::MemoryExtensions::ToLower(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) फ़ंक्शन

निर्दिष्ट संस्कृति का उपयोग करके अक्षरों को छोटे अक्षर में बदलता है।

```cpp
int32_t System::MemoryExtensions::ToLower(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | कन्वर्ट करने के लिए स्रोत कैरेक्टर स्पैन |
| destination | [Span](../../system/span/)\<char16_t\>\& | कन्वर्ट किए गए कैरेक्टरों को संग्रहीत करने के लिए गंतव्य स्पैन |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | कन्वर्शन के लिए उपयोग करने वाला कल्चर (वर्तमान कल्चर के लिए nullptr) |

### वापसी मान

कन्वर्ट किए गए कैरेक्टरों की संख्या, या यदि गंतव्य बहुत छोटा हो तो -1

## संबंधित देखें

* Typedef [SharedPtr](../../system/sharedptr/)
* क्लास [ReadOnlySpan](../../system/readonlyspan/)
* क्लास [Span](../../system/span/)
* क्लास [CultureInfo](../../system.globalization/cultureinfo/)
* नेमस्पेस [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)