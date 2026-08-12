---
title: GetCharCount()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: बफ़र को डिकोड करने के लिए आवश्यक अक्षरों की संख्या प्राप्त करता है।
type: docs
weight: 40
url: /hi/system.text/decoder/getcharcount/
---
## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) मेथड

बफ़र को डिकोड करने के लिए आवश्यक अक्षरों की संख्या प्राप्त करता है।

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | डिकोड करने के लिए बाइट्स। |
| index | int | [Buffer](../../../system/buffer/) ऑफ़सेट। |
| count | int | डिकोड करने के लिए बाइट्स की संख्या। |

### रिटर्न वैल्यू

बफ़र को डिकोड करने के लिए आवश्यक अक्षरों की संख्या।

## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) मेथड

बफ़र को डिकोड करने के लिए आवश्यक अक्षरों की संख्या प्राप्त करता है।

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | डिकोड करने के लिए बाइट्स। |
| index | int | [Buffer](../../../system/buffer/) ऑफ़सेट। |
| count | int | डिकोड करने के लिए बाइट्स की संख्या। |
| flush | **bool** | यदि true हो, तो गणना के बाद आंतरिक डिकोडर स्थिति को साफ़ करता है। |

### रिटर्न वैल्यू

बफ़र को डिकोड करने के लिए आवश्यक अक्षरों की संख्या।

## Decoder::GetCharCount(const uint8_t *, int, bool) मेथड

बफ़र को डिकोड करने के लिए आवश्यक अक्षरों की संख्या प्राप्त करता है।

```cpp
virtual int System::Text::Decoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| bytes | const **uint8_t** * | डिकोड करने के लिए बाइट्स। |
| count | int | डिकोड करने के लिए बाइट्स की संख्या। |
| flush | **bool** | यदि true हो, तो गणना के बाद आंतरिक डिकोडर स्थिति को साफ़ करता है। |

### रिटर्न वैल्यू

बफ़र को डिकोड करने के लिए आवश्यक अक्षरों की संख्या।

## देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [Decoder](../)
* नामस्थान [System::Text](../../)
* लाइब्रेरी [Aspose.Slides](../../../)