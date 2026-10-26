---
title: Convert()
second_title: Aspose.Slides for C++ API संदर्भ
description: बाइट्स को अक्षरों में परिवर्तित करता है।
type: docs
weight: 66
url: /hi/system.text/icudecoder/convert/
---
## ICUDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) method

बाइट्स को अक्षरों में परिवर्तित करता है।

```cpp
virtual void System::Text::ICUDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | डिकोड करने के लिए बाइट्स। |
| byteIndex | int | इनपुट बफ़र ऑफ़सेट। |
| byteCount | int | इनपुट बफ़र आकार। |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | गंतव्य अक्षर बफ़र। |
| charIndex | int | गंतव्य एरे ऑफ़सेट। |
| charCount | int | गंतव्य एरे आकार। |
| flush | **bool** | यदि true है, गणना के बाद आंतरिक डीकोडर स्थिति को साफ़ करता है। |
| bytesUsed | int\& | पढ़े गए बाइट्स की गिनती संग्रहीत करने के लिए वेरिएबल का रेफ़रेंस। |
| charsUsed | int\& | लिखे गए अक्षरों की गिनती संग्रहीत करने के लिए वेरिएबल का रेफ़रेंस। |
| completed | **bool**\& | यदि इनपुट बफ़र समाप्त हो गया है तो true सेट करने और अन्यथा false सेट करने के लिए वेरिएबल का रेफ़रेंस। |

## ICUDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) method

बाइट्स को अक्षरों में परिवर्तित करता है।

```cpp
virtual void System::Text::ICUDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| bytes | const **uint8_t** * | डिकोड करने के लिए बाइट्स। |
| byteCount | int | इनपुट बफ़र आकार। |
| chars | char_t * | गंतव्य अक्षर बफ़र। |
| charCount | int | गंतव्य एरे आकार। |
| flush | **bool** | यदि true है, गणना के बाद आंतरिक डीकोडर स्थिति को साफ़ करता है। |
| bytesUsed | int\& | पढ़े गए बाइट्स की गिनती संग्रहीत करने के लिए वेरिएबल का रेफ़रेंस। |
| charsUsed | int\& | लिखे गए अक्षरों की गिनती संग्रहीत करने के लिए वेरिएबल का रेफ़रेंस। |
| completed | **bool**\& | यदि इनपुट बफ़र समाप्त हो गया है तो true सेट करने और अन्यथा false सेट करने के लिए वेरिएबल का रेफ़रेंस। |

## देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [ICUDecoder](../)
* नेमस्पेस [System::Text](../../)
* लाइब्रेरी [Aspose.Slides](../../../)