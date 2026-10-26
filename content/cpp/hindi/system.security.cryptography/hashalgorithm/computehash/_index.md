---
title: ComputeHash()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: बफ़र को हैश करता है।
type: docs
weight: 14
url: /hi/system.security.cryptography/hashalgorithm/computehash/
---
## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&) method

बफ़र को हैश करता है।

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | स्रोत बफ़र। |

### वापसी मान

गणना किया गया हैश मान।

## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&, int, int) method

बफ़र स्लाइस को हैश करता है।

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer, int offset, int count)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | स्रोत बफ़र। |
| offset | int | स्रोत बफ़र में ऑफ़सेट। |
| count | int | स्रोत बफ़र से उपयोग की जाने वाली बाइट्स की संख्या। |

### वापसी मान

गणना किया गया हैश मान।

## HashAlgorithm::ComputeHash(SharedPtr\<IO::Stream\> const\&) method

स्ट्रीम को अंत तक पढ़ता है और पढ़े गये डेटा के लिए हैश की गणना करता है।

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(SharedPtr<IO::Stream> const &inputStream)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| inputStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> const\& | डेटा पढ़ने के लिए स्ट्रीम। |

### वापसी मान

पूरा स्ट्रीम डेटा के लिए गणना किया गया हैश मान।

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HashAlgorithm](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)