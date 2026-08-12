---
title: ToInt32()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट एरे से निर्दिष्ट इंडेक्स से शुरू होते हुए चार बाइट को 32-बिट पूर्णांक मान में बदलता है।
type: docs
weight: 66
url: /hi/system/bitconverter/toint32/
---
## BitConverter::ToInt32(const System::ArrayPtr\<uint8_t\>\&, int) method


निर्दिष्ट ऐरे से निर्दिष्ट इंडेक्स से शुरू होते हुए चार बाइट को 32-बिट पूर्णांक मान में परिवर्तित करता है।

```cpp
static int System::BitConverter::ToInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) that contains bytes to convert |
| startIndex | int | [Index](../../index/) in the array at which to start taking bytes for conversion |

### वापसी मान

परिवर्तन से प्राप्त 32-बिट पूर्णांक मान

## BitConverter::ToInt32(const System::Details::ArrayView\<uint8_t\>\&, int) method


निर्दिष्ट ऐरे से निर्दिष्ट इंडेक्स से शुरू होते हुए चार बाइट को 32-бिट पूर्णांक मान में परिवर्तित करता है।

```cpp
static int System::BitConverter::ToInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView जिसमें परिवर्तित करने के लिए बाइट्स होते हैं |
| startIndex | int | [Index](../../index/) in the array at which to start taking bytes for conversion |

### वापसी मान

परिवर्तन से प्राप्त 32-बिट पूर्णांक मान

## संबंधित देखें

* Typedef [ArrayPtr](../../arrayptr/)
* क्लास [BitConverter](../)
* नेमस्पेस [System](../../)
* Library [Aspose.Slides](../../../)