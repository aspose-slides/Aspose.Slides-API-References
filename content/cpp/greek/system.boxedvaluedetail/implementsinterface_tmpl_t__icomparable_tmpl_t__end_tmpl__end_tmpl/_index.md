---
title: ImplementsInterface< T, IComparable< T > >
second_title: Aspose.Slides για C++ Αναφορά API
description: Πρότυπο πρόταση που ελέγχει εάν το συσκευασμένο αντικείμενο πρέπει να υλοποιήσει τη διεπαφή IComparable από μόνο του.
type: docs
weight: 53
url: /el/system.boxedvaluedetail/implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/
---
## ImplementsInterface< T, IComparable< T > > struct


Πρότυπο πρόταση που ελέγχει αν το συσκευασμένο αντικείμενο πρέπει να υλοποιήσει τη διεπαφή [IComparable](../../system/icomparable/) από μόνο του.

```cpp
template<typename T>class ImplementsInterface< T, IComparable< T > > : public std::integral_constant<bool, std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

## Δείτε επίσης

* Χώρος ονομάτων [System::BoxedValueDetail](../)
* Βιβλιοθήκη [Aspose.Slides](../../)