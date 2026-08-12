---
title: GetChars()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक बाइट बफ़र को डिकोड करने से प्राप्त होने वाले अक्षर प्राप्त करें।
type: docs
weight: 66
url: /hi/system.text/icuencoding/getchars/
---
## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) विधि

एक बाइट बफ़र को डिकोड करने से प्राप्त होने वाले अक्षर प्राप्त करें।

```cpp
int System::Text::ICUEncoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) से बाइट पढ़ने के लिए। |
| byte_count | int | इनपुट बफ़र का आकार। |
| chars | char_t * | [Buffer](../../../system/buffer/) में अक्षर रखने के लिए। |
| char_count | int | आउटपुट बफ़र का आकार। |

### रिटर्न मान

लिखे गए अक्षरों की संख्या।

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) विधि

एक बाइट बफ़र को डिकोड करने से प्राप्त होने वाले अक्षर प्राप्त करें।

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) से बाइट पढ़ने के लिए। |
| byte_index | int | इनपुट बफ़र ऑफ़सेट। |
| byte_count | int | इनपुट बफ़र का आकार। |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) में अक्षर रखने के लिए। |
| char_index | int | आउटपुट बफ़र ऑफ़सेट। |

### रिटर्न मान

लिखे गए अक्षरों की संख्या।

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int) विधि

एक बाइट बफ़र को डिकोड करने से प्राप्त होने वाले अक्षर प्राप्त करें।

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) से बाइट पढ़ने के लिए। |
| index | int | इनपुट बफ़र ऑफ़सेट। |
| count | int | इनपुट बफ़र का आकार। |

### रिटर्न मान

डिकोड किए गए अक्षरों की [Buffer](../../../system/buffer/)।

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>) विधि

एक बाइट बफ़र को डिकोड करने से प्राप्त होने वाले अक्षर प्राप्त करें।

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) से बाइट पढ़ने के लिए। |

### रिटर्न मान

डिकोड किए गए अक्षरों की [Buffer](../../../system/buffer/)।

## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) विधि

एक बाइट बफ़र को डिकोड करने से प्राप्त होने वाले अक्षर प्राप्त करें।

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) से बाइट पढ़ने के लिए। |
| byte_count | int | इनपुट बफ़र का आकार। |
| chars | char_t * | [Buffer](../../../system/buffer/) में अक्षर रखने के लिए। |
| char_count | int | आउटपुट बफ़र का आकार। |

### रिटर्न मान

लिखे गए अक्षरों की संख्या।

## देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [ICUEncoding](../)
* नेमस्पेस [System::Text](../../)
* लाइब्रेरी [Aspose.Slides](../../../)