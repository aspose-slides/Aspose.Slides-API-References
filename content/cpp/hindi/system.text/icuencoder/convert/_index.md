---
title: Convert()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: अक्षरों को बाइट्स में परिवर्तित करता है।
type: docs
weight: 66
url: /hi/system.text/icuencoder/convert/
---
## ICUEncoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) विधि


अक्षरों को बाइट्स में परिवर्तित करता है।

```cpp
virtual void System::Text::ICUEncoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | एन्कोड करने के लिए अक्षर। |
| charIndex | int | इनपुट बफ़र ऑफ़सेट। |
| charCount | int | इनपुट बफ़र आकार। |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | लक्ष्य बाइट बफ़र। |
| byteIndex | int | लक्ष्य ऐरे ऑफ़सेट। |
| byteCount | int | लक्ष्य ऐरे आकार। |
| flush | **bool** | यदि true हो, गणना के बाद आंतरिक एन्कोडर स्थिति को साफ करता है। |
| charsUsed | int\& | पढ़े गए अक्षरों की संख्या संग्रहीत करने के लिए चर का संदर्भ। |
| bytesUsed | int\& | लिखे गए बाइट्स की संख्या संग्रहीत करने के लिए चर का संदर्भ। |
| completed | **bool**\& | इनपुट बफ़र समाप्त होने पर true सेट करने और अन्यथा false सेट करने के लिए चर का संदर्भ। |

## ICUEncoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) विधि


अक्षरों को बाइट्स में परिवर्तित करता है।

```cpp
virtual void System::Text::ICUEncoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chars | const char_t * | एन्कोड करने के लिए अक्षर। |
| charCount | int | इनपुट बफ़र आकार। |
| bytes | **uint8_t** * | लक्ष्य बाइट बफ़र। |
| byteCount | int | लक्ष्य ऐरे आकार। |
| flush | **bool** | यदि true हो, गणना के बाद आंतरिक एन्कोडर स्थिति को साफ करता है। |
| charsUsed | int\& | पढ़े गए अक्षरों की संख्या संग्रहीत करने के लिए चर का संदर्भ। |
| bytesUsed | int\& | लिखे गए बाइट्स की संख्या संग्रहीत करने के लिए चर का संदर्भ। |
| completed | **bool**\& | इनपुट बफ़र समाप्त होने पर true सेट करने और अन्यथा false सेट करने के लिए चर का संदर्भ। |

## देखें भी

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [ICUEncoder](../)
* नामस्थान [System::Text](../../)
* लाइब्रेरी [Aspose.Slides](../../../)