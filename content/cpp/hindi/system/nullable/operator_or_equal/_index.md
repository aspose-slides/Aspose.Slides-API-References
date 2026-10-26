---
title: operator|=()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट मान को दाएँ-पक्ष तर्क के रूप में उपयोग करके, वर्तमान वस्तु द्वारा दर्शाए गए मान पर operator|=() लागू करता है।
type: docs
weight: 261
url: /hi/system/nullable/operator_or_equal/
---
## Nullable::operator|=(bool) विधि


निर्दिष्ट मान को दाएँ-पक्ष तर्क के रूप में उपयोग करके, वर्तमान वस्तु द्वारा दर्शाए गए मान पर [operator|=()](./) लागू करता है।

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator|=(bool other)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | SFINAE को काम करने के लिए टेम्प्लेट पैरामीटर। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | **bool** | एक बूलियन मान जो वर्तमान वस्तु द्वारा दर्शाए गए मान पर लागू [operator|=()](./) के दाएँ-पक्ष मान के रूप में उपयोग किया जाता है। |

### रिटर्न मान

स्वयं का एक संदर्भ।

## संबंधित देखें

* क्लास [Nullable](../)
* नामस्थान [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)