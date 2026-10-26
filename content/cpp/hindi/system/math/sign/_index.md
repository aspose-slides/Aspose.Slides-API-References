---
title: Sign()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट हस्ताक्षरित पूर्णांक मान का चिन्ह निर्धारित करता है।
type: docs
weight: 274
url: /hi/system/math/sign/
---
## Math::Sign(T) विधि

निर्दिष्ट हस्ताक्षरित पूर्णांक मान का चिन्ह निर्धारित करता है।

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::Math::Sign(T value)
```

### टेम्प्लेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| T | हस्ताक्षरित पूर्णांक प्रकार |

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | T | जिस मान का चिन्ह निर्धारित करना है |

### रिटर्न मान

- 1 यदि **value** 0 से छोटा है; 0 यदि **value** 0 के बराबर है; 1 यदि **value** 0 से बड़ा है

## Math::Sign(T) विधि

निर्दिष्ट फ्लोटिंग-पॉइंट मान का चिन्ह निर्धारित करता है।

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::Math::Sign(T value)
```

### टेम्प्लेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| T | आर्ग्युमेंट का फ्लोटिंग पॉइंट प्रकार |

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | T | जिस मान का चिन्ह निर्धारित करना है |

### रिटर्न मान

- 1 यदि **value** 0 से छोटा है; 0 यदि **value** 0 के बराबर है; 1 यदि **value** 0 से बड़ा है

## Math::Sign(const Decimal\&) विधि

निर्दिष्ट दशमलव मान का चिन्ह निर्धारित करता है।

```cpp
static int System::Math::Sign(const Decimal &value)
```

### आर्ग्युमेंट

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | जिस मान का चिन्ह निर्धारित करना है |

### रिटर्न मान

- 1 यदि **value** 0 से छोटा है; 0 यदि **value** 0 के बराबर है; 1 यदि **value** 0 से बड़ा है

## संबंधित देखें

* क्लास [Decimal](../../decimal/)
* संरचना [Math](../)
* नामस्थान [System](../../)
* पुस्तकालय [Aspose.Slides](../../../)