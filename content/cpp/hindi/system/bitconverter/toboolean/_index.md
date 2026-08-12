---
title: ToBoolean()
second_title: Aspose.Slides C++ के लिए API रेफ़रेंस
description: निर्दिष्ट इंडेक्स से शुरू होने वाले निर्दिष्ट एरे से एक बाइट को बूलियन मान में परिवर्तित करता है।
type: docs
weight: 27
url: /hi/system/bitconverter/toboolean/
---
## BitConverter::ToBoolean(const System::ArrayPtr\<uint8_t\>\&, int) मेथड


निर्दिष्ट इंडेक्स से शुरू होने वाले निर्दिष्ट एरे से एक बाइट को बूलियन मान में परिवर्तित करता है।

```cpp
static bool System::BitConverter::ToBoolean(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) that contains bytes to convert |
| startIndex | int | [Index](../../index/) in the array at which to start taking bytes for conversion |

### रिटर्न वैल्यू

[Boolean](../../boolean/) value resulting from conversion

## BitConverter::ToBoolean(const System::Details::ArrayView\<uint8_t\>\&, int) मेथड


निर्दिष्ट इंडेक्स से शुरू होने वाले निर्दिष्ट एरे से एक बाइट को बूलियन मान में परिवर्तित करता है।

```cpp
static bool System::BitConverter::ToBoolean(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView जो बाइट्स को परिवर्तित करने के लिए रखता है |
| startIndex | int | [Index](../../index/) in the array at which to start taking bytes for conversion |

### रिटर्न वैल्यू

[Boolean](../../boolean/) value resulting from conversion

## सम्बंधित देखें

* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)