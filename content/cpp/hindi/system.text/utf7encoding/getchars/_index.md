---
title: GetChars()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: डिकोड किए गए बाइट बफ़र से प्राप्त अक्षर।
type: docs
weight: 92
url: /hi/system.text/utf7encoding/getchars/
---
## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) विधि

एक बाइट बफ़र को डिकोड करने के परिणामस्वरूप अक्षर प्राप्त करें।

```cpp
int System::Text::UTF7Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) से बाइट्स पढ़ने के लिए। |
| byte_index | int | इनपुट बफ़र ऑफ़सेट। |
| byte_count | int | इनपुट बफ़र आकार। |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) पर अक्षर रखने के लिए। |
| char_index | int | आउटपुट बफ़र ऑफ़सेट। |

### रिटर्न वैल्यू

लिखे गए अक्षरों की संख्या।

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) विधि

एक बाइट बफ़र को डिकोड करने के परिणामस्वरूप अक्षर प्राप्त करें।

```cpp
int System::Text::UTF7Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) से बाइट्स पढ़ने के लिए। |
| byte_count | int | इनपुट बफ़र आकार। |
| chars | char_t * | [Buffer](../../../system/buffer/) पर अक्षर रखने के लिए। |
| char_count | int | आउटपुट बफ़र आकार। |

### रिटर्न वैल्यू

लिखे गए अक्षरों की संख्या।

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) विधि

एक बाइट बफ़र को डिकोड करने के परिणामस्वरूप अक्षर प्राप्त करें।

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) से बाइट्स पढ़ने के लिए। |
| byte_index | int | इनपुट बफ़र ऑफ़सेट। |
| byte_count | int | इनपुट बफ़र आकार। |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) पर अक्षर रखने के लिए। |
| char_index | int | आउटपुट बफ़र ऑफ़सेट। |

### रिटर्न वैल्यू

लिखे गए अक्षरों की संख्या।

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) विधि

एक बाइट बफ़र को डिकोड करने के परिणामस्वरूप अक्षर प्राप्त करें।

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) से बाइट्स पढ़ने के लिए। |
| index | int | इनपुट बफ़र ऑफ़सेट। |
| count | int | इनपुट बफ़र आकार। |

### रिटर्न वैल्यू

[Buffer](../../../system/buffer/) डिकोडेड अक्षरों की संख्या।

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>) विधि

एक बाइट बफ़र को डिकोड करने के परिणामस्वरूप अक्षर प्राप्त करें।

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) से बाइट्स पढ़ने के लिए। |

### रिटर्न वैल्यू

[Buffer](../../../system/buffer/) डिकोडेड अक्षरों की संख्या।

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) विधि

एक बाइट बफ़र को डिकोड करने के परिणामस्वरूप अक्षर प्राप्त करें।

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) से बाइट्स पढ़ने के लिए। |
| byte_count | int | इनपुट बफ़र आकार। |
| chars | char_t * | [Buffer](../../../system/buffer/) पर अक्षर रखने के लिए। |
| char_count | int | आउटपुट बफ़र आकार। |

### रिटर्न वैल्यू

लिखे गए अक्षरों की संख्या।

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)