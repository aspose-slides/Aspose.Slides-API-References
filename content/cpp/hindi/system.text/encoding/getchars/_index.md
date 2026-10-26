---
title: GetChars()
second_title: Aspose.Slides for C++ API संदर्भ
description: डिकोडिंग बाइट बफ़र से प्राप्त होने वाले अक्षरों को प्राप्त करें।
type: docs
weight: 274
url: /hi/system.text/encoding/getchars/
---
## Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) विधि

डिकोडिंग बाइट बफ़र से प्राप्त अक्षरों को प्राप्त करें।

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) से बाइट्स पढ़ने के लिए। |
| byte_index | int | इनपुट बफ़र ऑफ़सेट। |
| byte_count | int | इनपुट बफ़र आकार। |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) अक्षरों को रखने के लिए। |
| char_index | int | आउटपुट बफ़र ऑफ़सेट। |

### रिटर्न मान

लिखे गए अक्षरों की संख्या।

## Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) विधि

डिकोडिंग बाइट बफ़र से प्राप्त अक्षरों को प्राप्त करें।

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) से बाइट्स पढ़ने के लिए। |
| index | int | इनपुट बफ़र ऑफ़सेट। |
| count | int | इनपुट बफ़र आकार। |

### रिटर्न मान

[Buffer](../../../system/buffer/) डिकोड किए गए अक्षरों की।

## Encoding::GetChars(ArrayPtr\<uint8_t\>) विधि

डिकोडिंग बाइट बफ़र से प्राप्त अक्षरों को प्राप्त करें।

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) से बाइट्स पढ़ने के लिए। |

### रिटर्न मान

[Buffer](../../../system/buffer/) डिकोड किए गए अक्षरों की।

## Encoding::GetChars(const uint8_t *, int, char_t *, int) विधि

डिकोडिंग बाइट बफ़र से प्राप्त अक्षरों को प्राप्त करें।

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) से बाइट्स पढ़ने के लिए। |
| byte_count | int | इनपुट बफ़र आकार। |
| chars | char_t * | [Buffer](../../../system/buffer/) अक्षरों को रखने के लिए। |
| char_count | int | आउटपुट बफ़र आकार। |

### रिटर्न मान

लिखे गए अक्षरों की संख्या।

## देखें

* टाइपडिफ़ [ArrayPtr](../../../system/arrayptr/)
* क्लास [Encoding](../)
* नेमस्पेस [System::Text](../../)
* लाइब्रेरी [Aspose.Slides](../../../)