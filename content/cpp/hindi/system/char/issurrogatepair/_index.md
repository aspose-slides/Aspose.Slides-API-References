---
title: IsSurrogatePair()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्धारित करता है कि दो निर्दिष्ट वर्ण UTF-16 सरोगेट जोड़ी के लिए हैं या नहीं।
type: docs
weight: 27
url: /hi/system/char/issurrogatepair/
---
## Char::IsSurrogatePair(char_t, char_t) विधि

निर्धारित करता है कि दो निर्दिष्ट वर्ण UTF-16 सरोगेट जोड़ी के लिए हैं या नहीं।

```cpp
static bool System::Char::IsSurrogatePair(char_t highSurrogate, char_t lowSurrogate)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| highSurrogate | char_t | एक वर्ण जिसका परीक्षण उच्च सरोगेट होने के लिए किया जाता है |
| lowSurrogate | char_t | एक वर्ण जिसका परीक्षण निम्न सरोगेट होने के लिए किया जाता है |

### रिटर्न मान

True यदि निर्दिष्ट वर्ण एक सरोगेट जोड़ी बनाते हैं, अन्यथा - false

## Char::IsSurrogatePair(const String\&, int) विधि

निर्धारित करता है कि निर्दिष्ट वर्ण बफ़र में दो क्रमागत वर्ण एक सरोगेट जोड़ी हैं या नहीं।

```cpp
static bool System::Char::IsSurrogatePair(const String &str, int index)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | const [String](../../string/)\& | एक स्ट्रिंग |
| index | int | निर्दिष्ट बफ़र में वह शून्य-आधारित सूचकांक जहाँ परीक्षण करने वाली वर्ण अनुक्रम शुरू होती है |

### रिटर्न मान

True यदि निर्दिष्ट वर्ण एक सरोगेट जोड़ी हैं, अन्यथा - false

## देखें

* क्लास [Char](../)
* क्लास [String](../../string/)
* नामस्थान [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)