---
title: GetByteCount()
second_title: Aspose.Slides for C++ API संदर्भ
description: किसी कैरेक्टर बफ़र को एन्कोड करने के लिए आवश्यक अक्षरों की संख्या प्राप्त करें।
type: docs
weight: 27
url: /hi/system.text/icuencoding/getbytecount/
---
## ICUEncoding::GetByteCount(const char_t *, int) विधि

एक कैरेक्टर बफ़र को एन्कोड करने के लिए आवश्यक अक्षरों की संख्या प्राप्त करें।

```cpp
int System::Text::ICUEncoding::GetByteCount(const char_t *chars, int count) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| chars | const char_t * | Characters buffer. |
| count | int | [Buffer](../../../system/buffer/) आकार। |

### वापसी मान

आवश्यक बफ़र आकार।

## ICUEncoding::GetByteCount(ArrayPtr\<char_t\>, int, int) विधि

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

## ICUEncoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) विधि

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

## ICUEncoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) विधि

RTTI.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

## ICUEncoding::GetByteCount(const String\&) विधि

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

## ICUEncoding::GetByteCount(ArrayPtr\<char_t\>) विधि

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

## ICUEncoding::GetByteCount(const char_t *, int) विधि

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [ICUEncoding](../)
* क्लास [String](../../../system/string/)
* नेमस्पेस [System::Text](../../)
* Library [Aspose.Slides](../../../)