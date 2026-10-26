---
title: GetByteCount()
second_title: Aspose.Slides for C++ API संदर्भ
description: बफ़र को एन्कोड करने के लिए आवश्यक बाइट्स की संख्या प्राप्त करता है।
type: docs
weight: 40
url: /hi/system.text/icuencoder/getbytecount/
---
## ICUEncoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) विधि

बफ़र को एन्कोड करने के लिए आवश्यक बाइट्स की संख्या प्राप्त करता है।

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | एन्कोड करने के लिए अक्षर। |
| index | int | [Buffer](../../../system/buffer/) ऑफ़सेट। |
| count | int | एन्कोड करने के लिए अक्षरों की संख्या। |
| flush | **bool** | यदि true हो, तो गणना के बाद आंतरिक एन्कोडर स्थिति को साफ़ करता है। |

### रिटर्न मान

बफ़र को एन्कोड करने के लिए आवश्यक बाइट्स की संख्या।

## ICUEncoder::GetByteCount(const char_t *, int, bool) विधि

बफ़र को एन्कोड करने के लिए आवश्यक बाइट्स की संख्या प्राप्त करता है।

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(const char_t *chars, int count, bool flush)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chars | const char_t * | एन्कोड करने के लिए अक्षर। |
| count | int | एन्कोड करने के लिए अक्षरों की संख्या। |
| flush | **bool** | यदि true हो, तो गणना के बाद आंतरिक एन्कोडर स्थिति को साफ़ करता है। |

### रिटर्न मान

बफ़र को एन्कोड करने के लिए आवश्यक बाइट्स की संख्या।

## संबंधित

* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [ICUEncoder](../)
* नामस्थान [System::Text](../../)
* लाइब्रेरी [Aspose.Slides](../../../)