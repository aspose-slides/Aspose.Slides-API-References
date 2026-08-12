---
title: IsStringLiteral
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: टेम्प्लेट जादू जो जांचता है कि कोई प्रकार स्ट्रिंग लिटरल है या नहीं।
type: docs
weight: 1730
url: /hi/system/isstringliteral/
---
## IsStringLiteral struct

टेम्प्लेट जादू जो जांचता है कि कोई प्रकार स्ट्रिंग लिटरल है या नहीं।

```cpp
template<typename T,typename CharT>class IsStringLiteral : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_array<T>::value>
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | जाँचा गया प्रकार। |
| CharT | जाँच के लिए वर्ण प्रकार। |

## देखें

* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)