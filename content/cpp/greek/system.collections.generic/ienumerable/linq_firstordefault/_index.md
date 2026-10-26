---
title: LINQ_FirstOrDefault()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει το πρώτο στοιχείο μιας ακολουθίας ή μια προεπιλεγμένη τιμή εάν η ακολουθία είναι κενή.
type: docs
weight: 66
url: /el/system.collections.generic/ienumerable/linq_firstordefault/
---
## IEnumerable::LINQ_FirstOrDefault() μέθοδος


Επιστρέφει το πρώτο στοιχείο μιας ακολουθίας ή μια προεπιλεγμένη τιμή εάν η ακολουθία είναι κενή.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault()
```


### Τιμή Επιστροφής

Πρώτο στοιχείο στην ακολουθία ή τιμή προεπιλεγμένης κατασκευής εάν η ακολουθία είναι κενή.

## IEnumerable::LINQ_FirstOrDefault(std::function\<bool(T)>) μέθοδος


Επιστρέφει το πρώτο στοιχείο της ακολουθίας που ικανοποιεί μια συνθήκη ή μια προεπιλεγμένη τιμή εάν δεν βρεθεί τέτοιο στοιχείο.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault(std::function<bool(T)> predicate)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | Μία συνάρτηση για τη δοκιμή κάθε στοιχείου ως προς μια συνθήκη. |

### Τιμή Επιστροφής

default(T) εάν η πηγή είναι κενή ή εάν κανένα στοιχείο δεν περνάει τη δοκιμή που ορίζεται από το predicate· διαφορετικά, το πρώτο στοιχείο στην πηγή που περνάει τη δοκιμή που ορίζεται από το predicate.

## Δείτε επίσης

* Κλάση [IEnumerable](../)
* Χώρος ονομάτων [System::Collections::Generic](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)