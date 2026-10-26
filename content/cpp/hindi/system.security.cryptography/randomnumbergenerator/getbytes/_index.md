---
title: GetBytes()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: मौजूदा ऐरे तत्वों को रैंडम बाइट्स से भरता है।
type: docs
weight: 14
url: /hi/system.security.cryptography/randomnumbergenerator/getbytes/
---
## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>) मेथड


मौजूदा ऐरे तत्वों को रैंडम बाइट्स से भरता है।

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | भरण हेतु बाइट्स ऐरे। |

## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>, int, int) मेथड


मौजूदा ऐरे स्लाइस को रैंडम बाइट्स से भरता है।

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes, int offset, int count)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | भरण हेतु बाइट्स ऐरे स्लाइस। |
| offset | int | स्लाइस की प्रारम्भिक इंडेक्स। |
| count | int | स्लाइस का आकार। |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>) मेथड


मौजूदा ऐरे व्यू तत्वों को रैंडम बाइट्स से भरता है।

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | भरण हेतु बाइट्स ऐरे व्यू। |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>, int, int) मेथड


मौजूदा ऐरे व्यू स्लाइस को रैंडम बाइट्स से भरता है।

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes, int offset, int count)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | भरण हेतु बाइट्स ऐरे व्यू स्लाइस। |
| offset | int | स्लाइस की प्रारम्भिक इंडेक्स। |
| count | int | स्लाइस का आकार। |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&) मेथड


मौजूदा स्टैक ऐरे तत्वों को रैंडम बाइट्स से भरता है।

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | भरण हेतु बाइट्स स्टैक ऐरे। |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&, int, int) मेथड


मौजूदा स्टैक ऐरे स्लाइस को रैंडम बाइट्स से भरता है।

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes, int offset, int count)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | भरण हेतु बाइट्स स्टैक ऐरे स्लाइस। |
| offset | int | स्लाइस की प्रारम्भिक इंडेक्स। |
| count | int | स्लाइस का आकार। |

## संबंधित देखें

* टाइपडैफ़ [ArrayPtr](../../../system/arrayptr/)
* क्लास [RandomNumberGenerator](../)
* नामस्थान [System::Security::Cryptography](../../)
* लाइब्रेरी [Aspose.Slides](../../../)