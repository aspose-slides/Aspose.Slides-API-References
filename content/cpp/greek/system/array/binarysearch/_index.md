---
title: BinarySearch()
second_title: Aspose.Slides για C++ API Αναφορά
description: Εκτελεί δυαδική αναζήτηση στον ταξινομημένο πίνακα.
type: docs
weight: 612
url: /el/system/array/binarysearch/
---
## Array::BinarySearch(System::ArrayPtr\<T\>, const T\&) μέθοδος


Εκτελεί δυαδική αναζήτηση στον ταξινομημένο πίνακα.

```cpp
static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const T &item)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | Ταξινομημένος πίνακας για την εκτέλεση της αναζήτησης |
| item | const T\& | Ένα στοιχείο προς αναζήτηση |

### Τιμή Επιστροφής

Δείκτης του αναζητημένου στοιχείου εφόσον βρεθεί, διαφορετικά, ένας αρνητικός ακέραιος που είναι το δυαδικό συμπλήρωμα του δείκτη του επόμενου στοιχείου μεγαλύτερου από το αναζητημένο στοιχείο ή, εάν δεν υπάρχει μεγαλύτερο στοιχείο, το δυαδικό συμπλήρωμα του αριθμού των στοιχείων στο πίνακα.

## Array::BinarySearch(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) μέθοδος


ΔΕΝ ΥΛΟΠΟΙΗΘΕΙ.

```cpp
template<typename Y,typename Z> static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const Y &item, const SharedPtr<Collections::Generic::IComparer<Z>> &comparer)
```


## Δείτε Επίσης

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Κλάση [Array](../)
* Κλάση [IComparer](../../../system.collections.generic/icomparer/)
* Χώρος Ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)