---
title: Copy()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αντιγράφει τον καθορισμένο αριθμό στοιχείων από τον πηγαίο πίνακα στον πίνακα προορισμού.
type: docs
weight: 729
url: /el/system/array/copy/
---
## Array::Copy(const ArrayPtr\<SrcType\>\&, const ArrayPtr\<DstType\>\&, int64_t) μέθοδος

Αντιγράφει τον καθορισμένο αριθμό στοιχείων από τον πηγαίο πίνακα στον πίνακα προορισμού.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Πηγαίος πίνακας |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Πίνακας προορισμού |
| count | **int64_t** | Ο αριθμός των στοιχείων προς αντιγραφή |

## Array::Copy(System::Details::ArrayView\<SrcType\>, const ArrayPtr\<DstType\>\&, int64_t) μέθοδος

Αντιγράφει τον καθορισμένο αριθμό στοιχείων από την προβολή του πηγαίου πίνακα στον πίνακα προορισμού.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Πηγαία προβολή πίνακα |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Πίνακας προορισμού |
| count | **int64_t** | Ο αριθμός των στοιχείων προς αντιγραφή |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::ArrayView\<DstType\>, int64_t) μέθοδος

Αντιγράφει τον καθορισμένο αριθμό στοιχείων από τον πηγαίο πίνακα στην προβολή του πίνακα προορισμού.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Πηγαίος πίνακας |
| dstArray | System::Details::ArrayView\<DstType\> | Προβολή πίνακα προορισμού |
| count | **int64_t** | Ο αριθμός των στοιχείων προς αντιγραφή |

## Array::Copy(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, int64_t) μέθοδος

Αντιγράφει τον καθορισμένο αριθμό στοιχείων από την προβολή του πηγαίου πίνακα στην προβολή του πίνακα προορισμού.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Πηγαία προβολή πίνακα |
| dstArray | System::Details::ArrayView\<DstType\> | Προβολή πίνακα προορισμού |
| count | **int64_t** | Ο αριθμός των στοιχείων προς αντιγραφή |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, const ArrayPtr\<DstType\>\&, int64_t) μέθοδος

Αντιγράφει τον καθορισμένο αριθμό στοιχείων από τον πηγαίο πίνακα στην στοίβα στον πίνακα προορισμού.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Πηγαίος πίνακας στην στοίβα |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Πίνακας προορισμού |
| count | **int64_t** | Ο αριθμός των στοιχείων προς αντιγραφή |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, int64_t) μέθοδος

Αντιγράφει τον καθορισμένο αριθμό στοιχείων από τον πηγαίο πίνακα στην στοίβα του πίνακα προορισμού.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::StackArray<DstType, N> &dstArray, int64_t count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Πηγαίος πίνακας |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Πίνακας προορισμού στην στοίβα |
| count | **int64_t** | Ο αριθμός των στοιχείων προς αντιγραφή |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, int64_t) μέθοδος

Αντιγράφει τον καθορισμένο αριθμό στοιχείων από τον πηγαίο πίνακα στην στοίβα στον πίνακα προορισμού στην στοίβα.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, System::Details::StackArray<DstType, ND> &dstArray, int64_t count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Πηγαίος πίνακας στην στοίβα |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Πίνακας προορισμού στην στοίβα |
| count | **int64_t** | Ο αριθμός των στοιχείων προς αντιγραφή |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) μέθοδος

Αντιγράφει έναν καθορισμένο αριθμό στοιχείων από τον πηγαίο πίνακα, αρχίζοντας από το καθορισμένο ευρετήριο, στη συγκεκριμένη θέση του πίνακα προορισμού.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| SrcType | Τύπος των στοιχείων στον πηγαίο πίνακα |
| DstType | Τύπος των στοιχείων στον πίνακα προορισμού |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Πηγαίος πίνακας |
| srcIndex | **int64_t** | Ευρετήριο στον πηγαίο πίνακα που ορίζει την αρχή της περιοχής των στοιχείων προς αντιγραφή |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Πίνακας προορισμού |
| dstIndex | **int64_t** | Ευρετήριο στον πίνακα προορισμού όπου αρχίζει η εισαγωγή των αντιγραφόμενων στοιχείων |
| count | **int64_t** | Ο αριθμός των στοιχείων προς αντιγραφή |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) μέθοδος

