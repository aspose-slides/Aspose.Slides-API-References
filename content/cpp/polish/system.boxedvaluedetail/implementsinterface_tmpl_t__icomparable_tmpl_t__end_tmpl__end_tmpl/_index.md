---
title: ImplementsInterface< T, IComparable< T > >
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Predykat szablonu, który sprawdza, czy opakowany obiekt powinien samodzielnie implementować interfejs IComparable.
type: docs
weight: 53
url: /pl/system.boxedvaluedetail/implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/
---
## ImplementsInterface< T, IComparable< T > > struct


Szablon predykatu, który sprawdza, czy opakowany obiekt powinien samodzielnie implementować interfejs [IComparable](../../system/icomparable/).

```cpp
template<typename T>class ImplementsInterface< T, IComparable< T > > : public std::integral_constant<bool, std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

## Zobacz także

* Przestrzeń nazw [System::BoxedValueDetail](../)
* Biblioteka [Aspose.Slides](../../)