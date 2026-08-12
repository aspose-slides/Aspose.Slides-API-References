---
title: ImplementsInterface< T, IComparable< T > >
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक टेम्पलेट प्रेडिकेट जो जांचता है कि बॉक्स्ड ऑब्जेक्ट को स्वयं IComparable इंटरफ़ेस लागू करना चाहिए।
type: docs
weight: 53
url: /hi/system.boxedvaluedetail/implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/
---
## ImplementsInterface< T, IComparable< T > > struct


एक टेम्पलेट प्रेडिकेट जो जांचता है कि बॉक्स्ड ऑब्जेक्ट को [IComparable](../../system/icomparable/) इंटरफ़ेस स्वयं लागू करना चाहिए।

```cpp
template<typename T>class ImplementsInterface< T, IComparable< T > > : public std::integral_constant<bool, std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

## संबंधित देखें

* नामस्थान [System::BoxedValueDetail](../)
* लाइब्रेरी [Aspose.Slides](../../)