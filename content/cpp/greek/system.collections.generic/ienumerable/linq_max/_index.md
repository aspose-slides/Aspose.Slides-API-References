---
title: LINQ_Max()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καλεί μια συνάρτηση μετασχηματισμού σε κάθε στοιχείο μιας γενικής ακολουθίας και επιστρέφει τη μέγιστη προκύπτουσα τιμή.
type: docs
weight: 339
url: /el/system.collections.generic/ienumerable/linq_max/
---
## IEnumerable::LINQ_Max(const Func\<T, ResultType\>\&) μέθοδος

Καλεί μια συνάρτηση μετασχηματισμού σε κάθε στοιχείο μιας γενικής ακολουθίας και επιστρέφει τη μέγιστη προκύπτουσα τιμή.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<T, ResultType> &selector)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| ResultType | Ο τύπος της τιμής που επιστρέφεται από τον selector. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Μια συνάρτηση μετασχηματισμού για εφαρμογή σε κάθε στοιχείο. |

### Return Value

Η μέγιστη τιμή στην ακολουθία.

## IEnumerable::LINQ_Max(const Func\<Source, ResultType\>\&) μέθοδος

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<Source, ResultType> &selector)
```

## See Also

* Κλάση [Func](../../../system/func/)
* Κλάση [IEnumerable](../)
* Χώρος ονομάτων [System::Collections::Generic](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)