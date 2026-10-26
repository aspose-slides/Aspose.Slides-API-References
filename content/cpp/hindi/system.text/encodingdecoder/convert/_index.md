---
title: Convert()
second_title: Aspose.Slides for C++ API संदर्भ
description: बाइट्स को अक्षरों में परिवर्तित करता है।
type: docs
weight: 1
url: /hi/system.text/encodingdecoder/convert/
---
## EncodingDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int&, int&, bool&) विधि

बाइट्स को अक्षरों में परिवर्तित करता है।

```cpp
void System::Text::EncodingDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytes | const **uint8_t** * | डिकोड करने के लिए बाइट्स। |
| byteCount | int | इनपुट बफ़र का आकार। |
| chars | char_t * | लक्ष्य अक्षर बफ़र। |
| charCount | int | लक्ष्य ऐरे का आकार। |
| flush | **bool** | यदि true है, तो गणना के बाद आंतरिक डिकोडर स्थिति को साफ करता है। |
| bytesUsed | int& | पढ़े गए बाइट्स की संख्या को संग्रहीत करने वाले चर का संदर्भ। |
| charsUsed | int& | लिखे गए अक्षरों की संख्या को संग्रहीत करने वाले चर का संदर्भ। |
| completed | **bool**& | इनपुट बफ़र समाप्त हो जाने पर true सेट करने और अन्यथा false सेट करने के लिए चर का संदर्भ। |

## EncodingDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int&, int&, bool&) विधि

बाइट्स को अक्षरों में परिवर्तित करता है।

```cpp
void System::Text::EncodingDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | डिकोड करने के लिए बाइट्स। |
| byteIndex | int | इनपुट बफ़र ऑफसेट। |
| byteCount | int | इनपुट बफ़र का आकार। |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | लक्ष्य अक्षर बफ़र। |
| charIndex | int | लक्ष्य ऐरे ऑफसेट। |
| charCount | int | लक्ष्य ऐरे का आकार। |
| flush | **bool** | यदि true है, तो गणना के बाद आंतरिक डिकोडर स्थिति को साफ करता है। |
| bytesUsed | int& | पढ़े गए बाइट्स की संख्या को संग्रहीत करने वाले चर का संदर्भ। |
| charsUsed | int& | लिखे गए अक्षरों की संख्या को संग्रहीत करने वाले चर का संदर्भ। |
| completed | **bool**& | इनपुट बफ़र समाप्त हो जाने पर true सेट करने और अन्यथा false सेट करने के लिए चर का संदर्भ। |

## देखें भी

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [EncodingDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)