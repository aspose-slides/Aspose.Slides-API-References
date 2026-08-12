---
title: Convert()
second_title: Aspose.Slides for C++ API संदर्भ
description: अक्षरों को बाइट्स में परिवर्तित करता है।
type: docs
weight: 1
url: /hi/system.text/encodingencoder/convert/
---
## EncodingEncoder::Convert(const char_t *, int, uint8_t *, int, bool, int&, int&, bool&) विधि

अक्षरों को बाइट्स में परिवर्तित करता है।

```cpp
virtual void System::Text::EncodingEncoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chars | const char_t * | एन्कोड करने के लिये अक्षर। |
| charCount | int | इनपुट बफ़र का आकार। |
| bytes | **uint8_t** * | गंतव्य बाइट बफ़र। |
| byteCount | int | गंतव्य एरे का आकार। |
| flush | **bool** | यदि true हो, तो गणना के बाद आंतरिक एनकोडर की स्थिति को साफ़ करता है। |
| charsUsed | int\& | पढ़े गए अक्षरों की गिनती संग्रहीत करने वाले चर का संदर्भ। |
| bytesUsed | int\& | लिखे गए बाइट्स की गिनती संग्रहीत करने वाले चर का संदर्भ। |
| completed | **bool**\& | इनपुट बफ़र समाप्त हो जाने पर true सेट करने और अन्यथा false सेट करने के लिये चर का संदर्भ। |

## EncodingEncoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int&, int&, bool&) विधि

अक्षरों को बाइट्स में परिवर्तित करता है।

```cpp
virtual void System::Text::EncodingEncoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | एन्कोड करने के लिये अक्षर। |
| charIndex | int | इनपुट बफ़र का ऑफ़सेट। |
| charCount | int | इनपुट बफ़र का आकार। |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | गंतव्य बाइट बफ़र। |
| byteIndex | int | गंतव्य एरे का ऑफ़सेट। |
| byteCount | int | गंतव्य एरे का आकार। |
| flush | **bool** | यदि true हो, तो गणना के बाद आंतरिक एनकोडर की स्थिति को साफ़ करता है। |
| charsUsed | int\& | पढ़े गए अक्षरों की गिनती संग्रहीत करने वाले चर का संदर्भ। |
| bytesUsed | int\& | लिखे गए बाइट्स की गिनती संग्रहीत करने वाले चर का संदर्भ। |
| completed | **bool**\& | इनपुट बफ़र समाप्त हो जाने पर true सेट करने और अन्यथा false सेट करने के लिये चर का संदर्भ। |

## देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [EncodingEncoder](../)
* नेमस्पेस [System::Text](../../)
* लाइब्रेरी [Aspose.Slides](../../../)