---
title: StaticCastArray()
second_title: Aspose.Slides για την Αναφορά API C++
description: Εκτελεί μετατροπή των στοιχείων του καθορισμένου πίνακα σε διαφορετικό τύπο. Υπερισχύει για περιπτώσεις όπου το From είναι SmartPtr obj.
type: docs
weight: 2939
url: /el/system/staticcastarray/
---
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) function

Εκτελεί μετατροπή των στοιχείων του καθορισμένου πίνακα σε διαφορετικό τύπο. Υπερισχύει για περιπτώσεις όπου το From είναι [SmartPtr](../smartptr/) αντικείμενο.

```cpp
template<typename To,typename From> std::enable_if_t<System::IsSmartPtr<From>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```

### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| To | Ο τύπος στον οποίο θα μετατραπούν τα στοιχεία του καθορισμένου πίνακα |
| From | Ο τύπος των στοιχείων του πίνακα από τα οποία θα γίνει η μετατροπή |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | Κοινή αναφορά σε πίνακα που περιέχει τα στοιχεία προς μετατροπή |

### Τιμή επιστροφής

Ένας δείκτης σε νέο πίνακα που περιέχει στοιχεία τύπου **To** ισοδύναμα με τα στοιχεία του **from**

Παρωχημένο
:   Προστέθηκε για συμβατότητα με παλαιότερες εκδόσεις. Χρησιμοποιήστε το ExplicitCast.

## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) function

Εκτελεί μετατροπή των στοιχείων του καθορισμένου πίνακα σε διαφορετικό τύπο. Υπερισχύει για περιπτώσεις όπου το From είναι Boxable και το To είναι [Object](../object/)[].

```cpp
template<typename To,typename From> std::enable_if_t<!System::IsSmartPtr<From>::value &&System::IsBoxable<From>::value &&std::is_same<To, System::SharedPtr<Object>>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```

### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| To | Ο τύπος στον οποίο θα μετατραπούν τα στοιχεία του καθορισμένου πίνακα |
| From | Ο τύπος των στοιχείων του πίνακα από τα οποία θα γίνει η μετατροπή |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | Κοινή αναφορά σε πίνακα που περιέχει τα στοιχεία προς μετατροπή |

### Τιμή επιστροφής

Ένας δείκτης σε νέο πίνακα που περιέχει στοιχεία τύπου **To** ισοδύναμα με τα στοιχεία του **from**

Παρωχημένο
:   Προστέθηκε για συμβατότητα με παλαιότερες εκδόσεις. Χρησιμοποιήστε το ExplicitCast.

## Δείτε επίσης

* Typedef [SharedPtr](../sharedptr/)
* Κλάση [Array](../array/)
* Κλάση [Object](../object/)
* Struct [IsSmartPtr](../issmartptr/)
* Struct [IsBoxable](../isboxable/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)