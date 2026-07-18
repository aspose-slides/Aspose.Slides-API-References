---
title: LINQ_SelectMany()
second_title: Αναφορά API του Aspose.Slides για C++
description: Εφαρμόζει μια λειτουργία σε κάθε στοιχείο μιας ακολουθίας και συνδυάζει τις προκύπτουσες ακολουθίες σε μία ακολουθία.
type: docs
weight: 300
url: /el/system.collections.generic/ienumerable/linq_selectmany/
---
## IEnumerable::LINQ_SelectMany(const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\&) μέθοδος

Εφαρμόζει μια λειτουργία σε κάθε στοιχείο μιας ακολουθίας και συνδυάζει τις προκύπτουσες ακολουθίες σε μία ακολουθία.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<T, SharedPtr<IEnumerable<ResultType>>> &selector)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| ResultType | Ο τύπος της τιμής που επιστρέφεται από τον **selector**. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, [SharedPtr](../../../system/sharedptr/)\<[IEnumerable](../)\<ResultType\>\>\>\& | Μια λειτουργία μετασχηματισμού. |

### Τιμή επιστροφής

Ένα [IEnumerable](../) που περιέχει το αποτέλεσμα της κλήσης μιας συνάρτησης προβολής ένα-προς-πολλά σε κάθε στοιχείο της εισερχόμενης ακολουθίας.

## IEnumerable::LINQ_SelectMany(const Func\<Source, SharedPtr\<IEnumerable\<Result\>\>\>\&) μέθοδος




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<Source, SharedPtr<IEnumerable<Result>>> &selector)
```

## Δείτε επίσης

* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [IEnumerable](../)
* Κλάση [Func](../../../system/func/)
* Χώρος ονομάτων [System::Collections::Generic](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)