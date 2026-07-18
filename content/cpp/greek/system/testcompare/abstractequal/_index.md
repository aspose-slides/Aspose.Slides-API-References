---
title: AbstractEqual()
second_title: Aspose.Slides για C++ API Reference
description: Συγκρίνει δύο συλλογές άγνωστου τύπου.
type: docs
weight: 14
url: /el/system/testcompare/abstractequal/
---
## TestCompare::AbstractEqual(SCG::ICollection\<T\> *const, SCG::ICollection\<T\> *const) μέθοδος


Συγκρίνει δύο συλλογές άγνωστου τύπου.

```cpp
template<typename T> static bool System::TestCompare::AbstractEqual(SCG::ICollection<T> *const collA, SCG::ICollection<T> *const collB)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος στοιχείου συλλογής. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| collA | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | Συλλογή στην αριστερή πλευρά. |
| collB | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | Συλλογή στην δεξιά πλευρά. |

### Τιμή Επιστροφής

true εάν οι συλλογές ταιριάζουν (π.χ. και οι δύο είναι null), ή εάν τα μεγέθη ταιριάζουν και τα στοιχεία ταιριάζουν, false διαφορετικά.

## Δείτε επίσης

* Κλάση [ICollection](../../../system.collections.generic/icollection/)
* Δομή [TestCompare](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)