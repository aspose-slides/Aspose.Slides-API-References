---
title: GetByteCount()
second_title: Aspose.Slides का C++ API संदर्भ
description: बफ़र को एन्कोड करने के लिए आवश्यक बाइट्स की संख्या प्राप्त करता है।
type: docs
weight: 40
url: /hi/system.text/encoder/getbytecount/
---
## Encoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) विधि

बफ़र को एन्कोड करने के लिए आवश्यक बाइट्स की संख्या प्राप्त करता है।

```cpp
virtual int System::Text::Encoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | एन्कोड करने के लिए अक्षर। |
| index | int | [Buffer](../../../system/buffer/) ऑफ़सेट। |
| count | int | एन्कोड करने के लिये अक्षरों की संख्या। |
| flush | **bool** | यदि true है, तो गणना के बाद आंतरिक एन्कोडर स्थिति को साफ़ करता है। |

### Return Value

बफ़र को एन्कोड करने के लिए आवश्यक बाइट्स की संख्या।

## Encoder::GetByteCount(const char_t *, int, bool) विधि

बफ़र को एन्कोड करने के लिए आवश्यक बाइट्स की संख्या प्राप्त करता है।

```cpp
virtual int System::Text::Encoder::GetByteCount(const char_t *chars, int count, bool flush)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | एन्कोड करने के लिये अक्षर। |
| count | int | एन्कोड करने के लिये अक्षरों की संख्या। |
| flush | **bool** | यदि true है, तो गणना के बाद आंतरिक एन्कोडर स्थिति को साफ़ करता है। |

### Return Value

बफ़र को एन्कोड करने के लिए आवश्यक बाइट्स की संख्या।

## See Also

* टाइपडिफ़ [ArrayPtr](../../../system/arrayptr/)
* क्लास [Encoder](../)
* नेमस्पेस [System::Text](../../)
* लाइब्रेरी [Aspose.Slides](../../../)