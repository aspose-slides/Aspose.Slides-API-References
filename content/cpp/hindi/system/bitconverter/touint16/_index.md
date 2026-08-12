---
title: ToUInt16()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट एरे में निर्दिष्ट इंडेक्स से शुरू होते हुए दो बाइट्स को unsigned 16-bit integer मान में परिवर्तित करता है।
type: docs
weight: 92
url: /hi/system/bitconverter/touint16/
---
## BitConverter::ToUInt16(const System::ArrayPtr\<uint8_t\>\&, int) मेथड

निर्दिष्ट एरे में निर्दिष्ट इंडेक्स से शुरू होकर दो बाइटों को unsigned 16-bit integer मान में परिवर्तित करता है।

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### आर्ग्युमेंट्स

| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) जो बाइट्स को परिवर्तित करने के लिये रखती है |
| startIndex | int | [Index](../../index/) एरे में वह स्थान जहाँ से बाइट्स को परिवर्तित करने के लिये लेना शुरू किया जाना है |

### वापसी मान

Unsigned 16-bit integer value resulting from conversion

## BitConverter::ToUInt16(const System::Details::ArrayView\<uint8_t\>\&, int) मेथड

निर्दिष्ट एरे में निर्दिष्ट इंडेक्स से शुरू होकर दो बाइटों को unsigned 16-bit integer मान में परिवर्तित करता है।

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### आर्ग्युमेंट्स

| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView जो बाइट्स को परिवर्तित करने के लिये रखती है |
| startIndex | int | [Index](../../index/) एरे में वह स्थान जहाँ से बाइट्स को परिवर्तित करने के लिये लेना शुरू किया जाना है |

### वापसी मान

Unsigned 16-bit integer value resulting from conversion

## संबंधित देखें

* Typedef [ArrayPtr](../../arrayptr/)
* क्लास [BitConverter](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)