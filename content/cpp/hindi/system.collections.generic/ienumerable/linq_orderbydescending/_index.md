---
title: LINQ_OrderByDescending()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक अनुक्रम के तत्वों को keySelector द्वारा चयनित कुंजी मानों के आधार पर अवरोही क्रम में क्रमबद्ध करता है।
type: docs
weight: 222
url: /hi/system.collections.generic/ienumerable/linq_orderbydescending/
---
## IEnumerable::LINQ_OrderByDescending(const Func\<T, Key\>\&) विधि


एक अनुक्रम के तत्वों को keySelector द्वारा चयनित कुंजी मानों के आधार पर अवरोही क्रम में क्रमबद्ध करता है।

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<T, Key> &keySelector)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| keySelector | एक फ़ंक्शन जो किसी तत्व से कुंजी निकालता है। |

### वापसी मान

एक IOrderedEnumerable जिसका तत्व कुंजी के अवरोही क्रम में क्रमबद्ध किया गया है।

## IEnumerable::LINQ_OrderByDescending(const Func\<Source, Key\>\&) विधि




```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<Source, Key> &keySelector)
```

## देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* क्लास [Func](../../../system/func/)
* क्लास [IEnumerable](../)
* नेमस्पेस [System::Collections::Generic](../../)
* लाइब्रेरी [Aspose.Slides](../../../)