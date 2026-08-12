---
title: Equals()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: operator==() का उपयोग करके निर्धारित मान की समानता निर्धारित करता है।
type: docs
weight: 66
url: /hi/system.boxedvaluedetail/equals/
---
## System::BoxedValueDetail::Equals(T, T) फ़ंक्शन

निर्दिष्ट मान की समानता को [operator==()](../../system/operator_equal_equal/) का उपयोग करके निर्धारित करता है।

```cpp
template<typename T> std::enable_if<detail::has_operator_equal<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| The | तुलना किए जा रहे मानों का प्रकार |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value1 | T | पहला तुल्य |
| value2 | T | दूसरा तुल्य |

### रिटर्न वैल्यू

यदि निर्दिष्ट मान [operator==()](../../system/operator_equal_equal/) द्वारा निर्धारित समान हो तो True, अन्यथा - false।

## System::BoxedValueDetail::Equals(T, T) फ़ंक्शन

निर्दिष्ट मान की समानता को विधि [System::Object::Equals()](../../system/object/equals/) का उपयोग करके निर्धारित करता है।

```cpp
template<typename T> std::enable_if<detail::has_only_method_equals<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| The | तुलना किए जा रहे मानों का प्रकार |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value1 | T | पहला तुल्य |
| value2 | T | दूसरा तुल्य |

### रिटर्न वैल्यू

यदि निर्दिष्ट मान विधि [Equals()](./) द्वारा निर्धारित समान हो तो True, अन्यथा - false।

## देखें

* नेमस्पेस [System::BoxedValueDetail](../)
* लाइब्रेरी [Aspose.Slides](../../)