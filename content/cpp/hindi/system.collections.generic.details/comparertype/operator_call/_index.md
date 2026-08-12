---
title: operator()()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: IComparable इंटरफ़ेस को लागू करने वाले मान प्रकारों की तुलना करता है।
type: docs
weight: 1
url: /hi/system.collections.generic.details/comparertype/operator_call/
---
## ComparerType::operator()(const Q\&, const Q\&) const विधि

[IComparable](../../../system/icomparable/) इंटरफ़ेस को लागू करने वाले मान प्रकारों की तुलना करता है।

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<Q>, Q>::value||has_method_compareto<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Q | तुलना करने के लिए प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| a | const Q\& | बाएं हाथ का मान। |
| b | const Q\& | दाएं हाथ का मान। |

### रिटर्न वैल्यू

यदि **a** को **b** से कम माना जाता है तो True, अन्यथा false।

## ComparerType::operator()(const Q\&, const Q\&) const विधि

[IComparable](../../../system/icomparable/) इंटरफ़ेस को लागू नहीं करने वाले प्रिमिटिव मान प्रकारों और ऑब्जेक्ट्स की तुलना करता है।

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<IComparable<Q>, Q>::value||has_method_compareto<Q>::value)&&!std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Q | तुलना करने के लिए प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| a | const Q\& | बाएं हाथ का मान। |
| b | const Q\& | दाएं हाथ का मान। |

### रिटर्न वैल्यू

यदि **a** को **b** से कम माना जाता है तो True, अन्यथा false।

## ComparerType::operator()(const Q\&, const Q\&) const विधि

फ्लोटिंग पॉइंट प्रकारों की तुलना करता है।

```cpp
template<typename Q> std::enable_if<std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Q | तुलना करने के लिए प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| a | const Q\& | बाएं हाथ का मान। |
| b | const Q\& | दाएं हाथ का मान। |

### रिटर्न वैल्यू

यदि **a** को **b** से कम माना जाता है तो True, अन्यथा false।

## See Also

* Class [IComparable](../../../system/icomparable/)
* Struct [has_method_compareto](../../has_method_compareto/)
* Struct [ComparerType](../)
* Namespace [System::Collections::Generic::Details](../../)
* Library [Aspose.Slides](../../../)