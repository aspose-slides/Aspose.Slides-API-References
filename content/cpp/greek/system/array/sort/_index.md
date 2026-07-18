---
title: Sort()
second_title: Αναφορά API Aspose.Slides για C++
description: Ταξινομεί στοιχεία στον καθορισμένο πίνακα χρησιμοποιώντας τον προεπιλεγμένο συγκριτή.
type: docs
weight: 742
url: /el/system/array/sort/
---
## Array::Sort(const ArrayPtr\<Type\>\&) μέθοδος


Ταξινομεί στοιχεία στον καθορισμένο πίνακα χρησιμοποιώντας τον προεπιλεγμένο συγκριτή.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Πίνακας-στόχος |

## Array::Sort(const ArrayPtr\<Type\>\&, int, int) μέθοδος


Ταξινομεί μια περιοχή στοιχείων στον καθορισμένο πίνακα χρησιμοποιώντας τον προεπιλεγμένο συγκριτή.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, int startIndex, int count)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Πίνακας-στόχος |
| startIndex | int | Ο δείκτης που υποδεικνύει την αρχή της περιοχής των στοιχείων προς ταξινόμηση |
| count | int | Το μέγεθος της περιοχής των στοιχείων προς ταξινόμηση |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) μέθοδος


Ταξινομεί στοιχεία στον καθορισμένο πίνακα χρησιμοποιώντας τον καθορισμένο συγκριτή.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Πίνακας-στόχος |
| comparator | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<T\>\>\& | Αντικείμενο IComparer<T> που χρησιμοποιείται για τη σύγκριση των στοιχείων του πίνακα |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) μέθοδος


NOT IMPLEMENTED.

```cpp
template<typename Type,typename Y> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<Y>> &comparator)
```


## Array::Sort(const ArrayPtr\<Type\>\&, const System::Comparison\<T\>\&) μέθοδος


Ταξινομεί στοιχεία στον καθορισμένο πίνακα χρησιμοποιώντας την καθορισμένη σύγκριση.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const System::Comparison<T> &comparison)
```

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) μέθοδος


Ταξινομεί δύο πίνακες, έναν που περιέχει κλειδιά και τον άλλο – τα αντίστοιχα αντικείμενα, με βάση τις τιμές του πίνακα που περιέχει κλειδιά, των οποίων τα στοιχεία συγκρίνονται με τον τελεστή <.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TKey | Ο τύπος των στοιχείων στον **keys** πίνακα |
| TValue | Ο τύπος των στοιχείων στον **items** πίνακα |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) που περιέχει τιμές κλειδιών |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) που περιέχει αντικείμενα τα οποία αντιστοιχίζονται στις τιμές κλειδιών στον **keys** πίνακα |

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) μέθοδος


Ταξινομεί δύο πίνακες, έναν που περιέχει κλειδιά και τον άλλο – τα αντίστοιχα αντικείμενα, με βάση τις τιμές του πίνακα που περιέχει κλειδιά, των οποίων τα στοιχεία συγκρίνονται με τον προεπιλεγμένο συγκριτή.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items, int index, int length)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TKey | Ο τύπος των στοιχείων στον **keys** πίνακα |
| TValue | Ο τύπος των στοιχείων στον **items** πίνακα |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) που περιέχει τιμές κλειδιών |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) που περιέχει αντικείμενα τα οποία αντιστοιχίζονται στις τιμές κλειδιών στον **keys** πίνακα |
| index | int | Ο δείκτης που υποδεικνύει την αρχή της περιοχής προς ταξινόμηση |
| length | int | Ο αριθμός των στοιχείων στην περιοχή προς ταξινόμηση |

## Δείτε επίσης

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [Type](../../object/type/)
* Class [Array](../)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [Comparison](../../comparison/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)