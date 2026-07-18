---
title: DynamicCastArray()
second_title: Aspose.Slides για την Αναφορά API του C++
description: Πραγματοποιεί μετατροπή των στοιχείων του καθορισμένου πίνακα σε διαφορετικό τύπο.
type: docs
weight: 2952
url: /el/system/dynamiccastarray/
---
## System::DynamicCastArray(const SharedPtr<Array<From>>&) συνάρτηση

Εκτελεί μετατροπή των στοιχείων του καθορισμένου πίνακα σε διαφορετικό τύπο.

```cpp
template<class To,class From> SharedPtr<Array<To>> System::DynamicCastArray(const SharedPtr<Array<From>> &from)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| To | Ο τύπος στον οποίο θα μετατραπούν τα στοιχεία του καθορισμένου πίνακα |
| From | Ο τύπος των στοιχείων των οποίων θα μετατραπούν |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| from | const [SharedPtr](../sharedptr/)\<[Array](../array/)\<From\>\>\& | Κοινός δείκτης προς τον πίνακα που περιέχει τα στοιχεία που θα μετατραπούν |

### Τιμή επιστροφής

Ένας δείκτης σε ένα νέο πίνακα που περιέχει στοιχεία τύπου **To** ισοδύναμα με τα στοιχεία του **from**

Παρωχημένο
:   Προστέθηκε για συμβατότητα με παλαιότερες εκδόσεις. Χρησιμοποιήστε το ExplicitCast αντί αυτού.

## Δείτε επίσης

* Typedef [SharedPtr](../sharedptr/)
* Κλάση [Array](../array/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)