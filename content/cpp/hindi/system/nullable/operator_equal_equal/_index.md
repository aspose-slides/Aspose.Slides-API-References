---
title: operator==()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान null है या नहीं।
type: docs
weight: 118
url: /hi/system/nullable/operator_equal_equal/
---
## Nullable::operator==(std::nullptr_t) const विधि

निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान null है या नहीं।

```cpp
bool System::Nullable<T>::operator==(std::nullptr_t) const
```

### Return Value

यदि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान null है तो true, अन्यथा false

## Nullable::operator==(const T1\&) const विधि

निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान निर्दिष्ट मान के बराबर है या नहीं।

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator==(const T1 &other) const
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | जिन मान से तुलना की जा रही है उसका प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | const T1\& | तुलना के लिये मान का स्थिर संदर्भ |

### Return Value

यदि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान निर्दिष्ट मान के बराबर है तो true, अन्यथा false

## Nullable::operator==(const Nullable\<T1\>\&) const विधि

निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान निर्दिष्ट [Nullable](../) ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान के बराबर है या नहीं।

```cpp
template<typename T1> bool System::Nullable<T>::operator==(const Nullable<T1> &other) const
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | तुलना किए जाने वाले [Nullable](../) ऑब्जेक्ट का अंतर्निहित प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | तुलना करने वाले [Nullable](../) ऑब्जेक्ट का स्थिर संदर्भ |

### Return Value

यदि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान निर्दिष्ट [Nullable](../) ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान के बराबर है तो true, अन्यथा false

## See Also

* क्लास [Nullable](../)
* स्ट्रक्ट [IsNullable](../../isnullable/)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)