---
title: LINQ_Select()
second_title: Aspose.Slides για C++ Αναφορά API
description: Μετατρέπει στοιχεία μιας ακολουθίας.
type: docs
weight: 248
url: /el/system.collections.generic/ienumerable/linq_select/
---
## IEnumerable::LINQ_Select(const Func\<T, ResultType\>\&) μέθοδος

Μετατρέπει τα στοιχεία μιας ακολουθίας.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, ResultType> &selector)
```

### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| ResultType | The type of the value returned by the **selector**. |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | A transform function. |

### Τιμή επιστροφής

Ένα [IEnumerable](../) που περιέχει τα στοιχεία που επιστρέφει η συνάρτηση **selector**.

## IEnumerable::LINQ_Select(const Func\<T, int32_t, ResultType\>\&) μέθοδος

Μετασχηματίζει κάθε στοιχείο μιας ακολουθίας σε νέα μορφή ενσωματώνοντας το **int32_t** του στοιχείου.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, int32_t, ResultType> &selector)
```

### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| ResultType | The type of the value returned by the **selector**. |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, **int32_t**, ResultType\>\& | A transform function. |

### Τιμή επιστροφής

Ένα [IEnumerable](../) που περιέχει τα στοιχεία που επιστρέφει η συνάρτηση **selector**.

## IEnumerable::LINQ_Select(const Func\<Source, Result\>\&) μέθοδος




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, Result> &selector)
```

## IEnumerable::LINQ_Select(const Func\<Source, int32_t, Result\>\&) μέθοδος




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, int32_t, Result> &selector)
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IEnumerable](../)
* Κλάση [Func](../../../system/func/)
* Χώρος ονομάτων [System::Collections::Generic](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)