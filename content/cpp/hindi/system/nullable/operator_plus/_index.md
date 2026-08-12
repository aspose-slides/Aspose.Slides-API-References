---
title: operator+()
second_title: Aspose.Slides C++ API रेफ़रेंस के लिए
description: Nullable<T> क्लास का डिफ़ॉल्ट निर्मित इंस्टेंस लौटाता है।
type: docs
weight: 209
url: /hi/system/nullable/operator_plus/
---
## Nullable::operator+(std::nullptr_t) const विधि

Nullable<T> क्लास का डिफ़ॉल्ट निर्मित इंस्टेंस लौटाता है।

```cpp
Nullable<T> System::Nullable<T>::operator+(std::nullptr_t) const
```

## Nullable::operator+(const T1\&) const विधि

nullable और non-nullable मानों को जोड़ता है।

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator+(const T1 &other) const -> Nullable<decltype(get_Value()+other)>
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | दायें ऑपरेण्ड प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | const T1\& | जोड़ने के लिये मान। |

### वापसी मान

योग परिणाम।

## Nullable::operator+(const Nullable\<T1\>\&) const विधि

nullable मानों को जोड़ता है।

```cpp
template<typename T1> auto System::Nullable<T>::operator+(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value()+other.get_Value())>
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | दायें ऑपरेण्ड प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | जोड़ने के लिये मान। |

### वापसी मान

योग परिणाम।

## देखें

* क्लास [Nullable](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)