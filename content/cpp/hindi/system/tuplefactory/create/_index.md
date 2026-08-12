---
title: Create()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक नया ट्यूपल ऑब्जेक्ट बनाता है।
type: docs
weight: 1
url: /hi/system/tuplefactory/create/
---
## TupleFactory::Create(Args...) विधि

एक नया ट्यूपल ऑब्जेक्ट बनाता है।

```cpp
template<typename ...> static SharedPtr<Tuple<Args...>> System::TupleFactory::Create(Args... args)
```

## TupleFactory::Create(T1, T2, T3, T4, T5, T6, T7, TRest) विधि

एक नया 8-ट्यूपल बनाता है। 8वां तत्व [Tuple](../../tuple/) के अंदर संग्रहीत किया जाता है।

```cpp
template<typename T1,typename T2,typename T3,typename T4,typename T5,typename T6,typename T7,typename TRest> static SharedPtr<Tuple<T1, T2, T3, T4, T5, T6, T7, SharedPtr<Tuple<TRest>>>> System::TupleFactory::Create(T1 item1, T2 item2, T3 item3, T4 item4, T5 item5, T6 item6, T7 item7, TRest rest)
```

## देखें

* टाइपडिफ़ [SharedPtr](../../sharedptr/)
* क्लास [Tuple](../../tuple/)
* क्लास [TupleFactory](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)