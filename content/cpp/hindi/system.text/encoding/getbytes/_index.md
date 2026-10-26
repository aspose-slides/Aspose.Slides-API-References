---
title: GetBytes()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक अक्षर बफ़र को एन्कोड करने से प्राप्त बाइट्स प्राप्त करें।
type: docs
weight: 248
url: /hi/system.text/encoding/getbytes/
---
## Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) मेथड

एक अक्षर बफ़र को एन्कोड करने से प्राप्त बाइट्स प्राप्त करें।

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### आर्ग्यूमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | एन्कोड करने के लिए अक्षर। |
| char_index | int | अक्षर स्लाइस की शुरुआत। |
| char_count | int | परिवर्तित करने के लिए अक्षरों की संख्या। |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) अक्षरों को रखने के लिए। |
| byte_index | int | आउटपुट बफ़र का ऑफ़सेट। |

### रिटर्न वैल्यू

लिखे गए बाइट्स की संख्या।

## Encoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) मेथड

एक अक्षर बफ़र को एन्कोड करने से प्राप्त बाइट्स प्राप्त करें।

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```

### आर्ग्यूमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | एन्कोड करने के लिए अक्षर। |
| char_index | int | अक्षर स्लाइस की शुरुआत। |
| char_count | int | परिवर्तित करने के लिए अक्षरों की संख्या। |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) अक्षरों को रखने के लिए। |
| byte_index | int | आउटपुट बफ़र का ऑफ़सेट। |

### रिटर्न वैल्यू

लिखे गए बाइट्स की संख्या।

## Encoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) मेथड

एक अक्षर बफ़र को एन्कोड करने से प्राप्त बाइट्स प्राप्त करें।

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```

### आर्ग्यूमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | एन्कोड करने के लिए अक्षर। |
| char_index | int | अक्षर स्लाइस की शुरुआत। |
| char_count | int | परिवर्तित करने के लिए अक्षरों की संख्या। |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) अक्षरों को रखने के लिए। |
| byte_index | int | आउटपुट बफ़र का ऑफ़सेट। |

### रिटर्न वैल्यू

लिखे गए बाइट्स की संख्या।

## Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) मेथड

एक अक्षर बफ़र को एन्कोड करने से प्राप्त बाइट्स प्राप्त करें।

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### आर्ग्यूमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) एन्कोड करने के लिए। |
| char_index | int | अक्षर स्लाइस की शुरुआत। |
| char_count | int | परिवर्तित करने के लिए अक्षरों की संख्या। |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) अक्षरों को रखने के लिए। |
| byte_index | int | आउटपुट बफ़र का ऑफ़सेट। |

### रिटर्न वैल्यू

लिखे गए बाइट्स की संख्या।

## Encoding::GetBytes(const String\&) मेथड

एक अक्षर बफ़र को एन्कोड करने से प्राप्त बाइट्स प्राप्त करें।

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```

### आर्ग्यूमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) एन्कोड करने के लिए। |

### रिटर्न वैल्यू

[Buffer](../../../system/buffer/) जो एन्कोड किए जा रहे अक्षरों का प्रतिनिधित्व रखता है।

## Encoding::GetBytes(ArrayPtr\<char_t\>, int, int) मेथड

एक अक्षर बफ़र को एन्कोड करने से प्राप्त बाइट्स प्राप्त करें।

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```

### आर्ग्यूमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | एन्कोड करने के लिए अक्षर। |
| index | int | अक्षर स्लाइस की शुरुआत। |
| count | int | परिवर्तित करने के लिए अक्षरों की संख्या। |

### रिटर्न वैल्यू

[Buffer](../../../system/buffer/) जो एन्कोड किए जा रहे अक्षरों का प्रतिनिधित्व रखता है।

## Encoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) मेथड

एक अक्षर बफ़र को एन्कोड करने से प्राप्त बाइट्स प्राप्त करें।

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```

### आर्ग्यूमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | एन्कोड करने के लिए अक्षर। |
| index | int | अक्षर स्लाइस की शुरुआत। |
| count | int | परिवर्तित करने के लिए अक्षरों की संख्या। |

### रिटर्न वैल्यू

[Buffer](../../../system/buffer/) जो एन्कोड किए जा रहे अक्षरों का प्रतिनिधित्व रखता है।

## Encoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) मेथड

एक अक्षर बफ़र को एन्कोड करने से प्राप्त बाइट्स प्राप्त करें।

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### आर्ग्यूमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | एन्कोड करने के लिए अक्षर। |
| index | int | अक्षर स्लाइस की शुरुआत। |
| count | int | परिवर्तित करने के लिए अक्षरों की संख्या। |

### रिटर्न वैल्यू

[Buffer](../../../system/buffer/) जो एन्कोड किए जा रहे अक्षरों का प्रतिनिधित्व रखता है।

## Encoding::GetBytes(ArrayPtr\<char_t\>) मेथड

एक अक्षर बफ़र को एन्कोड करने से प्राप्त बाइट्स प्राप्त करें।

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```

### आर्ग्यूमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | एन्कोड करने के लिए अक्षर। |

### रिटर्न वैल्यू

[Buffer](../../../system/buffer/) जो एन्कोड किए जा रहे अक्षरों का प्रतिनिधित्व रखता है।

## Encoding::GetBytes(const char_t *, int, uint8_t *, int) मेथड

एक अक्षर बफ़र को एन्कोड करने से प्राप्त बाइट्स प्राप्त करें।

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```

### आर्ग्यूमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | एन्कोड करने के लिए अक्षर। |
| char_count | int | परिवर्तित करने के लिए अक्षरों की संख्या। |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) अक्षरों को रखने के लिए। |
| byte_count | int | आउटपुट बफ़र का आकार। |

### रिटर्न वैल्यू

लिखे गए बाइट्स की संख्या।

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [Encoding](../)
* क्लास [String](../../../system/string/)
* नामस्थान [System::Text](../../)
* Library [Aspose.Slides](../../../)