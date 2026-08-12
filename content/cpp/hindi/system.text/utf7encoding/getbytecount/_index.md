---
title: GetByteCount()
second_title: Aspose.Slides for C++ API संदर्भ
description: अक्षर बफ़र को एन्कोड करने के लिए आवश्यक अक्षरों की संख्या प्राप्त करें।
type: docs
weight: 157
url: /hi/system.text/utf7encoding/getbytecount/
---
## UTF7Encoding::GetByteCount(const char_t *, int) विधि

एक अक्षर बफ़र को एन्कोड करने के लिए आवश्यक अक्षरों की संख्या प्राप्त करें।

```cpp
int System::Text::UTF7Encoding::GetByteCount(const char_t *chars, int count) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chars | const char_t * | अक्षरों का बफ़र। |
| count | int | [Buffer](../../../system/buffer/) आकार। |

### रिटर्न वैल्यू

आवश्यक बफ़र आकार।

## UTF7Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) विधि

एक अक्षर बफ़र को एन्कोड करने के लिए आवश्यक अक्षरों की संख्या प्राप्त करें।

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | अक्षरों का बफ़र। |
| index | int | स्लाइस की शुरुआत। |
| count | int | स्लाइस का आकार। |

### रिटर्न वैल्यू

आवश्यक बफ़र आकार।

## UTF7Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) विधि

एक अक्षर बफ़र को एन्कोड करने के लिए आवश्यक अक्षरों की संख्या प्राप्त करें।

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | अक्षरों का बफ़र। |
| index | int | स्लाइस की शुरुआत। |
| count | int | स्लाइस का आकार। |

### रिटर्न वैल्यू

आवश्यक बफ़र आकार।

## UTF7Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) विधि

एक अक्षर बफ़र को एन्कोड करने के लिए आवश्यक अक्षरों की संख्या प्राप्त करें।

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | अक्षरों का बफ़र। |
| index | int | स्लाइस की शुरुआत। |
| count | int | स्लाइस का आकार। |

### रिटर्न वैल्यू

आवश्यक बफ़र आकार।

## UTF7Encoding::GetByteCount(const String\&) विधि

एक स्ट्रिंग को एन्कोड करने के लिए आवश्यक अक्षरों की संख्या प्राप्त करें।

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) को एन्कोड करने के लिए। |

### रिटर्न वैल्यू

आवश्यक बफ़र आकार।

## UTF7Encoding::GetByteCount(ArrayPtr\<char_t\>) विधि

एक अक्षर बफ़र को एन्कोड करने के लिए आवश्यक अक्षरों की संख्या प्राप्त करें।

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | अक्षरों का बफ़र। |

### रिटर्न वैल्यू

आवश्यक बफ़र आकार।

## UTF7Encoding::GetByteCount(const char_t *, int) विधि

एक अक्षर बफ़र को एन्कोड करने के लिए आवश्यक अक्षरों की संख्या प्राप्त करें।

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chars | const char_t * | अक्षरों का बफ़र। |
| count | int | [Buffer](../../../system/buffer/) आकार। |

### रिटर्न वैल्यू

आवश्यक बफ़र आकार।

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [UTF7Encoding](../)
* क्लास [String](../../../system/string/)
* नेमस्पेस [System::Text](../../)
* लाइब्रेरी [Aspose.Slides](../../../)