---
title: IsBoxable
second_title: Aspose.Slides για C++ Αναφορά API
description: Πρότυπο πρόταση που ελέγχει εάν η συσκευασία του καθορισμένου τύπου υποστηρίζεται.
type: docs
weight: 1639
url: /el/system/isboxable/
---
## IsBoxable struct

Πρότυπο πρόταση που ελέγχει εάν η συσκευασία του καθορισμένου τύπου υποστηρίζεται.

```cpp
template<typename T>class IsBoxable : public std::integral_constant<bool, std::is_base_of<Details::BoxableObjectBase, T>::value||std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος προς έλεγχο |

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Library [Aspose.Slides](../../)