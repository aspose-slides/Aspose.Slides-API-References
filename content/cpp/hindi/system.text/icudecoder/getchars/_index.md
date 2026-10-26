---
title: GetChars()
second_title: Aspose.Slides for C++ API संदर्भ
description: डिकोड किए गए बफ़र से उत्पन्न अक्षरों को प्राप्त करें।
type: docs
weight: 53
url: /hi/system.text/icudecoder/getchars/
---
## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) विधि


डिकोड किए गए बफ़र से प्राप्त अक्षरों को प्राप्त करता है।

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | डिकोड करने के लिए बाइट्स। |
| byteIndex | int | इनपुट बफ़र ऑफ़सेट। |
| byteCount | int | इनपुट बफ़र आकार। |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | गंतव्य अक्षर बफ़र। |
| charIndex | int | गंतव्य एरे ऑफ़सेट। |

### वापसी मान

लिखे गए अक्षरों की संख्या।

## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) विधि


डिकोड किए गए बफ़र से प्राप्त अक्षरों को प्राप्त करता है।

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | डिकोड करने के लिए बाइट्स। |
| byteIndex | int | इनपुट बफ़र ऑफ़सेट। |
| byteCount | int | इनपुट बफ़र आकार। |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | गंतव्य अक्षर बफ़र। |
| charIndex | int | गंतव्य एरे ऑफ़सेट। |
| flush | **bool** | यदि सत्य हो, गणना के बाद आंतरिक डिकोडर स्थिति को साफ़ करता है। |

### वापसी मान

लिखे गए अक्षरों की संख्या।

## ICUDecoder::GetChars(const uint8_t *, int, char_t *, int, bool) विधि


डिकोड किए गए बफ़र से प्राप्त अक्षरों को प्राप्त करता है।

```cpp
virtual int System::Text::ICUDecoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytes | const **uint8_t** * | डिकोड करने के लिए बाइट्स। |
| byteCount | int | इनपुट बफ़र आकार। |
| chars | char_t * | गंतव्य अक्षर बफ़र। |
| charCount | int | गंतव्य एरे आकार। |
| flush | **bool** | यदि सत्य हो, गणना के बाद आंतरिक डिकोडर स्थिति को साफ़ करता है। |

### वापसी मान

लिखे गए अक्षरों की संख्या।

## संबंधित देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [ICUDecoder](../)
* नेमस्पेस [System::Text](../../)
* लाइब्रेरी [Aspose.Slides](../../../)