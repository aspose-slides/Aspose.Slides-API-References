---
title: GetByteCount()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक अक्षर बफ़र को एन्कोड करने के लिए आवश्यक अक्षरों की संख्या प्राप्त करें।
type: docs
weight: 235
url: /hi/system.text/encoding/getbytecount/
---
## Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) method

एक अक्षर बफ़र को एन्कोड करने के लिए आवश्यक अक्षरों की संख्या प्राप्त करें।

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | अक्षर बफ़र। |
| index | int | स्लाइस की शुरुआत। |
| count | int | स्लाइस आकार। |

### वापसी मान

आवश्यक बफ़र आकार।

## Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) method

एक अक्षर बफ़र को एन्कोड करने के लिए आवश्यक अक्षरों की संख्या प्राप्त करें।

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | अक्षर बफ़र। |
| index | int | स्लाइस की शुरुआत। |
| count | int | स्लाइस आकार। |

### वापसी मान

आवश्यक बफ़र आकार।

## Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) method

एक अक्षर बफ़र को एन्कोड करने के लिए आवश्यक अक्षरों की संख्या प्राप्त करें।

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | अक्षर बफ़र। |
| index | int | स्लाइस की शुरुआत। |
| count | int | स्लाइस आकार। |

### वापसी मान

आवश्यक बफ़र आकार।

## Encoding::GetByteCount(const String\&) method

एक स्ट्रिंग को एन्कोड करने के लिए आवश्यक अक्षरों की संख्या प्राप्त करें।

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) को एन्कोड करने के लिए। |

### वापसी मान

आवश्यक बफ़र आकार।

## Encoding::GetByteCount(ArrayPtr\<char_t\>) method

एक अक्षर बफ़र को एन्कोड करने के लिए आवश्यक अक्षरों की संख्या प्राप्त करें।

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | अक्षर बफ़र। |

### वापसी मान

आवश्यक बफ़र आकार।

## Encoding::GetByteCount(const char_t *, int) method

एक अक्षर बफ़र को एन्कोड करने के लिए आवश्यक अक्षरों की संख्या प्राप्त करें।

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chars | const char_t * | अक्षर बफ़र। |
| count | int | [Buffer](../../../system/buffer/) आकार। |

### वापसी मान

आवश्यक बफ़र आकार।

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoding](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)