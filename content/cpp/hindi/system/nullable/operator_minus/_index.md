---
title: operator-()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: नल योग्य और नल-पॉइंटेड मानों को घटाता है।
type: docs
weight: 222
url: /hi/system/nullable/operator_minus/
---
## Nullable::operator-(T1) const मेथड

नल योग्य और नल-पॉइंटेड मानों को घटाता है।

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-(T1) const
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | दाहिना ऑपरेण्ड प्रकार, इसे nullptr_t होना चाहिए। |

### वापसी मान

खाली [Nullable](../) ऑब्जेक्ट।

## Nullable::operator-(const T1\&) const मेथड

नल योग्य और गैर-नल योग्य मानों को घटाता है।

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator-(const T1 &other) const -> Nullable<decltype(get_Value() - other)>
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | दाहिना ऑपरेण्ड प्रकार। |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | const T1\& | घटाने के लिए मान। |

### वापसी मान

वियोजन परिणाम।

## Nullable::operator-(const Nullable\<T1\>\&) const मेथड

नल योग्य मानों को घटाता है।

```cpp
template<typename T1> auto System::Nullable<T>::operator-(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value() - other.get_Value())>
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | दाहिना ऑपरेण्ड प्रकार। |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | घटाने के लिए मान। |

### वापसी मान

वियोजन परिणाम।

## संबंधित देखें

* क्लास [Nullable](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)