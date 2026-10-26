---
title: operator==()
second_title: Αναφορά API του Aspose.Slides για C++
description: Συγκρίνει δύο ζεύγη κλειδιού-τιμής χρησιμοποιώντας τη σημασιολογία 'equals'. Χρησιμοποιεί τον τελεστή == ή τη μέθοδο EqualsTo για και τα κλειδιά και τις τιμές, όποια είναι ορισμένη.
type: docs
weight: 690
url: /el/system.collections.generic/operator_equal_equal/
---
## System::Collections::Generic::operator==(const KeyValuePair\<TKey, TValue\>\&, const KeyValuePair\<TKey, TValue\>\&) function

Συγκρίνει δύο ζεύγη κλειδιού-τιμής χρησιμοποιώντας τη σημασιολογία «equals». Χρησιμοποιεί τον τελεστή == ή τη μέθοδο EqualsTo για και τα κλειδιά και τις τιμές, όποια είναι ορισμένη.

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator==(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TKey | Τύπος κλειδιού. |
| TValue | Τύπος τιμής. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | Τελεστής αριστερού όρου. |
| right | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | Τελεστής δεξιού όρου. |

### Τιμή Επιστροφής

Αληθές εάν και τα κλειδιά και οι τιμές ταιριάζουν, αλλιώς ψευδές.

## See Also

* Κλάση [KeyValuePair](../keyvaluepair/)
* Χώρος ονομάτων [System::Collections::Generic](../)
* Βιβλιοθήκη [Aspose.Slides](../../)