---
title: CopyTo()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αντιγράφει όλα τα στοιχεία του τρέχοντα πίνακα στον καθορισμένο πίνακα προορισμού. Τα στοιχεία εισάγονται στον πίνακα προορισμού ξεκινώντας από το δείκτη που καθορίζεται από το όρισμα arrayIndex.
type: docs
weight: 118
url: /el/system/array/copyto/
---
## Array::CopyTo(ArrayPtr\<T\>, int) μέθοδος

Αντιγράφει όλα τα στοιχεία του τρέχοντα πίνακα στον καθορισμένο πίνακα προορισμού. Τα στοιχεία εισάγονται στον πίνακα προορισμού ξεκινώντας από το δείκτη που καθορίζεται από το όρισμα arrayIndex.

```cpp
virtual void System::Array<T>::CopyTo(ArrayPtr<T> arr, int arrayIndex) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | Destination array |
| arrayIndex | int | Index in destination array to start inserting copied items at |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t) const μέθοδος

Αντιγράφει όλα τα στοιχεία του τρέχοντα πίνακα στον καθορισμένο πίνακα προορισμού. Τα στοιχεία εισάγονται στον πίνακα προορισμού ξεκινώντας από το δείκτη που καθορίζεται από το όρισμα dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t dstIndex) const
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| DstType | Type of elements in destination array |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Destination array |
| dstIndex | **int64_t** | Index in destination array to start inserting copied items at |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t) const μέθοδος

Αντιγράφει όλα τα στοιχεία του τρέχοντα πίνακα στην καθορισμένη προβολή πίνακα προορισμού. Τα στοιχεία εισάγονται στην προβολή πίνακα προορισμού ξεκινώντας από το δείκτη που καθορίζεται από το όρισμα dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t dstIndex) const
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| DstType | Type of elements in destination array view |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Destination array view |
| dstIndex | **int64_t** | Index in destination array view to start inserting copied items at |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t, int64_t, int64_t) const μέθοδος

Αντιγράφει έναν καθορισμένο αριθμό στοιχείων από τον τρέχοντα πίνακα, αρχίζοντας από τη συγκεκριμένη θέση, σε έναν καθορισμένο πίνακα προορισμού. Τα στοιχεία εισάγονται στον πίνακα προορισμού ξεκινώντας από το δείκτη που καθορίζεται από το όρισμα dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| DstType | Type of elements in destination array |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Destination array |
| srcIndex | **int64_t** | Index in source array to start copying items at |
| dstIndex | **int64_t** | Index in destination array to start inserting copied items at |
| count | **int64_t** | Number of elements to copy |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t, int64_t, int64_t) const μέθοδος

Αντιγράφει έναν καθορισμένο αριθμό στοιχείων από τον τρέχοντα πίνακα, αρχίζοντας από τη συγκεκριμένη θέση, σε μια καθορισμένη προβολή πίνακα προορισμού. Τα στοιχεία εισάγονται στην προβολή πίνακα προορισμού ξεκινώντας από το δείκτη που καθορίζεται από το όρισμα dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| DstType | Type of elements in destination array view |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Destination array view |
| srcIndex | **int64_t** | Index in source array to start copying items at |
| dstIndex | **int64_t** | Index in destination array view to start inserting copied items at |
| count | **int64_t** | Number of elements to copy |

## Δείτε επίσης

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)