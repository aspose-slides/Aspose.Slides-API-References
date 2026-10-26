---
title: TryParse()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट स्ट्रिंग को समतुल्य enum कॉन्स्टैंट में परिवर्तित करने का प्रयास करता है।
type: docs
weight: 79
url: /hi/system/enum/tryparse/
---
## Enum::TryParse(const String\&, E\&) मेथड

निर्दिष्ट स्ट्रिंग को समतुल्य enum कॉन्स्टैंट में परिवर्तित करने का प्रयास करता है।

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, E &result)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) जो enum कॉन्स्टैंट के नाम को समाहित करने के रूप में व्याख्यायित किया जाता है |
| result | E\& | आउटपुट पैरामीटर जो यदि रूपांतरण सफल होता है तो फ़ंक्शन पर रूपांतरण का परिणाम समाहित करता है |

### रिटर्न वैल्यू

यदि रूपांतरण सफल हुआ तो true, अन्यथा - false

## Enum::TryParse(const String\&, bool, E\&) मेथड

निर्दिष्ट स्ट्रिंग को समतुल्य enum कॉन्स्टैंट में परिवर्तित करने का प्रयास करता है।

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, bool ignoreCase, E &result)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) जो enum कॉन्स्टैंट के नाम को समाहित करने के रूप में व्याख्यायित किया जाता है |
| ignoreCase | **bool** | यदि स्ट्रिंग की व्याख्या करते समय केस को अनदेखा किया जाना चाहिए तो इसे निर्दिष्ट करता है |
| result | E\& | आउटपुट पैरामीटर जो यदि रूपांतरण सफल होता है तो फ़ंक्शन रिटर्न पर रूपांतरण का परिणाम समाहित करता है |

### रिटर्न वैल्यू

यदि रूपांतरण सफल हुआ तो true, अन्यथा - false

## संबंधित देखें

* क्लास [String](../../string/)
* स्ट्रक्ट [Enum](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)