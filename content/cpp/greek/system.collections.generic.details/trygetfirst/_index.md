---
title: TryGetFirst()
second_title: Αναφορά API του Aspose.Slides για C++ 
description: Προσπαθεί να αποκτήσει το πρώτο στοιχείο της συλλογής.
type: docs
weight: 248
url: /el/system.collections.generic.details/trygetfirst/
---
## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, bool\&) συνάρτηση


Προσπαθεί να αποκτήσει το πρώτο στοιχείο της συλλογής.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, bool &found)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | The type of the collection elements. |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | Η συλλογή από την οποία θα ληφθεί ένα στοιχείο. |
| found | **bool**\& | Η παράμετρος εξόδου. Επιστρέφει true όταν η συλλογή περιέχει κάποιο στοιχείο. Διαφορετικά επιστρέφεται false. |

### Τιμή επιστροφής

Επιστρέφει το πρώτο στοιχείο της συλλογής. Η προεπιλεγμένη τιμή του τύπου θα επιστραφεί όταν η συλλογή είναι κενή.

## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, const Func\<T, bool\>\&, bool\&) συνάρτηση


Προσπαθεί να αποκτήσει το πρώτο στοιχείο της συλλογής που ικανοποιεί τη συνάρτηση πρόγνωσης.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, const Func<T, bool> &predicate, bool &found)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | The type of the collection elements. |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | Η συλλογή από την οποία θα ληφθεί ένα στοιχείο. |
| predicate | const [Func](../../system/func/)\<T, **bool**\>\& | Η συνάρτηση πρόγνωσης. |
| found | **bool**\& | Η παράμετρος εξόδου. Επιστρέφει true όταν η συλλογή περιέχει κάποιο στοιχείο. Διαφορετικά επιστρέφεται false. |

### Τιμή επιστροφής

Επιστρέφει το πρώτο στοιχείο της συλλογής. Η προεπιλεγμένη τιμή του τύπου θα επιστραφεί όταν δεν βρεθεί κανένα στοιχείο που ικανοποιεί τη συγκεκριμένη συνάρτηση πρόγνωσης.

## See Also

* Κλάση [IEnumerable](../../system.collections.generic/ienumerable/)
* Κλάση [Func](../../system/func/)
* Χώρος ονομάτων [System::Collections::Generic::Details](../)
* Βιβλιοθήκη [Aspose.Slides](../../)