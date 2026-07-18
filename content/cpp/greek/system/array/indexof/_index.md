---
title: IndexOf()
second_title: Αναφορά API του Aspose.Slides για C++
description: Καθορίζει τον δείκτη της πρώτης εμφάνισης του καθορισμένου στοιχείου στον πίνακα.
type: docs
weight: 131
url: /el/system/array/indexof/
---
## Array::IndexOf(const T\&) const μέθοδος

Καθορίζει το δείκτη της πρώτης εμφάνισης του καθορισμένου στοιχείου στον πίνακα.

```cpp
virtual int System::Array<T>::IndexOf(const T &item) const override
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | const T\& | Δείκτης του στοιχείου που πρέπει να προσδιοριστεί |

### Τιμή επιστροφής

Δείκτης της πρώτης εμφάνισης του καθορισμένου στοιχείου εάν το στοιχείο βρεθεί, διαφορετικά -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) μέθοδος

Καθορίζει το δείκτη της πρώτης εμφάνισης του καθορισμένου στοιχείου στον πίνακα.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| ArrayType | Τύπος των στοιχείων στον στοχευόμενο πίνακα |
| ValueType | Τύπος του στοιχείου που θα αναζητηθεί στον πίνακα |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) για αναζήτηση του καθορισμένου στοιχείου σε |
| value | const [ValueType](../valuetype/)\& | Δείκτης του στοιχείου που πρέπει να προσδιοριστεί |

### Τιμή επιστροφής

Δείκτης της πρώτης εμφάνισης του καθορισμένου στοιχείου εάν το στοιχείο βρεθεί, διαφορετικά -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) μέθοδος

Καθορίζει το δείκτη της πρώτης εμφάνισης του καθορισμένου στοιχείου στον πίνακα ξεκινώντας από το καθορισμένο δείκτη.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| ArrayType | Τύπος των στοιχείων στον στοχευόμενο πίνακα |
| ValueType | Τύπος του στοιχείου που θα αναζητηθεί στον πίνακα |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) για αναζήτηση του καθορισμένου στοιχείου σε |
| value | const [ValueType](../valuetype/)\& | Δείκτης του στοιχείου που πρέπει να προσδιοριστεί |
| startIndex | int | Δείκτης από τον οποίο ξεκινά η αναζήτηση |

### Τιμή επιστροφής

Δείκτης της πρώτης εμφάνισης του καθορισμένου στοιχείου εάν το στοιχείο βρεθεί, διαφορετικά -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) μέθοδος

Καθορίζει το δείκτη της πρώτης εμφάνισης του καθορισμένου στοιχείου σε ένα εύρος στοιχείων του πίνακα που ορίζεται από τον αρχικό δείκτη και τον αριθμό των στοιχείων στο εύρος.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| ArrayType | Τύπος των στοιχείων στον στοχευόμενο πίνακα |
| ValueType | Τύπος του στοιχείου που θα αναζητηθεί στον πίνακα |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) για αναζήτηση του καθορισμένου στοιχείου σε |
| value | const [ValueType](../valuetype/)\& | Δείκτης του στοιχείου που πρέπει να προσδιοριστεί |
| startIndex | int | Δείκτης από τον οποίο ξεκινά η αναζήτηση |
| count | int | Αριθμός στοιχείων της περιοχής για αναζήτηση |

### Τιμή επιστροφής

Δείκτης της πρώτης εμφάνισης του καθορισμένου στοιχείου εάν το στοιχείο βρεθεί, διαφορετικά -1

## Δείτε επίσης

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Τάξη [Array](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)