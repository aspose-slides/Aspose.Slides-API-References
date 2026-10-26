---
title: GetBytes()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप प्राप्त बाइट्स।
type: docs
weight: 40
url: /hi/system.text/icuencoding/getbytes/
---
## ICUEncoding::GetBytes(const char_t *, int, uint8_t *, int) मेथड


एक कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप प्राप्त बाइट्स।

```cpp
int System::Text::ICUEncoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count) override
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| chars | const char_t * | Characters to encode. |
| char_count | int | Number of characters to convert. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) को अक्षर रखने के लिए। |
| byte_count | int | Output buffer size. |

### वापसी मान

लिखे गए बाइट्स की संख्या।

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) मेथड


एक कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप प्राप्त बाइट्स।

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Characters to encode. |
| char_index | int | Character slice beginning. |
| char_count | int | Number of characters to convert. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) को अक्षर रखने के लिए। |
| byte_index | int | Output buffer offset. |

### वापसी मान

लिखे गए बाइट्स की संख्या।

## ICUEncoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) मेथड


एक कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप प्राप्त बाइट्स।

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Characters to encode. |
| char_index | int | Character slice beginning. |
| char_count | int | Number of characters to convert. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) को अक्षर रखने के लिए। |
| byte_index | int | Output buffer offset. |

### वापसी मान

लिखे गए बाइट्स की संख्या।

## ICUEncoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) मेथड


एक कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप प्राप्त बाइट्स।

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | Characters to encode. |
| char_index | int | Character slice beginning. |
| char_count | int | Number of characters to convert. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) को अक्षर रखने के लिए। |
| byte_index | int | Output buffer offset. |

### वापसी मान

लिखे गए बाइट्स की संख्या।

## ICUEncoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) मेथड


एक कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप प्राप्त बाइट्स।

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) एन्कोड करने के लिए। |
| char_index | int | Character slice beginning. |
| char_count | int | Number of characters to convert. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) को अक्षर रखने के लिए। |
| byte_index | int | Output buffer offset. |

### वापसी मान

लिखे गए बाइट्स की संख्या।

## ICUEncoding::GetBytes(const String\&) मेथड


एक कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप प्राप्त बाइट्स।

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) एन्कोड करने के लिए। |

### वापसी मान

[Buffer](../../../system/buffer/) जो एन्कोड किए जा रहे अक्षरों का प्रतिनिधित्व रखता है।

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>, int, int) मेथड


एक कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप प्राप्त बाइट्स।

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Characters to encode. |
| index | int | Character slice beginning. |
| count | int | Number of characters to convert. |

### वापसी मान

[Buffer](../../../system/buffer/) जो एन्कोड किए जा रहे अक्षरों का प्रतिनिधित्व रखता है।

## ICUEncoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) मेथड


एक कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप प्राप्त बाइट्स।

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | Characters to encode. |
| index | int | Character slice beginning. |
| count | int | Number of characters to convert. |

### वापसी मान

[Buffer](../../../system/buffer/) जो एन्कोड किए जा रहे अक्षरों का प्रतिनिधित्व रखता है।

## ICUEncoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) मेथड


एक कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप प्राप्त बाइट्स।

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Characters to encode. |
| index | int | Character slice beginning. |
| count | int | Number of characters to convert. |

### वापसी मान

[Buffer](../../../system/buffer/) जो एन्कोड किए जा रहे अक्षरों का प्रतिनिधित्व रखता है।

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>) मेथड


एक कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप प्राप्त बाइट्स।

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Characters to encode. |

### वापसी मान

[Buffer](../../../system/buffer/) जो एन्कोड किए जा रहे अक्षरों का प्रतिनिधित्व रखता है।

## ICUEncoding::GetBytes(const char_t *, int, uint8_t *, int) मेथड


एक कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप प्राप्त बाइट्स।

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| chars | const char_t * | Characters to encode. |
| char_count | int | Number of characters to convert. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) को अक्षर रखने के लिए। |
| byte_count | int | Output buffer size. |

### वापसी मान

लिखे गए बाइट्स की संख्या।

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)