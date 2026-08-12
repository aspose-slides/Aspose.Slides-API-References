---
title: GetBytes()
second_title: Aspose.Slides for C++ API संदर्भ
description: किसी कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप उत्पन्न बाइट्स प्राप्त करें।
type: docs
weight: 66
url: /hi/system.text/utf7encoding/getbytes/
---
## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) मेथड

किसी कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप बाइट्स प्राप्त करें।

```cpp
int System::Text::UTF7Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index) override
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | एन्कोड करने के लिए कैरैक्टर। |
| char_index | int | कैरैक्टर स्लाइस की शुरुआत। |
| char_count | int | परिवर्तित करने के लिए कैरैक्टरों की संख्या। |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) जिसमें कैरैक्टर रखे जाएँ। |
| byte_index | int | आउटपुट बफ़र ऑफसेट। |

### रिटर्न वैल्यू

लिखी गई बाइट्स की संख्या।

## UTF7Encoding::GetBytes(const char_t *, int, uint8_t *, int) मेथड

किसी कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप बाइट्स प्राप्त करें।

```cpp
int System::Text::UTF7Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count) override
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chars | const char_t * | एन्कोड करने के लिए कैरैक्टर। |
| char_count | int | परिवर्तित करने के लिए कैरैक्टरों की संख्या। |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) जिसमें कैरैक्टर रखे जाएँ। |
| byte_count | int | आउटपुट बफ़र आकार। |

### रिटर्न वैल्यू

लिखी गई बाइट्स की संख्या।

## UTF7Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) मेथड

किसी कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप बाइट्स प्राप्त करें।

```cpp
int System::Text::UTF7Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index) override
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) को एन्कोड करने के लिए। |
| char_index | int | कैरैक्टर स्लाइस की शुरुआत। |
| char_count | int | परिवर्तित करने के लिए कैरैक्टरों की संख्या। |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) जिसमें कैरैक्टर रखे जाएँ। |
| byte_index | int | आउटपुट बफ़र ऑफसेट। |

### रिटर्न वैल्यू

लिखी गई बाइट्स की संख्या।

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) मेथड

किसी कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप बाइट्स प्राप्त करें।

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | एन्कोड करने के लिए कैरैक्टर। |
| char_index | int | कैरैक्टर स्लाइस की शुरुआत। |
| char_count | int | परिवर्तित करने के लिए कैरैक्टरों की संख्या। |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) जिसमें कैरैक्टर रखे जाएँ। |
| byte_index | int | आउटपुट बफ़र ऑफसेट। |

### रिटर्न वैल्यू

लिखी गई बाइट्स की संख्या।

## UTF7Encoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) मेथड

किसी कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप बाइट्स प्राप्त करें।

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | एन्कोड करने के लिए कैरैक्टर। |
| char_index | int | कैरैक्टर स्लाइस की शुरुआत। |
| char_count | int | परिवर्तित करने के लिए कैरैक्टरों की संख्या। |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) जिसमें कैरैक्टर रखे जाएँ। |
| byte_index | int | आउटपुट बफ़र ऑफसेट। |

### रिटर्न वैल्यू

लिखी गई बाइट्स की संख्या।

## UTF7Encoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) मेथड

किसी कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप बाइट्स प्राप्त करें।

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | एन्कोड करने के लिए कैरैक्टर। |
| char_index | int | कैरैक्टर स्लाइस की शुरुआत। |
| char_count | int | परिवर्तित करने के लिए कैरैक्टरों की संख्या। |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) जिसमें कैरैक्टर रखे जाएँ। |
| byte_index | int | आउटपुट बफ़र ऑफसेट। |

### रिटर्न वैल्यू

लिखी गई बाइट्स की संख्या।

## UTF7Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) मेथड

किसी कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप बाइट्स प्राप्त करें।

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) को एन्कोड करने के लिए। |
| char_index | int | कैरैक्टर स्लाइस की शुरुआत। |
| char_count | int | परिवर्तित करने के लिए कैरैक्टरों की संख्या। |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) जिसमें कैरैक्टर रखे जाएँ। |
| byte_index | int | आउटपुट बफ़र ऑफसेट। |

### रिटर्न वैल्यू

लिखी गई बाइट्स की संख्या।

## UTF7Encoding::GetBytes(const String\&) मेथड

किसी कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप बाइट्स प्राप्त करें।

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) को एन्कोड करने के लिए। |

### रिटर्न वैल्यू

[Buffer](../../../system/buffer/) जिसमें एन्कोड किए जा रहे कैरैक्टरों का प्रतिनिधित्व है।

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int) मेथड

किसी कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप बाइट्स प्राप्त करें।

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | एन्कोड करने के लिए कैरैक्टर। |
| index | int | कैरैक्टर स्लाइस की शुरुआत। |
| count | int | परिवर्तित करने के लिए कैरैक्टरों की संख्या। |

### रिटर्न वैल्यू

[Buffer](../../../system/buffer/) जिसमें एन्कोड किए जा रहे कैरैक्टरों का प्रतिनिधित्व है।

## UTF7Encoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) मेथड

किसी कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप बाइट्स प्राप्त करें।

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | एन्कोड करने के लिए कैरैक्टर। |
| index | int | कैरैक्टर स्लाइस की शुरुआत। |
| count | int | परिवर्तित करने के लिए कैरैक्टरों की संख्या। |

### रिटर्न वैल्यू

[Buffer](../../../system/buffer/) जिसमें एन्कोड किए जा रहे कैरैक्टरों का प्रतिनिधित्व है।

## UTF7Encoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) मेथड

किसी कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप बाइट्स प्राप्त करें।

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | एन्कोड करने के लिए कैरैक्टर। |
| index | int | कैरैक्टर स्लाइस की शुरुआत। |
| count | int | परिवर्तित करने के लिए कैरैक्टरों की संख्या। |

### रिटर्न वैल्यू

[Buffer](../../../system/buffer/) जिसमें एन्कोड किए जा रहे कैरैक्टरों का प्रतिनिधित्व है।

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>) मेथड

किसी कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप बाइट्स प्राप्त करें।

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | एन्कोड करने के लिए कैरैक्टर। |

### रिटर्न वैल्यू

[Buffer](../../../system/buffer/) जिसमें एन्कोड किए जा रहे कैरैक्टरों का प्रतिनिधित्व है।

## UTF7Encoding::GetBytes(const char_t *, int, uint8_t *, int) मेथड

किसी कैरेक्टर बफ़र को एन्कोड करने के परिणामस्वरूप बाइट्स प्राप्त करें।

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chars | const char_t * | एन्कोड करने के लिए कैरैक्टर। |
| char_count | int | परिवर्तित करने के लिए कैरैक्टरों की संख्या। |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) जिसमें कैरैक्टर रखे जाएँ। |
| byte_count | int | आउटपुट बफ़र आकार। |

### रिटर्न वैल्यू

लिखी गई बाइट्स की संख्या।

## देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UTF7Encoding](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)