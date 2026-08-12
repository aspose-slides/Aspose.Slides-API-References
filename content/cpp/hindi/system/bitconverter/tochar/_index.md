---
title: ToChar()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट इंडेक्स से शुरू होकर निर्दिष्ट array से दो बाइट्स को char_t मान में परिवर्तित करता है।
type: docs
weight: 40
url: /hi/system/bitconverter/tochar/
---
## BitConverter::ToChar(const System::ArrayPtr\<uint8_t\>\&, int) मेथड

निर्दिष्ट इंडेक्स से शुरू होकर निर्दिष्ट array से दो बाइट्स को char_t मान में परिवर्तित करता है।

```cpp
static char_t System::BitConverter::ToChar(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) जिसमें बाइट्स को परिवर्तित किया जाता है |
| startIndex | int | [Index](../../index/) array में बाइट्स को परिवर्तित करने के लिए शुरू करने का इंडेक्स |

### रिटर्न मान

char_t value परिवर्तन से प्राप्त मान

## BitConverter::ToChar(const System::Details::ArrayView\<uint8_t\>\&, int) मेथड

निर्दिष्ट इंडेक्स से शुरू होकर निर्दिष्ट array से दो बाइट्स को char_t मान में परिवर्तित करता है।

```cpp
static char_t System::BitConverter::ToChar(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView जिसमें बाइट्स को परिवर्तित करने के लिए रखे गए हैं |
| startIndex | int | [Index](../../index/) array में बाइट्स को परिवर्तित करने के लिए शुरू करने का इंडेक्स |

### रिटर्न मान

char_t value परिवर्तन से प्राप्त मान

## देखें

* Typedef [ArrayPtr](../../arrayptr/)
* क्लास [BitConverter](../)
* नामस्थान [System](../../)
* Library [Aspose.Slides](../../../)