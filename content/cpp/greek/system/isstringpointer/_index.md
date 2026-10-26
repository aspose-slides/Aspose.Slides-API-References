---
title: IsStringPointer
second_title: Αναφορά API του Aspose.Slides για C++
description: Μαγικό πρότυπο για να ελέγξει αν ένας τύπος είναι δείκτης σε συμβολοσειρά χαρακτήρων.
type: docs
weight: 1717
url: /el/system/isstringpointer/
---
## IsStringPointer struct

Μαγικό πρότυπο για να ελέγξει αν ένας τύπος είναι δείκτης σε συμβολοσειρά χαρακτήρων.

```cpp
template<typename T,typename CharT>class IsStringPointer : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_pointer<T>::value>
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | ελεγμένος τύπος. |
| CharT | Τύπος χαρακτήρα προς έλεγχο. |

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)