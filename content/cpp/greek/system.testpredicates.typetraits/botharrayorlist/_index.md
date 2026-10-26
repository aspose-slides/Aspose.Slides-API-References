---
title: BothArrayOrList
second_title: Aspose.Slides για αναφορά API C++
description: Ελέγχει αν και τα δύο επιχειρήματα τύπου είναι πίνακες ή λίστες. Εάν είναι έτσι, το μέλος value ορίζεται σε true, διαφορετικά ορίζεται σε false.
type: docs
weight: 131
url: /el/system.testpredicates.typetraits/botharrayorlist/
---
## BothArrayOrList typedef


Ελέγχει αν και τα δύο επιχειρήματα τύπου είναι πίνακες ή λίστες. Εάν είναι έτσι, το μέλος value ορίζεται σε true, διαφορετικά ορίζεται σε false.

```cpp
using System::TestPredicates::TypeTraits::BothArrayOrList = typedef std::integral_constant<bool, (IsArray<T1>::value || IsList<T1>::value) && (IsArray<T2>::value || IsList<T2>::value)>
```


## Δείτε επίσης

* Χώρος ονομάτων [System::TestPredicates::TypeTraits](../)
* Βιβλιοθήκη [Aspose.Slides](../../)