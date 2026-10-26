---
title: ToUInt64()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट एरे में से निर्दिष्ट इंडेक्स से शुरू होते हुए आठ बाइट्स को unsigned 64-bit integer मान में परिवर्तित करता है।
type: docs
weight: 118
url: /hi/system/bitconverter/touint64/
---
## BitConverter::ToUInt64(const System::ArrayPtr\<uint8_t\>\&, int) मेथड

निर्दिष्ट एरे में से निर्दिष्ट इंडेक्स से शुरू होते हुए आठ बाइट्स को unsigned 64-bit integer मान में परिवर्तित करता है।

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) जो बाइट्स को परिवर्तित करने के लिए शामिल करता है |
| startIndex | int | [Index](../../index/) ऐरे में वह इंडेक्स जहाँ बाइट्स को परिवर्तित करने के लिए लेना शुरू किया जाता है |

### रिटर्न मान

परिवर्तन से प्राप्त unsigned 64-bit integer मान

## BitConverter::ToUInt64(const System::Details::ArrayView\<uint8_t\>\&, int) मेथड

निर्दिष्ट एरे में से निर्दिष्ट इंडेक्स से शुरू होते हुए आठ बाइट्स को unsigned 64-bit integer मान में परिवर्तित करता है।

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView जो बाइट्स को परिवर्तित करने के लिए शामिल करता है |
| startIndex | int | [Index](../../index/) ऐरे में वह इंडेक्स जहाँ बाइट्स को परिवर्तित करने के लिए लेना शुरू किया जाता है |

### रिटर्न मान

परिवर्तन से प्राप्त unsigned 64-bit integer मान

## देखें

* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)