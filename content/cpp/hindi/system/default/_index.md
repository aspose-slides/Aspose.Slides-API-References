---
title: Default()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक्सेप्शन प्रकार के एकल डिफ़ॉल्ट-निर्मित इंस्टेंस का संदर्भ लौटाता है।
type: docs
weight: 2224
url: /hi/system/default/
---
## System::Default() फ़ंक्शन

एक्सेप्शन प्रकार के एकल डिफ़ॉल्ट-निर्मित इंस्टेंस का संदर्भ लौटाता है।

```cpp
template<typename T> std::enable_if<IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | जिस प्रकार का इंस्टेंस लौटाया जाता है |

## System::Default() फ़ंक्शन

गैर-अपवाद प्रकार के एकल डिफ़ॉल्ट-निर्मित इंस्टेंस का संदर्भ लौटाता है।

```cpp
template<typename T> std::enable_if<!IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | जिस प्रकार का इंस्टेंस लौटाया जाता है |

## संबंधित देखें

* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)