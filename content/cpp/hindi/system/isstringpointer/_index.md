---
title: IsStringPointer
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: यदि कोई प्रकार अक्षर स्ट्रिंग का पॉइंटर है तो जाँचने के लिए टेम्पलेट जादू।
type: docs
weight: 1743
url: /hi/system/isstringpointer/
---
## IsStringPointer struct

यदि कोई प्रकार अक्षर स्ट्रिंग का पॉइंटर है तो जाँचने के लिए टेम्पलेट जादू।

```cpp
template<typename T,typename CharT>class IsStringPointer : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_pointer<T>::value>
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | जाँचा गया प्रकार। |
| CharT | जाँच के लिए उपयोग किया जाने वाला अक्षर प्रकार। |

## संबंधित देखें

* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)