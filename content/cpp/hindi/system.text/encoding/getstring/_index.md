---
title: GetString()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है।
type: docs
weight: 313
url: /hi/system.text/encoding/getstring/
---
## Encoding::GetString(uint8_t *, int) मेथड

एक बाइट बफ़र को स्ट्रिंग में डिकोड करता है।

```cpp
virtual String System::Text::Encoding::GetString(uint8_t *bytes, int byte_count)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) बाइट्स पढ़ने के लिए। |
| byte_count | int | Input buffer size. |

### रिटर्न वैल्यू

[String](../../../system/string/) डिकोड किए गए अक्षरों का।

## Encoding::GetString(const ReadOnlySpan\<uint8_t\>\&) मेथड

एक बाइट बफ़र को स्ट्रिंग में डिकोड करता है।

```cpp
String System::Text::Encoding::GetString(const ReadOnlySpan<uint8_t> &bytes)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| bytes | const [ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) बाइट्स पढ़ने के लिए। |

### रिटर्न वैल्यू

[String](../../../system/string/) डिकोड किए गए अक्षरों का।

## Encoding::GetString(ArrayPtr\<uint8_t\>) मेथड

एक बाइट बफ़र को स्ट्रिंग में डिकोड करता है।

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) बाइट्स पढ़ने के लिए। |

### रिटर्न वैल्यू

[String](../../../system/string/) डिकोड किए गए अक्षरों का।

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&) मेथड

एक बाइट बफ़र को स्ट्रिंग में डिकोड करता है।

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) बाइट्स पढ़ने के लिए। |

### रिटर्न वैल्यू

[String](../../../system/string/) डिकोड किए गए अक्षरों का।

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>\&) मेथड

एक बाइट बफ़र को स्ट्रिंग में डिकोड करता है।

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> &bytes)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | [Buffer](../../../system/buffer/) बाइट्स पढ़ने के लिए। |

### रिटर्न वैल्यू

[String](../../../system/string/) डिकोड किए गए अक्षरों का।

## Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) मेथड

एक बाइट बफ़र को स्ट्रिंग में डिकोड करता है।

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) बाइट्स पढ़ने के लिए। |
| index | int | Input buffer offset. |
| count | int | Input buffer size. |

### रिटर्न वैल्यू

[String](../../../system/string/) डिकोड किए गए अक्षरों का।

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&, int, int) मेथड

एक बाइट बफ़र को स्ट्रिंग में डिकोड करता है।

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes, int index, int count)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) बाइट्स पढ़ने के लिए। |
| index | int | Input buffer offset. |
| count | int | Input buffer size. |

### रिटर्न वैल्यू

[String](../../../system/string/) डिकोड किए गए अक्षरों का।

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>, int, int) मेथड

एक बाइट बफ़र को स्ट्रिंग में डिकोड करता है।

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> bytes, int index, int count)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\> | [Buffer](../../../system/buffer/) बाइट्स पढ़ने के लिए। |
| index | int | Input buffer offset. |
| count | int | Input buffer size. |

### रिटर्न वैल्यू

[String](../../../system/string/) डिकोड किए गए अक्षरों का।

## संबंधित देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [String](../../../system/string/)
* क्लास [Encoding](../)
* क्लास [ReadOnlySpan](../../../system/readonlyspan/)
* नामस्थान [System::Text](../../)
* लाइब्रेरी [Aspose.Slides](../../../)