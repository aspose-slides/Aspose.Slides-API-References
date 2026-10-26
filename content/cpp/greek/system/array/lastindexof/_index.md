---
title: LastIndexOf()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει το δείκτη της τελευταίας εμφάνισης του καθορισμένου στοιχείου σε ένα εύρος στοιχείων του πίνακα που ορίζεται από τον αρχικό δείκτη και τον αριθμό των στοιχείων στο εύρος.
type: docs
weight: 703
url: /el/system/array/lastindexof/
---
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) μέθοδος

Καθορίζει το δείκτη της τελευταίας εμφάνισης του καθορισμένου στοιχείου σε ένα εύρος στοιχείων του πίνακα που ορίζεται από τον αρχικό δείκτη και τον αριθμό των στοιχείων στο εύρος.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| ArrayType | Τύπος των στοιχείων στον πίνακα-στόχο |
| ValueType | τύπος του στοιχείου που θα αναζητηθεί στον πίνακα |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) για την αναζήτηση του καθορισμένου στοιχείου σε |
| value | const [ValueType](../valuetype/)\& | Δείκτης του στοιχείου του οποίου πρέπει να προσδιοριστεί |
| startIndex | int | Δείκτης από τον οποίο ξεκινά η αναζήτηση |
| count | int | Αριθμός των στοιχείων του εύρους στα οποία γίνεται η αναζήτηση |

### Τιμή επιστροφής

Δείκτης της τελευταίας εμφάνισης του καθορισμένου στοιχείου εάν βρεθεί, διαφορετικά -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) μέθοδος

Καθορίζει το δείκτη της τελευταίας εμφάνισης του καθορισμένου στοιχείου στο πίνακα ξεκινώντας από τον καθορισμένο δείκτη.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value, int startIndex)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| ArrayType | Τύπος των στοιχείων στον πίνακα-στόχο |
| ValueType | τύπος του στοιχείου που θα αναζητηθεί στον πίνακα |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) για την αναζήτηση του καθορισμένου στοιχείου σε |
| value | const [ValueType](../valuetype/)\& | Δείκτης του στοιχείου του οποίου πρέπει να προσδιοριστεί |
| startIndex | int | Δείκτης από τον οποίο ξεκινά η αναζήτηση |

### Τιμή επιστροφής

Δείκτης της τελευταίας εμφάνισης του καθορισμένου στοιχείου εάν βρεθεί, διαφορετικά -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) μέθοδος

Καθορίζει το δείκτη της τελευταίας εμφάνισης του καθορισμένου στοιχείου στο πίνακα.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| ArrayType | Τύπος των στοιχείων στον πίνακα-στόχο |
| ValueType | τύπος του στοιχείου που θα αναζητηθεί στον πίνακα |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) για την αναζήτηση του καθορισμένου στοιχείου σε |
| value | const [ValueType](../valuetype/)\& | Δείκτης του στοιχείου του οποίου πρέπει να προσδιοριστεί |

### Τιμή επιστροφής

Δείκτης της τελευταίας εμφάνισης του καθορισμένου στοιχείου εάν βρεθεί, διαφορετικά -1

## Δείτε επίσης

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)