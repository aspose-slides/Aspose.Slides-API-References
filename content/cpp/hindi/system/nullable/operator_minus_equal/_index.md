---
title: operator-=()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक Nullable क्लास का उदाहरण लौटाता है जो एक null-value का प्रतिनिधित्व करता है।
type: docs
weight: 248
url: /hi/system/nullable/operator_minus_equal/
---
## Nullable::operator-=(T1) विधि

एक [Nullable](../) क्लास का उदाहरण लौटाता है जो एक null-value का प्रतिनिधित्व करता है।

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-=(T1)
```

## Nullable::operator-=(const T1\&) विधि

[operator-=()](./) को वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए मान पर लागू करता है, जहाँ निर्दिष्ट मान को दाएँ-साइड तर्क के रूप में उपयोग किया जाता है।

```cpp
template<typename T1,typename> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator-=(const T1 &other)
```

### टेम्प्लेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| T1 | [operator-=()](./) के दाएँ-साइड मान के रूप में उपयोग किए जाने वाले मान का प्रकार |

### तर्क

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | const T1\& | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए मान पर लागू [operator-=()](./) के दाएँ-साइड मान के रूप में उपयोग किए जाने वाले मान का स्थिर रेफ़रेंस |

### रिटर्न मान

स्वयं का रेफ़रेंस

## Nullable::operator-=(const Nullable\<T1\>\&) विधि

[operator-=()](./) को वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए मान पर लागू करता है, जहाँ निर्दिष्ट [Nullable](../) ऑब्जेक्ट द्वारा दर्शाए गए मान को दाएँ-साइड तर्क के रूप में उपयोग किया जाता है।

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator-=(const Nullable<T1> &other)
```

### टेम्प्लेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| T1 | [Nullable](../) ऑब्जेक्ट के अंतर्निहित प्रकार, जिसका मान [operator-=()](./) के दाएँ-साइड तर्क के रूप में उपयोग किया जाता है |

### तर्क

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए मान पर लागू [operator-=()](./) के दाएँ-साइड तर्क के रूप में उपयोग किए जाने वाले [Nullable](../) ऑब्जेक्ट का स्थिर रेफ़रेंस |

### रिटर्न मान

स्वयं का रेफ़रेंस

## संबंधित देखें

* क्लास [Nullable](../)
* स्ट्रक्ट [IsNullable](../../isnullable/)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)