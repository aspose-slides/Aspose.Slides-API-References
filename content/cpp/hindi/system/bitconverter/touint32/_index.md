---
title: ToUInt32()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: निर्दिष्ट ऐरे से निर्दिष्ट इंडेक्स से शुरू होकर चार बाइट्स को अनसाइनड 32-बिट पूर्णांक मान में बदलता है।
type: docs
weight: 105
url: /hi/system/bitconverter/touint32/
---
## BitConverter::ToUInt32(const System::ArrayPtr\<uint8_t\>\&, int) method

निर्दिष्ट ऐरे से निर्दिष्ट इंडेक्स से शुरू होकर चार बाइट्स को अनसाइनड 32-बिट पूर्णांक मान में बदलता है।

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) जो बाइट्स को परिवर्तित करने के लिये रखता है |
| startIndex | int | [Index](../../index/) वह इंडेक्स है जहाँ से बाइट्स को परिवर्तित करने के लिये लेना शुरू किया जाता है |

### रिटर्न वैल्यू

परिवर्तन द्वारा प्राप्त अनसाइनड 32-बिट पूर्णांक मान

## BitConverter::ToUInt32(const System::Details::ArrayView\<uint8_t\>\&, int) method

निर्दिष्ट ऐरे से निर्दिष्ट इंडेक्स से शुरू होकर चार बाइट्स को अनसाइनड 32-बिट पूर्णांक मान में बदलता है।

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView जो बाइट्स को परिवर्तित करने के लिये रखता है |
| startIndex | int | [Index](../../index/) वह इंडेक्स है जहाँ से बाइट्स को परिवर्तित करने के लिये लेना शुरू किया जाता है |

### रिटर्न वैल्यू

परिवर्तन द्वारा प्राप्त अनसाइनड 32-बिट पूर्णांक मान

## संबंधित देखें

* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)