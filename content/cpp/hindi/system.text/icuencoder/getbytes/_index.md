---
title: GetBytes()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक बफ़र को एन्कोड करने के परिणामस्वरूप बाइट्स प्राप्त करें।
type: docs
weight: 53
url: /hi/system.text/icuencoder/getbytes/
---
## ICUEncoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) विधि

एक बफ़र को एन्कोड करने के परिणामस्वरूप प्राप्त बाइट्स।

```cpp
virtual int System::Text::ICUEncoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | एन्कोड करने के लिए अक्षर। |
| charIndex | int | स्रोत एरे का ऑफसेट। |
| charCount | int | स्रोत सबएरे की लंबाई। |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | गंतव्य बाइट बफ़र। |
| byteIndex | int | गंतव्य बफ़र का ऑफसेट। |
| flush | **bool** | यदि true हो, तो गणना के बाद आंतरिक एनकोडर की स्थिति साफ़ करता है। |

### वापसी मान

लिखे गए बाइट्स की संख्या।

## ICUEncoder::GetBytes(const char_t *, int, uint8_t *, int, bool) विधि

एक बफ़र को एन्कोड करने के परिणामस्वरूप प्राप्त बाइट्स।

```cpp
virtual int System::Text::ICUEncoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| chars | const char_t * | एन्कोड करने के लिए अक्षर। |
| charCount | int | स्रोत एरे की लंबाई। |
| bytes | **uint8_t** * | गंतव्य बाइट बफ़र। |
| byteCount | int | गंतव्य बफ़र का आकार। |
| flush | **bool** | यदि true हो, तो गणना के बाद आंतरिक एनकोडर की स्थिति साफ़ करता है। |

### वापसी मान

लिखे गए बाइट्स की संख्या।

## देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)