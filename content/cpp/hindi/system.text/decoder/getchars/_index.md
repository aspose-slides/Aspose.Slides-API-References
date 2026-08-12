---
title: GetChars()
second_title: Aspose.Slides for C++ API संदर्भ
description: डिकोडिंग बफ़र से प्राप्त होने वाले अक्षरों को प्राप्त करें।
type: docs
weight: 53
url: /hi/system.text/decoder/getchars/
---
## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) विधि

डिकोडिंग बफ़र से प्राप्त होने वाले अक्षरों को प्राप्त करें।

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | डिकोड करने के लिए बाइट्स। |
| byteIndex | int | इनपुट बफ़र ऑफ़सेट। |
| byteCount | int | इनपुट बफ़र आकार। |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | गंतव्य अक्षर बफ़र। |
| charIndex | int | गंतव्य एरे ऑफ़सेट। |

### रिटर्न वैल्यू

लिखे गए अक्षरों की संख्या।

## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) विधि

डिकोडिंग बफ़र से प्राप्त होने वाले अक्षरों को प्राप्त करें।

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | डिकोड करने के लिए बाइट्स। |
| byteIndex | int | इनपुट बफ़र ऑफ़सेट। |
| byteCount | int | इनपुट बफ़र आकार। |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | गंतव्य अक्षर बफ़र। |
| charIndex | int | गंतव्य एरे ऑफ़सेट। |
| flush | **bool** | यदि true है, तो गणना के बाद आंतरिक डिकोडर स्थिति को साफ़ करता है। |

### रिटर्न वैल्यू

लिखे गए अक्षरों की संख्या।

## Decoder::GetChars(const uint8_t *, int, char_t *, int, bool) विधि

डिकोडिंग बफ़र से प्राप्त होने वाले अक्षरों को प्राप्त करें।

```cpp
virtual int System::Text::Decoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| bytes | const **uint8_t** * | डिकोड करने के लिए बाइट्स। |
| byteCount | int | इनपुट बफ़र आकार। |
| chars | char_t * | गंतव्य अक्षर बफ़र। |
| charCount | int | गंतव्य एरे आकार। |
| flush | **bool** | यदि true है, तो गणना के बाद आंतरिक डिकोडर स्थिति को साफ़ करता है। |

### रिटर्न वैल्यू

लिखे गए अक्षरों की संख्या।

## देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [Decoder](../)
* नेमस्पेस [System::Text](../../)
* लाइब्रेरी [Aspose.Slides](../../../)