---
title: EqualityComparerHashAdapter
second_title: Aspose.Slides για την αναφορά API C++
description: Προσαρμοστής για τη χρήση του IEqualityComparer για κατακερματισμό. Χρησιμοποιεί το αντικείμενο συγκριτή, εάν έχει οριστεί· διαφορετικά, χρησιμοποιεί τη διαθέσιμη μέθοδο κατακερματισμού που επιλέγεται με τη δομή DictionaryHashSelector.
type: docs
weight: 677
url: /el/system.collections.generic/equalitycomparerhashadapter/
---
## EqualityComparerHashAdapter struct

Προσαρμοστής για τη χρήση του [IEqualityComparer](../iequalitycomparer/) για δημιουργία κατακερματισμού. Χρησιμοποιεί το αντικείμενο συγκριτή, εάν έχει οριστεί· διαφορετικά, χρησιμοποιεί τη διαθέσιμη μέθοδο κατακερματισμού που επιλέχθηκε χρησιμοποιώντας τη δομή [DictionaryHashSelector](../dictionaryhashselector/) struct.

```cpp
template<typename T>class EqualityComparerHashAdapter
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Hashed | τύπος. |

## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)() | Δημιουργεί προσαρμοστή χωρίς συγκριτή προς χρήση. |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Δημιουργεί προσαρμοστή με τον δεδομένο συγκριτή προς χρήση. |
| std::size_t [operator()](./operator_call/)(const T\&) const | Υπολογίζει την τιμή κατακερματισμού. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Ορίζει τον συγκριτή προς χρήση. |

## Δείτε επίσης

* Χώρος ονομάτων [System::Collections::Generic](../)
* Βιβλιοθήκη [Aspose.Slides](../../)