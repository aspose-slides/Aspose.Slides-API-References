---
title: operator>=()
second_title: Aspose.Slides for C++ API संदर्भ
description: हमेशा false लौटाता है।
type: docs
weight: 183
url: /hi/system/nullable/operator_greater_equal/
---
## Nullable::operator>=(std::nullptr_t) const विधि

हमेशा false लौटाता है।

```cpp
bool System::Nullable<T>::operator>=(std::nullptr_t) const
```

### रिटर्न मान

हमेशा - false

## Nullable::operator>=(const T1\&) const विधि

निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान निर्दिष्ट ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान से बड़ा या बराबर है या नहीं, इन मूल्यों पर [operator>=()](./) लागू करके।

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>=(const T1 &other) const
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान की तुलना करने वाले मान का अंतर्निहित प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | const T1\& | वर्तमान ऑब्जेक्ट की तुलना करने के लिए एक स्थिर संदर्भ |

### रिटर्न मान

यदि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान निर्दिष्ट ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान से बड़ा या बराबर हो, तो true, अन्यथा - false

## Nullable::operator>=(const Nullable\<T1\>\&) const विधि

निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान निर्दिष्ट [Nullable](../) ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान से बड़ा या बराबर है या नहीं, इन मूल्यों पर [operator>=()](./) लागू करके।

```cpp
template<typename T1> bool System::Nullable<T>::operator>=(const Nullable<T1> &other) const
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | तुलना करने वाले [Nullable](../) ऑब्जेक्ट का अंतर्निहित प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | तुलना करने के लिए [Nullable](../) ऑब्जेक्ट का एक स्थिर संदर्भ |

### रिटर्न मान

यदि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान निर्दिष्ट [Nullable](../) ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान से बड़ा या बराबर हो, तो true, अन्यथा - false

## देखें

* क्लास [Nullable](../)
* स्ट्रक्ट [IsNullable](../../isnullable/)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)