---
title: Nullable()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक इंस्टेंस बनाता है जो शून्य-मूल्य का प्रतिनिधित्व करता है।
type: docs
weight: 1
url: /hi/system/nullable/nullable/
---
## Nullable::Nullable() कन्स्ट्रक्टर

एक इंस्टेंस बनाता है जो शून्य-मूल्य का प्रतिनिधित्व करता है।

```cpp
System::Nullable<T>::Nullable()
```

## Nullable::Nullable(std::nullptr_t) कन्स्ट्रक्टर

एक इंस्टेंस बनाता है जो शून्य का प्रतिनिधित्व करता है।

```cpp
System::Nullable<T>::Nullable(std::nullptr_t)
```

## Nullable::Nullable(const T1\&) कन्स्ट्रक्टर

[Nullable](../) क्लास का एक इंस्टेंस बनाता है जो निर्दिष्ट मान को (यदि आवश्यक हो) अंतर्निहित प्रकार T के मान में परिवर्तित करता है।

```cpp
template<typename T1> System::Nullable<T>::Nullable(const T1 &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | निर्दिष्ट मान का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const T1\& | एक स्थिर संदर्भ जिसका मान नवीन निर्मित [Nullable](../) ऑब्जेक्ट द्वारा दर्शाया जाएगा |

## Nullable::Nullable(const Nullable\<T1\>\&) कन्स्ट्रक्टर

एक इंस्टेंस बनाता है जो निर्दिष्ट [Nullable](../) ऑब्जेक्ट द्वारा दर्शाए गए मान का प्रतिनिधित्व करता है। निर्दिष्ट nullable ऑब्जेक्ट का प्रकार निर्मित इंस्टेंस के अंतर्निहित प्रकार से अलग हो सकता है, ऐसे में दर्शाया गया मान प्रकार T में परिवर्तित हो जाता है।

```cpp
template<typename T1> System::Nullable<T>::Nullable(const Nullable<T1> &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | निर्दिष्ट [Nullable](../) ऑब्जेक्ट द्वारा दर्शाए गए मान का प्रकार |

## संबंधित देखें

* क्लास [Nullable](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)