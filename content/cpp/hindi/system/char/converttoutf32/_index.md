---
title: ConvertToUtf32()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट UTF-16 सरोगेट जोड़ी को UTF-32 कोड इकाई में परिवर्तित करता है।
type: docs
weight: 287
url: /hi/system/char/converttoutf32/
---
## Char::ConvertToUtf32(char_t, char_t) विधि

निर्दिष्ट UTF-16 सरोगेट जोड़ी को UTF-32 कोड यूनिट में परिवर्तित करता है।

```cpp
static int System::Char::ConvertToUtf32(char_t highSurrogate, char_t lowSurrogate)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| highSurrogate | char_t | कनवर्ट करने के लिए UTF-16 सरोगेट जोड़ी का highSurrogate |
| lowSurrogate | char_t | कनवर्ट करने के लिए UTF-16 सरोगेट जोड़ी का lowSurrogate |

### रिटर्न वैल्यू

कन्वर्ज़न के परिणामस्वरूप प्राप्त UTF-32 कोड यूनिट

## Char::ConvertToUtf32(const String\&, int) विधि

एक स्ट्रिंग में निर्दिष्ट स्थिति पर UTF-16 एन्कोडेड अक्षर या सरोगेट जोड़ी का मान को UTF-32 कोड यूनिट में परिवर्तित करता है।

```cpp
static int System::Char::ConvertToUtf32(const String &s, int index)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| s | const [String](../../string/)\& | एक स्ट्रिंग जिसमें अक्षर या सरोगेट जोड़ी शामिल है |
| index | int | निर्दिष्ट स्ट्रिंग में अक्षर या सरोगेट जोड़ी की इंडेक्स स्थिति |

### रिटर्न वैल्यू

कन्वर्ज़न के परिणामस्वरूप प्राप्त UTF-32 कोड यूनिट

## संबंधित देखें

* क्लास [Char](../)
* क्लास [String](../../string/)
* नामस्थान [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)