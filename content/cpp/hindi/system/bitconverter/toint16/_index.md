---
title: ToInt16()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट एरे से निर्धारित इंडेक्स से शुरू होकर दो बाइट्स को 16-बिट पूर्णांक मान में परिवर्तित करता है।
type: docs
weight: 53
url: /hi/system/bitconverter/toint16/
---
## BitConverter::ToInt16(const System::ArrayPtr\<uint8_t\>\&, int) विधि

निर्दिष्ट एरे से निर्धारित इंडेक्स से शुरू होकर दो बाइट्स को 16-बिट पूर्णांक मान में परिवर्तित करता है।

```cpp
static int16_t System::BitConverter::ToInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### आर्ग्युमेंट्स

| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) जिसमें बाइट्स होते हैं जिन्हें परिवर्तित किया जाता है |
| startIndex | int | [Index](../../index/) एरे में वह स्थान जहाँ से बाइट्स को रूपांतरण के लिए लेना शुरू किया जाता है |

## रिटर्न वैल्यू

रूपांतरण के परिणामस्वरूप प्राप्त 16-बिट पूर्णांक मान

## BitConverter::ToInt16(const System::Details::ArrayView\<uint8_t\>\&, int) विधि

निर्दिष्ट एरे से निर्धारित इंडेक्स से शुरू होकर दो बाइट्स को 16-बिट पूर्णांक मान में परिवर्तित करता है।

```cpp
static int16_t System::BitConverter::ToInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### आर्ग्युमेंट्स

| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView जिसमें बाइट्स होते हैं जिन्हें परिवर्तित किया जाता है |
| startIndex | int | [Index](../../index/) एरे में वह स्थान जहाँ से बाइट्स को रूपांतरण के लिए लेना शुरू किया जाता है |

## रिटर्न वैल्यू

रूपांतरण के परिणामस्वरूप प्राप्त 16-बिट पूर्णांक मान

## देखें

* टाइपडिफ [ArrayPtr](../../arrayptr/)
* क्लास [BitConverter](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)