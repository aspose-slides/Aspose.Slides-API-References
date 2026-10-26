---
title: LINQ_Min()
second_title: Aspose.Slides για C++ API Αναφορά
description: Καλεί μια συνάρτηση μετασχηματισμού σε κάθε στοιχείο μιας γενικής ακολουθίας και επιστρέφει την ελάχιστη προκύπτουσα τιμή.
type: docs
weight: 326
url: /el/system.collections.generic/ienumerable/linq_min/
---
## IEnumerable::LINQ_Min(const Func\<T, ResultType\>\&) μέθοδος


Καλεί μια συνάρτηση μετασχηματισμού σε κάθε στοιχείο μιας γενικής ακολουθίας και επιστρέφει την ελάχιστη προκύπτουσα τιμή.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<T, ResultType> &selector)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| ResultType | Ο τύπος της τιμής που επιστρέφεται από τη selector. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Μια συνάρτηση μετασχηματισμού που εφαρμόζεται σε κάθε στοιχείο. |

### Τιμή επιστροφής

Η ελάχιστη τιμή στην ακολουθία.

## IEnumerable::LINQ_Min(const Func\<Source, ResultType\>\&) μέθοδος




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<Source, ResultType> &selector)
```

## Δείτε επίσης

* Κλάση [Func](../../../system/func/)
* Κλάση [IEnumerable](../)
* Χώρος ονομάτων [System::Collections::Generic](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)