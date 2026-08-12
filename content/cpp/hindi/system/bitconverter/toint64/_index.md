---
title: ToInt64()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट ऐरे से, निर्दिष्ट सूचकांक से शुरू करके, आठ बाइट्स को 64-बिट पूर्णांक मान में परिवर्तित करता है।
type: docs
weight: 79
url: /hi/system/bitconverter/toint64/
---
## BitConverter::ToInt64(const System::ArrayPtr\<uint8_t\>\&, int) विधि

निर्दिष्ट ऐरे से, निर्दिष्ट सूचकांक से शुरू होकर, आठ बाइट्स को 64-बिट पूर्णांक मान में परिवर्तित करता है।

```cpp
static int64_t System::BitConverter::ToInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) जिसमें बाइट्स को परिवर्तित करने के लिए होते हैं |
| startIndex | int | [Index](../../index/) ऐरे में वह स्थान जहाँ से बाइट्स को परिवर्तित करने के लिए लेना शुरू किया जाता है |

### वापसी मान

64-बिट पूर्णांक मान जो रूपांतरण से प्राप्त होता है

## BitConverter::ToInt64(const System::Details::ArrayView\<uint8_t\>\&, int) विधि

निर्दिष्ट ऐरे से, निर्दिष्ट सूचकांक से शुरू होकर, आठ बाइट्स को 64-बिट पूर्णांक मान में परिवर्तित करता है।

```cpp
static int64_t System::BitConverter::ToInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView जिसमें बाइट्स को परिवर्तित करने के लिए होते हैं |
| startIndex | int | [Index](../../index/) ऐरे में वह स्थान जहाँ से बाइट्स को परिवर्तित करने के लिए लेना शुरू किया जाता है |

### वापसी मान

64-बिट पूर्णांक मान जो रूपांतरण से प्राप्त होता है

## संबंधित देखें

* टाइपडिफ़ [ArrayPtr](../../arrayptr/)
* क्लास [BitConverter](../)
* नेमस्पेस [System](../../)
* पुस्तकालय [Aspose.Slides](../../../)