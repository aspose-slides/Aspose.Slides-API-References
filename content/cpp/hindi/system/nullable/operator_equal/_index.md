---
title: operator=()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: वर्तमान वस्तु को null असाइन करता है।
type: docs
weight: 14
url: /hi/system/nullable/operator_equal/
---
## Nullable::operator=(std::nullptr_t) method


वर्तमान वस्तु को null असाइन करता है।

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator=(std::nullptr_t)
```


### रिटर्न वैल्यू

एक [Nullable](../) वस्तु जो null-मूल्य का प्रतिनिधित्व करती है।

## Nullable::operator=(const T1\&) method


वस्तु के वर्तमान प्रतिनिधित्व मान को निर्दिष्ट मान से बदलता है।

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value &&!std::is_null_pointer<T1>::value, Nullable<T> &>::type System::Nullable<T>::operator=(const T1 &x)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| वह | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए जाने वाले नए मान का प्रकार |

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | const T1\& | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए जाने वाला नया मान |

### रिटर्न वैल्यू

स्वयं का एक रेफ़रेंस

## Nullable::operator=(const Nullable\<T1\>\&) method


वस्तु के वर्तमान प्रतिनिधित्व मान को निर्दिष्ट मान से बदलता है।

```cpp
template<typename T1> Nullable<T> & System::Nullable<T>::operator=(const Nullable<T1> &x)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| वह | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए जाने वाले नए मान का प्रकार |

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | const [Nullable](../)\<T1\>\& | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए जाने वाला नया मान |

### रिटर्न वैल्यू

स्वयं का एक रेफ़रेंस

## संबंधित देखें

* क्लास [Nullable](../)
* स्ट्रक्ट [IsNullable](../../isnullable/)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)