Αντιγράφει έναν καθορισμένο αριθμό στοιχείων από την προβολή του πηγαίου πίνακα, αρχίζοντας από το καθορισμένο ευρετήριο, στη συγκεκριμένη θέση του πίνακα προορισμού.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| SrcType | Τύπος των στοιχείων στην προβολή του πηγαίου πίνακα |
| DstType | Τύπος των στοιχείων στον πίνακα προορισμού |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Πηγαία προβολή πίνακα |
| srcIndex | **int64_t** | Ευρετήριο στην προβολή του πηγαίου πίνακα που ορίζει την αρχή της περιοχής των στοιχείων προς αντιγραφή |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Πίνακας προορισμού |
| dstIndex | **int64_t** | Ευρετήριο στον πίνακα προορισμού όπου αρχίζει η εισαγωγή των αντιγραφόμενων στοιχείων |
| count | **int64_t** | Ο αριθμός των στοιχείων προς αντιγραφή |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) μέθοδος

Αντιγράφει έναν καθορισμένο αριθμό στοιχείων από τον πηγαίο πίνακα, αρχίζοντας από το καθορισμένο ευρετήριο, στη συγκεκριμένη θέση της προβολής του πίνακα προορισμού.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| SrcType | Τύπος των στοιχείων στον πηγαίο πίνακα |
| DstType | Τύπος των στοιχείων στην προβολή του πίνακα προορισμού |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Πηγαίος πίνακας |
| srcIndex | **int64_t** | Ευρετήριο στον πηγαίο πίνακα που ορίζει την αρχή της περιοχής των στοιχείων προς αντιγραφή |
| dstArray | System::Details::ArrayView\<DstType\> | Προβολή πίνακα προορισμού |
| dstIndex | **int64_t** | Ευρετήριο στην προβολή του πίνακα προορισμού όπου αρχίζει η εισαγωγή των αντιγραφόμενων στοιχείων |
| count | **int64_t** | Ο αριθμός των στοιχείων προς αντιγραφή |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) μέθοδος

Αντιγράφει έναν καθορισμένο αριθμό στοιχείων από την προβολή του πηγαίου πίνακα, αρχίζοντας από το καθορισμένο ευρετήριο, στη συγκεκριμένη θέση της προβολής του πίνακα προορισμού.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| SrcType | Τύπος των στοιχείων στην προβολή του πηγαίου πίνακα |
| DstType | Τύπος των στοιχείων στην προβολή του πίνακα προορισμού |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Πηγαία προβολή πίνακα |
| srcIndex | **int64_t** | Ευρετήριο στην προβολή του πηγαίου πίνακα που ορίζει την αρχή της περιοχής των στοιχείων προς αντιγραφή |
| dstArray | System::Details::ArrayView\<DstType\> | Προβολή πίνακα προορισμού |
| dstIndex | **int64_t** | Ευρετήριο στην προβολή του πίνακα προορισμού όπου αρχίζει η εισαγωγή των αντιγραφόμενων στοιχείων |
| count | **int64_t** | Ο αριθμός των στοιχείων προς αντιγραφή |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) μέθοδος

Αντιγράφει έναν καθορισμένο αριθμό στοιχείων από τον πηγαίο πίνακα στην στοίβα, αρχίζοντας από το καθορισμένο ευρετήριο, στη συγκεκριμένη θέση του πίνακα προορισμού.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| SrcType | Τύπος των στοιχείων στον πηγαίο πίνακα στην στοίβα |
| DstType | Τύπος των στοιχείων στον πίνακα προορισμού |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Πηγαίος πίνακας στην στοίβα |
| srcIndex | **int64_t** | Ευρετήριο στον πηγαίο πίνακα στην στοίβα που ορίζει την αρχή της περιοχής των στοιχείων προς αντιγραφή |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Πίνακας προορισμού |
| dstIndex | **int64_t** | Ευρετήριο στον πίνακα προορισμού όπου αρχίζει η εισαγωγή των αντιγραφόμενων στοιχείων |
| count | **int64_t** | Ο αριθμός των στοιχείων προς αντιγραφή |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, N\>\&, int64_t, int64_t) μέθοδος

