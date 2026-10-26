---
title: IsStringLiteral
second_title: Αναφορά API του Aspose.Slides για C++
description: Μαγικό πρότυπο για έλεγχο αν ένας τύπος είναι κυριολεκτικό συμβολοσειράς.
type: docs
weight: 1704
url: /el/system/isstringliteral/
---
## IsStringLiteral struct


Μαγικό πρότυπο για έλεγχο αν ένας τύπος είναι κυριολεκτικό συμβολοσειράς.

```cpp
template<typename T,typename CharT>class IsStringLiteral : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_array<T>::value>
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | ελεγμένος τύπος. |
| CharT | Τύπος χαρακτήρα για σύγκριση. |

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)