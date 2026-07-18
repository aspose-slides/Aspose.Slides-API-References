---
title: EqualityComparerAdapter
second_title: Αναφορά API του Aspose.Slides για C++
description: "Προσαρμογέας που καθιστά δυνατή τη χρήση του IEqualityComparer με συλλογές και αλγόριθμους τύπου STL. Χρησιμοποιεί το IEqualityComparer, εάν έχει οριστεί. Εάν δεν έχει οριστεί, χρησιμοποιεί τον τελεστή ==, Object::Equals ή T::Equals, όποιο είναι διαθέσιμο."
type: docs
weight: 664
url: /el/system.collections.generic/equalitycompareradapter/
---
## EqualityComparerAdapter struct

Adapter που καθιστά δυνατή τη χρήση του [IEqualityComparer](../iequalitycomparer/) με συλλογές και αλγόριθμους τύπου STL. Χρησιμοποιεί [IEqualityComparer](../iequalitycomparer/), εάν οριστεί. Εάν δεν οριστεί, χρησιμοποιεί τον τελεστή ==, [Object::Equals](../../system/object/equals/) ή T::Equals, ανάλογα με το ποιο είναι διαθέσιμο.

```cpp
template<class T>class EqualityComparerAdapter
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος που συγκρίνεται. |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  [EqualityComparerAdapter](./equalitycompareradapter/)() | Δημιουργεί προσαρμογέα χωρίς χρήση συγκριτή. |
|  [EqualityComparerAdapter](./equalitycompareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Δημιουργεί προσαρμογέα με τον δεδομένο συγκριτή. |
| **bool** [operator()](./operator_call/)(const T\&, const T\&) const | Συγκρίνει δύο αντικείμενα. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Ορίζει τον συγκριτή. |

## Δείτε επίσης

* Χώρος ονομάτων [System::Collections::Generic](../)
* Βιβλιοθήκη [Aspose.Slides](../../)