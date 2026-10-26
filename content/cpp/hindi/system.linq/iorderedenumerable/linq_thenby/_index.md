---
title: LINQ_ThenBy()
second_title: Aspose.Slides for C++ API संदर्भ
description: कुंजी के अनुसार अनुक्रम में तत्वों को बढ़ते क्रम में क्रमबद्ध करता है।
type: docs
weight: 27
url: /hi/system.linq/iorderedenumerable/linq_thenby/
---
## IOrderedEnumerable::LINQ_ThenBy(const Func\<T, Key\>\&) विधि

किसी कुंजी के अनुसार क्रम बढ़ते हुए, अनुक्रम में तत्वों को क्रमबद्ध करता है।

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<T>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<T, Key> &keySelector)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Key | keySelector द्वारा लौटाई गई कुंजी का प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| keySelector | const [Func](../../../system/func/)\<T, Key\>\& | प्रत्येक तत्व से कुंजी निकालने वाला फ़ंक्शन। |

### रिटर्न वैल्यू

[System::Linq::IOrderedEnumerable](../) जिसके तत्व एक कुंजी के अनुसार क्रमबद्ध किए गए हैं।

## IOrderedEnumerable::LINQ_ThenBy(const Func\<Source, Key\>\&) विधि

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<Source>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<Source, Key> &keySelector)
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOrderedEnumerable](../)
* Class [Func](../../../system/func/)
* Namespace [System::Linq](../../)
* Library [Aspose.Slides](../../../)