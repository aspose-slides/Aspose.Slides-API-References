---
title: BinarySearch()
second_title: Αναφορά API Aspose.Slides για C++
description: Αναζητά το στοιχείο σε μια ταξινομημένη λίστα.
type: docs
weight: 339
url: /el/system.collections.generic/list/binarysearch/
---
## List::BinarySearch(const T\&) const μέθοδος

Ψάχνει για το στοιχείο σε μια ταξινομημένη λίστα.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | const T\& | Στοιχείο προς αναζήτηση. |

### Τιμή Επιστροφής

Δείκτης του στοιχείου στην ταξινομημένη λίστα ή το συμπλήρωμα του κοντινότερου δείκτη.

## List::BinarySearch(const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const μέθοδος

Ψάχνει για το στοιχείο σε μια ταξινομημένη λίστα.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | const T\& | Στοιχείο προς αναζήτηση. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) προς χρήση. |

### Τιμή Επιστροφής

Δείκτης του στοιχείου στην ταξινομημένη λίστα ή το συμπλήρωμα του κοντινότερου δείκτη.

## List::BinarySearch(int, int, const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const μέθοδος

Ψάχνει για το στοιχείο σε μια ταξινομημένη λίστα.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(int index, int count, const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Αρχή του εύρους. |
| count | int | Μέγεθος του εύρους. |
| item | const T\& | Στοιχείο προς αναζήτηση. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) προς χρήση. |

### Τιμή Επιστροφας

Δείκτης του στοιχείου στην ταξινομημένη λίστα ή το συμπλήρωμα του κοντινότερου δείκτη.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [List](../)
* Κλάση [IComparer](../../icomparer/)
* Χώρος ονομάτων [System::Collections::Generic](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)