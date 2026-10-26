---
title: operator>()
second_title: Aspose.Slides for C++ API संदर्भ
description: हमेशा false लौटाता है।
type: docs
weight: 157
url: /hi/system/nullable/operator_greater/
---
## Nullable::operator>(std::nullptr_t) const मेथड

हमेशा false लौटाता है।

```cpp
bool System::Nullable<T>::operator>(std::nullptr_t) const
```

## Nullable::operator>(const T1\&) const मेथड

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान निर्दिष्ट मान से बड़ा है या नहीं, यह [operator>()](./) को इन मानों पर लागू करके निर्धारित करता है।

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>(const T1 &other) const
```

### टेम्पलेट पैरामीटर

| Parameter | Description |
| --- | --- |
| T1 | तुलना करने के लिए मान का प्रकार |

### आर्ग्युमेंट

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | तुलना करने के लिए मान का स्थिर संदर्भ |

### रिटर्न वैल्यू

यदि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान निर्दिष्ट मान से बड़ा है तो True, अन्यथा - false

## Nullable::operator>(const Nullable\<T1\>\&) const मेथड

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान निर्दिष्ट [Nullable](../) ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान से बड़ा है या नहीं, यह [operator>()](./) को इन मानों पर लागू करके निर्धारित करता है।

```cpp
template<typename T1> bool System::Nullable<T>::operator>(const Nullable<T1> &other) const
```

### टेम्पलेट पैरामीटर

| Parameter | Description |
| --- | --- |
| T1 | तुलना करने के लिए [Nullable](../) ऑब्जेक्ट का अंतर्निहित प्रकार |

### आर्ग्युमेंट

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | तुलना करने के लिए [Nullable](../) ऑब्जेक्ट का स्थिर संदर्भ |

### रिटर्न वैल्यू

यदि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान निर्दिष्ट [Nullable](../) ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान से बड़ा है तो True, अन्यथा - false

## संबंधित देखें

* क्लास [Nullable](../)
* स्ट्रक्ट [IsNullable](../../isnullable/)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)