Αντιγράφει έναν καθορισμένο αριθμό στοιχείων από τον πηγαίο πίνακα, αρχίζοντας από το καθορισμένο ευρετήριο, στη συγκεκριμένη θέση του πίνακα προορισμού στην στοίβα.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, N> &dstArray, int64_t dstIndex, int64_t count)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| SrcType | Τύπος των στοιχείων στον πηγαίο πίνακα |
| DstType | Τύπος των στοιχείων στον πίνακα προορισμού στην στοίβα |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Πηγαίος πίνακας |
| srcIndex | **int64_t** | Ευρετήριο στον πηγαίο πίνακα που ορίζει την αρχή της περιοχής των στοιχείων προς αντιγραφή |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Πίνακας προορισμού στην στοίβα |
| dstIndex | **int64_t** | Ευρετήριο στον πίνακα προορισμού στην στοίβα όπου αρχίζει η εισαγωγή των αντιγραφόμενων στοιχείων |
| count | **int64_t** | Ο αριθμός των στοιχείων προς αντιγραφή |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) μέθοδος

Αντιγράφει έναν καθορισμένο αριθμό στοιχείων από τον πηγαίο πίνακα στην στοίβα, αρχίζοντας από το καθορισμένο ευρετήριο, στη συγκεκριμένη θέση του πίνακα προορισμού στην στοίβα.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| SrcType | Τύπος των στοιχείων στον πηγαίο πίνακα στην στοίβα |
| DstType | Τύπος των στοιχείων στον πίνακα προορισμού στην στοίβα |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Πηγαίος πίνακας στην στοίβα |
| srcIndex | **int64_t** | Ευρετήριο στον πηγαίο πίνακα στην στοίβα που ορίζει την αρχή της περιοχής των στοιχείων προς αντιγραφή |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Πίνακας προορισμού στην στοίβα |
| dstIndex | **int64_t** | Ευρετήριο στον πίνακα προορισμού στην στοίβα όπου αρχίζει η εισαγωγή των αντιγραφόμενων στοιχείων |
| count | **int64_t** | Ο αριθμός των στοιχείων προς αντιγραφή |

## Array::Copy(System::Details::ArrayView\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) μέθοδος

Αντιγράφει έναν καθορισμένο αριθμό στοιχείων από την προβολή του πηγαίου πίνακα, αρχίζοντας από το καθορισμένο ευρετήριο, στη συγκεκριμένη θέση του πίνακα προορισμού στην στοίβα.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| SrcType | Τύπος των στοιχείων στην προβολή του πηγαίου πίνακα στην στοίβα |
| DstType | Τύπος των στοιχείων στον πίνακα προορισμού στην στοίβα |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\>\& | Πηγαία προβολή πίνακα |
| srcIndex | **int64_t** | Ευρετήριο στην προβολή του πηγαίου πίνακα που ορίζει την αρχή της περιοχής των στοιχείων προς αντιγραφή |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Πίνακας προορισμού στην στοίβα |
| dstIndex | **int64_t** | Ευρετήριο στον πίνακα προορισμού στην στοίβα όπου αρχίζει η εισαγωγή των αντιγραφόμενων στοιχείων |
| count | **int64_t** | Ο αριθμός των στοιχείων προς αντιγραφή |

## Δείτε επίσης

* Typedef [ArrayPtr](../../arrayptr/)
* Κλάση [Array](../)
* Χώρος ονομάτων [System](../../)
* Library [Aspose.Slides](../../../)