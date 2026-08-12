---
title: operator>()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा दर्शाया गया दिनांक और समय मान निर्दिष्ट DateTimeOffset ऑब्जेक्ट द्वारा दर्शाए गए मान से बाद में है या नहीं।
type: docs
weight: 573
url: /hi/system/datetimeoffset/operator_greater/
---
## DateTimeOffset::operator>(const DateTimeOffset\&) const विधि

वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए दिनांक और समय मान को निर्धारित करता है कि वह निर्दिष्ट [DateTimeOffset](../) ऑब्जेक्ट द्वारा दर्शाए गए मान से बाद में है या नहीं।

```cpp
bool System::DateTimeOffset::operator>(const DateTimeOffset &other) const
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | वर्तमान ऑब्जेक्ट की तुलना करने के लिये [DateTimeOffset](../) ऑब्जेक्ट |

### रिटर्न मान

True if the date and time value represented by the current object is later than the value represented by **other**, otherwise - false

## DateTimeOffset::operator>(std::nullptr_t) const विधि

```cpp
constexpr bool System::DateTimeOffset::operator>(std::nullptr_t) const
```

## देखें

* क्लास [DateTimeOffset](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)