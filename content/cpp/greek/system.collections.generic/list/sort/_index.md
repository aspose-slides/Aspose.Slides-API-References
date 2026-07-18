---
title: Sort()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ταξινομεί τα στοιχεία στη λίστα.
type: docs
weight: 521
url: /el/system.collections.generic/list/sort/
---
## List::Sort(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) μέθοδος


Ταξινομεί τα στοιχεία στη λίστα.

```cpp
void System::Collections::Generic::List<T>::Sort(const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| comparator | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | Σύγκριτρος προς χρήση. |

## List::Sort() μέθοδος


Ταξινομεί τα στοιχεία στη λίστα χρησιμοποιώντας το προεπιλεγμένο σύγκριτο.

```cpp
void System::Collections::Generic::List<T>::Sort()
```

## List::Sort(int, int, SharedPtr\<System::Collections::Generic::IComparer\<T\>\>) μέθοδος


Ταξινομεί τα στοιχεία στο τμήμα της λίστας.

```cpp
void System::Collections::Generic::List<T>::Sort(int index, int count, SharedPtr<System::Collections::Generic::IComparer<T>> comparator)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης έναρξης τμήματος. |
| count | int | Μέγεθος τμήματος. |
| comparator | [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\> | Σύγκριτρος προς χρήση. |

## List::Sort(Comparison\<T\>, bool) μέθοδος


Ταξινομεί τα στοιχεία στη λίστα.

```cpp
void System::Collections::Generic::List<T>::Sort(Comparison<T> comparison, bool)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| comparison | [Comparison](../../../system/comparison/)\<T\> | [Comparison](../../../system/comparison/) για χρήση. |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IComparer](../../icomparer/)
* Κλάση [List](../)
* Κλάση [Comparison](../../../system/comparison/)
* Χώρος ονομάτων [System::Collections::Generic](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)