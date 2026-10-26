---
title: operator<=()
second_title: Aspose.Slides के लिए C++ API रेफरेंस
description: हमेशा false लौटाता है।
type: docs
weight: 196
url: /hi/system/nullable/operator_less_equal/
---
## Nullable::operator<=(std::nullptr_t) const मेथड


हमेशा **false** लौटाता है।

```cpp
bool System::Nullable<T>::operator<=(std::nullptr_t) const
```

## Nullable::operator<=(const T1\&) const मेथड


वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए मान को निर्दिष्ट मान के साथ तुलना करके यह निर्धारित करता है कि वह कम या बराबर है या नहीं, इसके लिए इन मानों पर [operator<=()](./) लागू किया जाता है।

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<=(const T1 &other) const
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | तुलना के लिए मान का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | const T1\& | तुलना के लिए मान का स्थायी रेफ़रेंस |

### रिटर्न वैल्यू

यदि वर्तमान ऑब्जेक्ट द्वारा दर्शाया गया मान निर्दिष्ट मान से कम या बराबर है तो **true**, अन्यथा **false**।

## Nullable::operator<=(const Nullable\<T1\>\&) const मेथड


वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए मान को निर्दिष्ट [Nullable](../) ऑब्जेक्ट द्वारा दर्शाए गए मान के साथ तुलना करके यह निर्धारित करता है कि वह कम या बराबर है या नहीं, इसके लिए इन मानों पर [operator<=()](./) लागू किया जाता है।

```cpp
template<typename T1> bool System::Nullable<T>::operator<=(const Nullable<T1> &other) const
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | तुलना के लिए [Nullable](../) ऑब्जेक्ट का आधारभूत प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | तुलना के लिए [Nullable](../) ऑब्जेक्ट का स्थायी रेफ़रेंस |

### रिटर्न वैल्यू

यदि वर्तमान ऑब्जेक्ट द्वारा दर्शाया गया मान निर्दिष्ट [Nullable](../) ऑब्जेक्ट द्वारा दर्शाए गए मान से कम या बराबर है तो **true**, अन्यथा **false**।

## संबंधित देखें

* क्लास [Nullable](../)
* स्ट्रक्ट [IsNullable](../../isnullable/)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)