---
title: Sign()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट साइन्ड समाकलित मान का साइन निर्धारित करता है।
type: docs
weight: 274
url: /hi/system/mathf/sign/
---
## MathF::Sign(T) मेथड


निर्दिष्ट साइन्ड समाकलित मान का साइन निर्धारित करता है।

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::MathF::Sign(T value)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | समाकलित साइन्ड प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | T | साइन निर्धारित करने का मान |

### रिटर्न मान

- 1 यदि **value** 0 से कम है; 0 यदि **value** 0 के बराबर है; 1 यदि **value** 0 से बड़ा है

## MathF::Sign(T) मेथड


निर्दिष्ट फ्लोटिंग-पॉइंट मान का साइन निर्धारित करता है।

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::MathF::Sign(T value)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | आर्ग्यूमेंट का फ्लोटिंग पॉइंट प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | T | साइन निर्धारित करने का मान |

### रिटर्न मान

- 1 यदि **value** 0 से कम है; 0 यदि **value** 0 के बराबर है; 1 यदि **value** 0 से बड़ा है

## देखें भी

* संरचना [MathF](../)
* नामस्थान [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)