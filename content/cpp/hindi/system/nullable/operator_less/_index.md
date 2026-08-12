---
title: operator<()
second_title: Aspose.Slides for C++ API संदर्भ
description: हमेशा false लौटाता है।
type: docs
weight: 170
url: /hi/system/nullable/operator_less/
---
## Nullable::operator<(std::nullptr_t) const मेथड


हमेशा false लौटाता है।

```cpp
bool System::Nullable<T>::operator<(std::nullptr_t) const
```

## Nullable::operator<(const T1\&) const मेथड


वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान की तुलना निर्दिष्ट मान से कम होने का निर्धारण करता है, इन मानों पर [operator<()](./) लागू करके।

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<(const T1 &other) const
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | तुलना करने के लिये मान का प्रकार |

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | const T1\& | तुलना करने के लिये मान का स्थायी संदर्भ |

### रिटर्न मान

यदि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान निर्दिष्ट मान से कम है तो true, अन्यथा - false।

## Nullable::operator<(const Nullable\<T1\>\&) const मेथड


वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान की तुलना निर्दिष्ट [Nullable](../) ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान से कम होने का निर्धारण करता है, इन मानों पर [operator<()](./) लागू करके।

```cpp
template<typename T1> bool System::Nullable<T>::operator<(const Nullable<T1> &other) const
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | तुलना करने के लिये [Nullable](../) ऑब्जेक्ट का आधारभूत प्रकार |

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | तुलना करने के लिये [Nullable](../) ऑब्जेक्ट का स्थायी संदर्भ |

### रिटर्न मान

यदि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया मान निर्दिष्ट [Nullable](../) ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए मान से कम है तो true, अन्यथा - false।

## संदर्भ

* क्लास [Nullable](../)
* स्ट्रक्ट [IsNullable](../../isnullable/)
* नामस्थान [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)