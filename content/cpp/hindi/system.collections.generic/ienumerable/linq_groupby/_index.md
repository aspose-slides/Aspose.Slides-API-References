---
title: LINQ_GroupBy()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक अनुक्रम के तत्वों को समूहित करता है।
type: docs
weight: 287
url: /hi/system.collections.generic/ienumerable/linq_groupby/
---
## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>) विधि

एक अनुक्रम के तत्वों को समूहित करता है।

```cpp
template<typename Key> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, T>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Key | keyPredicate द्वारा लौटाए गए कुंजी का प्रकार |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | प्रत्येक तत्व के लिए कुंजी निकालने का फ़ंक्शन। |

### रिटर्न मान

एक [IEnumerable](../) जिसमें ऑब्जेक्ट्स का अनुक्रम और एक कुंजी होती है

## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>, System::Func\<T, Element\>) विधि

एक अनुक्रम के तत्वों को समूहित करता है।

```cpp
template<typename Key,typename Element> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate, System::Func<T, Element> elementSelector)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Key | keyPredicate द्वारा लौटाए गए कुंजी का प्रकार |
| Element | elementSelector द्वारा लौटाए गए तत्व का प्रकार |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | प्रत्येक तत्व के लिए कुंजी निकालने का फ़ंक्शन। |
| elementSelector | [System::Func](../../../system/func/)\<T, Element\> | प्रत्येक तत्व के लिए मान कुंजी निकालने का फ़ंक्शन। |

### रिटर्न मान

एक [IEnumerable](../) जिसमें ऑब्जेक्ट्स का अनुक्रम और एक कुंजी होती है

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>) विधि




```cpp
template<typename Key> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Source>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate)
```

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>, System::Func\<Source, Element\>) विधि




```cpp
template<typename Key,typename Element> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate, System::Func<Source, Element> elementSelector)
```

## संबंधित

* टाइपडेफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IEnumerable](../)
* क्लास [IGrouping](../../../system.linq/igrouping/)
* क्लास [Func](../../../system/func/)
* नेमस्पेस [System::Collections::Generic](../../)
* लाइब्रेरी [Aspose.Slides](../../../)