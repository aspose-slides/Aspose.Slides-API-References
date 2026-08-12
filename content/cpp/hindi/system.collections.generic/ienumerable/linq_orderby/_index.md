---
title: LINQ_OrderBy()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: क्रम में तत्वों को आरोही क्रम में क्रमबद्ध करता है, जहाँ कुंजी मान keySelector द्वारा चुने जाते हैं।
type: docs
weight: 209
url: /hi/system.collections.generic/ienumerable/linq_orderby/
---
## IEnumerable::LINQ_OrderBy(const Func\<T, Key\>\&) मेथड

एक क्रम में तत्वों को आरोही क्रम में क्रमबद्ध करता है, जहाँ कुंजी मान keySelector द्वारा चुने जाते हैं।

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<T, Key> &keySelector)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| keySelector | एक फ़ंक्शन जो तत्व से कुंजी निकालता है। |

### रिटर्न मान

एक IOrderedEnumerable जिसके तत्व एक कुंजी के अनुसार क्रमबद्ध होते हैं।

## IEnumerable::LINQ_OrderBy(const Func\<Source, Key\>\&) मेथड



```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<Source, Key> &keySelector)
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* क्लास [Func](../../../system/func/)
* क्लास [IEnumerable](../)
* नेमस्पेस [System::Collections::Generic](../../)
* लाइब्रेरी [Aspose.Slides](../../../)