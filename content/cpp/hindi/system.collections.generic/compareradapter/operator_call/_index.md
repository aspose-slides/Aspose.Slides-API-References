---
title: operator()()
second_title: Aspose.Slides for C++ API संदर्भ
description: ऑपरेटर < उपलब्ध प्रकारों के लिए तुलना फ़ंक्शन।
type: docs
weight: 27
url: /hi/system.collections.generic/compareradapter/operator_call/
---
## ComparerAdapter::operator()(const Q\&, const Q\&) const विधि


[Comparison](../../../system/comparison/) फ़ंक्शन प्रकारों के लिए जिनमें operator < उपलब्ध है।

```cpp
template<typename Q> std::enable_if<detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Q | तुलना किया जाने वाला प्रकार; प्रकार परिवर्तन उपलब्धता के लिए टेम्पलेट। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | const Q\& | तुलना करने के लिए पहला मान। |
| y | const Q\& | तुलना करने के लिए दूसरा मान। |

### वापसी मान

True यदि **x** को **y** से छोटा माना जाता है, अन्यथा false।

## ComparerAdapter::operator()(const Q\&, const Q\&) const विधि


[Comparison](../../../system/comparison/) फ़ंक्शन उन प्रकारों के लिए जिनमें operator < उपलब्ध नहीं है।

```cpp
template<typename Q> std::enable_if<!detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Q | तुलना किया जाने वाला प्रकार; प्रकार परिवर्तन उपलब्धता के लिए टेम्पलेट। |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | const Q\& | तुलना करने के लिए पहला मान। |
| y | const Q\& | तुलना करने के लिए दूसरा मान। |

### वापसी मान

True यदि comparator सेट है और **x** को **y** से छोटा माना जाता है, अन्यथा false।

## देखें भी

* संरचना [ComparerAdapter](../)
* नामस्थान [System::Collections::Generic](../../)
* लाइब्रेरी [Aspose.Slides](../../../)