---
title: HashSet()
second_title: Αναφορά API του Aspose.Slides για C++
description: Πληροφορίες RTTI.
type: docs
weight: 1
url: /el/system.collections.generic/hashset/hashset/
---
## HashSet::HashSet() κατασκευαστής

Πληροφορίες RTTI.

```cpp
System::Collections::Generic::HashSet<T>::HashSet()
```

## Σχόλια

Δημιουργεί κενό σύνολο. 
## HashSet::HashSet(int) κατασκευαστής

Δημιουργεί κενό σύνολο με καθορισμένη χωρητικότητα.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(int capacity)
```

## HashSet::HashSet(const SharedPtr\<IEqualityComparer\<T\>\>\&) κατασκευαστής

Δημιουργεί κενό σύνολο που χρησιμοποιεί το καθορισμένο συγκριτικό ισότητας.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEqualityComparer<T>> &comparer)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<T\>\>\& | [Comparer](../../comparer/) object to associate with hashset. |

## HashSet::HashSet(const SharedPtr\<IEnumerable\<T\>\>\&) κατασκευαστής

Δημιουργεί hashset βάσει επαναλήψιμων τιμών.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEnumerable<T>> &items)
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [HashSet](../)
* Κλάση [IEqualityComparer](../../iequalitycomparer/)
* Κλάση [IEnumerable](../../ienumerable/)
* Χώρος ονομάτων [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)