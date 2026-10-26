---
title: Convert()
second_title: Aspose.Slides for C++ API संदर्भ
description: अक्षरों को बाइट्स में बदलता है।
type: docs
weight: 79
url: /hi/system.text/encoder/convert/
---
## Encoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) मेथड

अक्षरों को बाइट्स में बदलता है।

```cpp
virtual void System::Text::Encoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | एन्कोड करने के लिए अक्षर। |
| charIndex | int | इनपुट बफ़र ऑफ़सेट। |
| charCount | int | इनपुट बफ़र आकार। |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | गंतव्य बाइट बफ़र। |
| byteIndex | int | गंतव्य ऐरे ऑफ़सेट। |
| byteCount | int | गंतव्य ऐरे आकार। |
| flush | **bool** | यदि true है, तो गणना के बाद आंतरिक एन्कोडर स्थिति को साफ़ करता है। |
| charsUsed | int\& | पढ़े गए अक्षरों की गणना संग्रहीत करने वाले वेरिएबल का रेफ़रेंस। |
| bytesUsed | int\& | लिखे गए बाइट्स की गणना संग्रहीत करने वाले वेरिएबल का रेफ़रेंस। |
| completed | **bool**\& | इनपुट बफ़र समाप्त हो गया तो true सेट करने के लिए वेरिएबल का रेफ़रेंस, अन्यथा false। |

## Encoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) मेथड

अक्षरों को बाइट्स में बदलता है।

```cpp
virtual void System::Text::Encoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chars | const char_t * | एन्कोड करने के लिए अक्षर। |
| charCount | int | इनपुट बफ़र आकार। |
| bytes | **uint8_t** * | गंतव्य बाइट बफ़र। |
| byteCount | int | गंतव्य ऐरे आकार। |
| flush | **bool** | यदि true है, तो गणना के बाद आंतरिक एन्कोडर स्थिति को साफ़ करता है। |
| charsUsed | int\& | पढ़े गए अक्षरों की गणना संग्रहीत करने वाले वेरिएबल का रेफ़रेंस। |
| bytesUsed | int\& | लिखे गए बाइट्स की गणना संग्रहीत करने वाले वेरिएबल का रेफ़रेंस। |
| completed | **bool**\& | इनपुट बफ़र समाप्त हो गया तो true सेट करने के लिए वेरिएबल का रेफ़रेंस, अन्यथा false। |

## देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [Encoder](../)
* नामस्थान [System::Text](../../)
* लाइब्रेरी [Aspose.Slides](../../../)