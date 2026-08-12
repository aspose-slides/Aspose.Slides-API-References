---
title: IsStringByteSequence
second_title: Aspose.Slides for C++ API संदर्भ
description: टेम्प्लेट जादू जो यह जांचता है कि कोई प्रकार स्ट्रिंग अक्षरों का अनुक्रम है।
type: docs
weight: 1717
url: /hi/system/isstringbytesequence/
---
## IsStringByteSequence struct

टेम्प्लेट जादू जो यह जांचता है कि कोई प्रकार स्ट्रिंग अक्षरों का अनुक्रम है।

```cpp
template<typename T,typename CharT>class IsStringByteSequence : public std::integral_constant<bool, std::is_same<std::remove_const<std::remove_pointer<std::decay<T>::type>::type>::type, CharT>::value>
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | जाँचा गया प्रकार। |
| CharT | जाँच के लिए चरित्र प्रकार। |

## संबंधित देखें

* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)