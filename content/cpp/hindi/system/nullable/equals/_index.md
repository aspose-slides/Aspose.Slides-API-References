---
title: Equals()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्धारित करता है कि क्या वर्तमान वस्तु द्वारा प्रतिनिधित्व किया गया मान निर्दिष्ट Nullable वस्तु द्वारा प्रतिनिधित्व किए गए मान के बराबर है।
type: docs
weight: 131
url: /hi/system/nullable/equals/
---
## Nullable::Equals(const T1\&) const विधि

निर्धारित करता है कि क्या वर्तमान वस्तु द्वारा प्रदर्शित मान निर्दिष्ट [Nullable](../) वस्तु द्वारा प्रदर्शित मान के बराबर है।

```cpp
template<typename T1> std::enable_if<IsNullable<T1>::value, bool>::type System::Nullable<T>::Equals(const T1 &other) const
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | तुलना करने के लिए [Nullable](../) वस्तु का आधारभूत प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | const T1\& | तुलना करने के लिए [Nullable](../) वस्तु का एक स्थिर संदर्भ |

### वापसी मान

True if the value represented by the current object is equal to the value represented by the specified [Nullable](../) object, otherwise - false

## देखें भी

* क्लास [Nullable](../)
* स्ट्रक्ट [IsNullable](../../isnullable/)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)