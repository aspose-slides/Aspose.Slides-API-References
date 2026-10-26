---
title: Box()
second_title: Aspose.Slides for C++ API संदर्भ
description: Object में बदलने के लिए मान प्रकारों को बॉक्स करता है। enum प्रकारों के लिए कार्यान्वयन।
type: docs
weight: 40
url: /hi/system/objectext/box/
---
## ObjectExt::Box(const T\&) विधि

मान प्रकारों को [Object](../../object/) में बदलने के लिए बॉक्स करता है। enum प्रकारों के लिए कार्यान्वयन।

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```

### Template parameters

| पैरामीटर | विवरण |
| --- | --- |
| T | [Enum](../../enum/) प्रकार। |

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const T\& | [Enum](../../enum/) मान को बॉक्स करने के लिए। |

### Return Value

स्मार्ट पॉइंटर ऑब्जेक्ट के लिए जो बॉक्स किया हुआ मान रखता है।

## ObjectExt::Box(const T\&) विधि

मान प्रकारों को [Object](../../object/) में बदलने के लिए बॉक्स करता है। नॉन-enum प्रकारों के लिए कार्यान्वयन।

```cpp
template<typename T> static std::enable_if<!std::is_enum<T>::value &&!IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```

### Template parameters

| पैरामीटर | विवरण |
| --- | --- |
| T | मान प्रकार। |

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const T\& | बॉक्स करने के लिए मान। |

### Return Value

स्मार्ट पॉइंटर ऑब्जेक्ट के लिए जो बॉक्स किया हुआ मान रखता है।

## ObjectExt::Box(const T\&) विधि

[Nullable](../../nullable/) प्रकारों को [Object](../../object/) में बदलने के लिए बॉक्स करता है।

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```

### Template parameters

| पैरामीटर | विवरण |
| --- | --- |
| T | मान प्रकार। |

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const T\& | बॉक्स करने के लिए मान। |

### Return Value

स्मार्ट पॉइंटर ऑब्जेक्ट के लिए जो बॉक्स किया हुआ मान रखता है।

## ObjectExt::Box(const String\&) विधि

स्ट्रिंग मानों को बॉक्स करता है।

```cpp
SmartPtr<Object> System::ObjectExt::Box(const String &value)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [String](../../string/)\& | बॉक्स करने के लिए मान। |

### Return Value

बॉक्स किया हुआ मान या null, यदि स्रोत स्ट्रिंग null है।

## और देखें

* क्लास [SmartPtr](../../smartptr/)
* क्लास [Object](../../object/)
* क्लास [ObjectExt](../)
* क्लास [String](../../string/)
* स्ट्रक्ट [IsNullable](../../isnullable/)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)