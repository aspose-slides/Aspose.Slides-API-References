---
title: IsDefined()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: निर्धारित करता है कि निर्दिष्ट मान enumeration प्रकार E का सदस्य है या नहीं।
type: docs
weight: 27
url: /hi/system/enum/isdefined/
---
## Enum::IsDefined(E) विधि


निर्धारित करता है कि निर्दिष्ट मान enumeration प्रकार **E** का सदस्य है या नहीं।

```cpp
static bool System::Enum<E, Guard>::IsDefined(E value)
```


### आर्ग्यूमेंट्स

| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | E | जांचने के लिए मान |

### रिटर्न वैल्यू

यदि **value** enumeration **E** का सदस्य है तो true, अन्यथा false

## Enum::IsDefined(T) विधि


निर्धारित करता है कि निर्दिष्ट मान enumeration प्रकार **T** का सदस्य है या नहीं।

```cpp
template<class T> static std::enable_if<std::is_convertible<T, UnderlyingType>::value, bool>::type System::Enum<E, Guard>::IsDefined(T value)
```


### आर्ग्यूमेंट्स

| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | T | जांचने के लिए मान |

### रिटर्न वैल्यू

यदि **value** enumeration **T** का सदस्य है तो true, अन्यथा false

## Enum::IsDefined(const String\&) विधि


निर्धारित करता है कि निर्दिष्ट नाम वाला मान enum **E** के सदस्यों में है या नहीं।

```cpp
static bool System::Enum<E, Guard>::IsDefined(const String &name)
```


### आर्ग्यूमेंट्स

| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| name | const [String](../../string/)\& | जांचने के लिए नाम |

### रिटर्न वैल्यू

यदि **E** enum के साथ निर्दिष्ट नाम का सदस्य मौजूद है तो true, अन्यथा false

## देखें

* टाइपडिफ़ [UnderlyingType](../underlyingtype/)
* क्लास [String](../../string/)
* स्ट्रक्ट [Enum](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)