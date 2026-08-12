---
title: Convert()
second_title: Aspose.Slides C++ के लिए एपीआई संदर्भ
description: बाइट्स को अक्षरों में बदलता है।
type: docs
weight: 79
url: /hi/system.text/decoder/convert/
---
## Decoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) विधि

बाइट्स को अक्षरों में बदलता है।

```cpp
virtual void System::Text::Decoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### तर्क

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | डिकोड करने के लिए बाइट्स। |
| byteIndex | int | इनपुट बफ़र ऑफ़सेट। |
| byteCount | int | इनपुट बफ़र आकार। |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | गंतव्य अक्षर बफ़र। |
| charIndex | int | गंतव्य एरे ऑफ़सेट। |
| charCount | int | गंतव्य एरे आकार। |
| flush | **bool** | यदि true हो, तो गणना के बाद आंतरिक डिकोडर स्थिति को साफ़ करता है। |
| bytesUsed | int\& | बाइट्स पढ़े जाने की संख्या संग्रहीत करने वाले चर का संदर्भ। |
| charsUsed | int\& | लिखे गए अक्षरों की संख्या संग्रहीत करने वाले चर का संदर्भ। |
| completed | **bool**\& | यदि इनपुट बफ़र समाप्त हो गया हो तो true सेट करने और अन्यथा false सेट करने के लिए चर का संदर्भ। |

## Decoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) विधि

बाइट्स को अक्षरों में बदलता है।

```cpp
virtual void System::Text::Decoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### तर्क

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytes | const **uint8_t** * | डिकोड करने के लिए बाइट्स। |
| byteCount | int | इनपुट बफ़र आकार। |
| chars | char_t * | गंतव्य अक्षर बफ़र। |
| charCount | int | गंतव्य एरे आकार। |
| flush | **bool** | यदि true हो, तो गणना के बाद आंतरिक डिकोडर स्थिति को साफ़ करता है। |
| bytesUsed | int\& | बाइट्स पढ़े जाने की संख्या संग्रहीत करने वाले चर का संदर्भ। |
| charsUsed | int\& | लिखे गए अक्षरों की संख्या संग्रहीत करने वाले चर का संदर्भ। |
| completed | **bool**\& | यदि इनपुट बफ़र समाप्त हो गया हो तो true सेट करने और अन्यथा false सेट करने के लिए चर का संदर्भ। |

## देखें

* टाइपडिफ़ [ArrayPtr](../../../system/arrayptr/)
* क्लास [Decoder](../)
* नामस्थान [System::Text](../../)
* लाइब्रेरी [Aspose.Slides](../../../)