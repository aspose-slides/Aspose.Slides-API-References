---
title: SafeInvoke()
second_title: Aspose.Slides for C++ API संदर्भ
description: '.?' ऑपरेटर अनुवाद का कार्यान्वयन।
type: docs
weight: 2653
url: /hi/system/safeinvoke/
---
## System::SafeInvoke(T0\&&, T1\&&) फ़ंक्शन

Implementation of '?.' operator translation.

```cpp
template<typename T0,typename T1> static auto System::SafeInvoke(T0 &&expr, T1 &&func)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T0 | एक्सप्रेशन प्रकार। |
| T1 | ‘WhenTrue’ एक्सप्रेशन को संलग्न करने वाले लैम्ब्डा का प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| expr | T0\&& | एक्सप्रेशन मान। |
| func | T1\&& | ‘WhenTrue’ एक्सप्रेशन जो फंक्टर से बंधा है। |

### वापसी मान

यदि expr मान null नहीं है, तो func को उसके मान को पहले तर्क के रूप में लेकर कॉल किया जाता है और उसका परिणाम लौटाया जाता है, अन्यथा null लौटाया जाता है।

## देखें

* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)