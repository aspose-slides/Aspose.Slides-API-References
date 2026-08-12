---
title: operator!=()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रदर्शित मान null नहीं है।
type: docs
weight: 144
url: /hi/system/nullable/operator_not_equal/
---
## Nullable::operator!=(std::nullptr_t) const विधि

निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रदर्शित मान null नहीं है।

```cpp
bool System::Nullable<T>::operator!=(std::nullptr_t) const
```

### रिटर्न वैल्यू

True यदि वर्तमान ऑब्जेक्ट द्वारा प्रदर्शित मान null नहीं है, अन्यथा - false

## Nullable::operator!=(const T1\&) const विधि

निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रदर्शित मान निर्दिष्ट मान के बराबर नहीं है।

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator!=(const T1 &other) const
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | तुलना करने वाले मान का प्रकार |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | const T1\& | तुलना करने वाले मान का एक स्थिर संदर्भ |

### रिटर्न वैल्यू

True यदि वर्तमान ऑब्जेक्ट द्वारा प्रदर्शित मान निर्दिष्ट मान के बराबर नहीं है, अन्यथा - false

## Nullable::operator!=(const Nullable\<T1\>\&) const विधि

निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रदर्शित मान निर्दिष्ट [Nullable](../) ऑब्जेक्ट द्वारा प्रदर्शित मान के बराबर नहीं है।

```cpp
template<typename T1> bool System::Nullable<T>::operator!=(const Nullable<T1> &other) const
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | तुलना करने वाले [Nullable](../) ऑब्जेक्ट का अंतर्निहित प्रकार |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | तुलना करने वाले [Nullable](../) ऑब्जेक्ट का एक स्थिर संदर्भ |

### रिटर्न वैल्यू

True यदि वर्तमान ऑब्जेक्ट द्वारा प्रदर्शित मान निर्दिष्ट [Nullable](../) ऑब्जेक्ट द्वारा प्रदर्शित मान के बराबर नहीं है, अन्यथा - false

## देखें

* क्लास [Nullable](../)
* स्ट्रक्ट [IsNullable](../../isnullable/)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)