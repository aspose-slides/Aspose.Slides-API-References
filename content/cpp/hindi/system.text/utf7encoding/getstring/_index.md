---
title: GetString()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक बाइट्स बफ़र को स्ट्रिंग में डिकोड करता है।
type: docs
weight: 170
url: /hi/system.text/utf7encoding/getstring/
---
## UTF7Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) विधि

बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है।

```cpp
String System::Text::UTF7Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) बाइट्स पढ़ने के लिए। |
| index | int | इनपुट बफ़र ऑफ़सेट। |
| count | int | इनपुट बफ़र आकार। |

### वापसी मान

[String](../../../system/string/) डिकोडेड अक्षरों का।

## UTF7Encoding::GetString(uint8_t *, int) विधि

बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है।

```cpp
virtual String System::Text::Encoding::GetString(uint8_t *bytes, int byte_count)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) बाइट्स पढ़ने के लिए। |
| byte_count | int | इनपुट बफ़र आकार। |

### वापसी मान

[String](../../../system/string/) डिकोडेड अक्षरों का।

## UTF7Encoding::GetString(const ReadOnlySpan\<uint8_t\>\&) विधि

बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है।

```cpp
String System::Text::Encoding::GetString(const ReadOnlySpan<uint8_t> &bytes)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytes | const [ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) बाइट्स पढ़ने के लिए। |

### वापसी मान

[String](../../../system/string/) डिकोडेड अक्षरों का।

## UTF7Encoding::GetString(ArrayPtr\<uint8_t\>) विधि

बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है।

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) बाइट्स पढ़ने के लिए। |

### वापसी मान

[String](../../../system/string/) डिकोडेड अक्षरों का।

## UTF7Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&) विधि

बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है।

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) बाइट्स पढ़ने के लिए। |

### वापसी मान

[String](../../../system/string/) डिकोडेड अक्षरों का।

## UTF7Encoding::GetString(System::Details::StackArray\<uint8_t, N\>\&) विधि

बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है।

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> &bytes)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | [Buffer](../../../system/buffer/) बाइट्स पढ़ने के लिए। |

### वापसी मान

[String](../../../system/string/) डिकोडेड अक्षरों का।

## UTF7Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) विधि

बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है।

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) बाइट्स पढ़ने के लिए। |
| index | int | इनपुट बफ़र ऑफ़सेट। |
| count | int | इनपुट बफ़र आकार। |

### वापसी मान

[String](../../../system/string/) डिकोडेड अक्षरों का।

## UTF7Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&, int, int) विधि

बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है।

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes, int index, int count)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) बाइट्स पढ़ने के लिए। |
| index | int | इनपुट बफ़र ऑफ़सेट। |
| count | int | इनपुट बफ़र आकार। |

### वापसी मान

[String](../../../system/string/) डिकोडेड अक्षरों का।

## UTF7Encoding::GetString(System::Details::StackArray\<uint8_t, N\>, int, int) विधि

बाइट्स के बफ़र को स्ट्रिंग में डिकोड करता है।

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> bytes, int index, int count)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\> | [Buffer](../../../system/buffer/) बाइट्स पढ़ने के लिए। |
| index | int | इनपुट बफ़र ऑफ़सेट। |
| count | int | इनपुट बफ़र आकार। |

### वापसी मान

[String](../../../system/string/) डिकोडेड अक्षरों का।

## संबंधित

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [UTF7Encoding](../)
* Class [ReadOnlySpan](../../../system/readonlyspan/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)