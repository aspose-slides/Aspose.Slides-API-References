---
title: Array()
second_title: Αναφορά API Aspose.Slides για C++
description: Δημιουργεί έναν κενό πίνακα.
type: docs
weight: 1
url: /el/system/array/array/
---
## Array::Array() κατασκευαστής

Δημιουργεί έναν κενό πίνακα.

```cpp
System::Array<T>::Array()
```

## Array::Array(int, const T&) κατασκευαστής

Κατασκευαστής γεμίσματος.

```cpp
System::Array<T>::Array(int count, const T &init=T())
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| count | int | Αρχικό μέγεθος του πίνακα |
| init | const T\& | Η αρχική τιμή που χρησιμοποιείται για να γεμίσει ο πίνακας |

## Array::Array(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type, ValueType) κατασκευαστής

Κατασκευαστής γεμίσματος.

```cpp
template<typename ValueType> System::Array<T>::Array(typename std::enable_if<std::is_arithmetic<T>::value &&std::is_arithmetic<ValueType>::value &&std::is_convertible<ValueType, T>::value, int>::type count, ValueType init)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| ValueType | Τύπος αρχικής τιμής |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| count | typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](../valuetype/)\>::value\&&std::is_convertible\<[ValueType](../valuetype/), T\>::value, int\>::type | Αρχικό μέγεθος του πίνακα |
| init | [ValueType](../valuetype/) | Η αρχική τιμή που χρησιμοποιείται για να γεμίσει ο πίνακας |

## Array::Array(int, const T) κατασκευαστής

Κατασκευαστής γεμίσματος.

```cpp
System::Array<T>::Array(int count, const T inits[])
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| count | int | Αρχικό μέγεθος του πίνακα |
| inits | const T | Τιμές για να γεμίσει ο πίνακας |

## Array::Array(vector_t\&&) κατασκευαστής

Κατασκευαστής μετακίνησης.

```cpp
System::Array<T>::Array(vector_t &&value)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | **vector_t**\&& | std::vector, τα στοιχεία του των οποίων αποκτώνται από το πίνακα |

## Array::Array(const vector_t\&) κατασκευαστής

Κατασκευαστής αντιγραφής.

```cpp
System::Array<T>::Array(const vector_t &assgn)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| assgn | const **vector_t**\& | std::vector για αντιγραφή τιμών |

## Array::Array(const std::vector\<Q\>\&) κατασκευαστής

Δημιουργεί ένα αντικείμενο [Array](../) και το γεμίζει με τιμές που αντιγράφονται από ένα αντικείμενο std::vector του οποίου ο τύπος των τιμών είναι ο ίδιος με **T**, αλλά διαφορετικός από **UnderlyingType**.

```cpp
template<typename Q,typename> System::Array<T>::Array(const std::vector<Q> &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Q | Ο τύπος των στοιχείων του αντικειμένου std::vector από τα οποία θα αντιγραφούν τα στοιχεία |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const std::vector\<Q\>\& | std::vector για αντιγραφή των τιμών |

## Array::Array(std::vector\<Q\>\&&) κατασκευαστής

Δημιουργεί ένα αντικείμενο [Array](../) και το γεμίζει με τιμές που μετακινούνται από ένα αντικείμενο std::vector του οποίου ο τύπος των τιμών είναι ο ίδιος με **T**, αλλά διαφορετικός από **UnderlyingType**.

```cpp
template<typename Q,typename> System::Array<T>::Array(std::vector<Q> &&value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Q | Ο τύπος των στοιχείων του αντικειμένου std::vector από τα οποία θα μετακινηθούν τα στοιχεία |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | std::vector\<Q\>\&& | std::vector για αντιγραφή των τιμών |

## Array::Array(std::initializer_list\<UnderlyingType\>) κατασκευαστής

Δημιουργεί ένα αντικείμενο [Array](../) και το γεμίζει με τιμές από την καθορισμένη λίστα εκκίνησης που περιέχει στοιχεία τύπου **UnderlyingType**.

```cpp
System::Array<T>::Array(std::initializer_list<UnderlyingType> init)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| init | std::initializer_list\<[UnderlyingType](../underlyingtype/)\> | Λίστα εκκίνησης που περιέχει στοιχεία για να γεμίσει ο πίνακας |

## Array::Array(const std::array\<UnderlyingType, InitArraySize\>\&) κατασκευαστής

Δημιουργεί ένα αντικείμενο [Array](../) και το γεμίζει με τιμές από τον καθορισμένο πίνακα που περιέχει στοιχεία τύπου **UnderlyingType**.

```cpp
template<std::size_t> System::Array<T>::Array(const std::array<UnderlyingType, InitArraySize> &init)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| InitArraySize | Αριθμός στοιχείων του πίνακα **init**. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| init | const std::array\<[UnderlyingType](../underlyingtype/), InitArraySize\>\& | [Array](../) για αντιγραφή στον πίνακα που κατασκευάζεται. |

## Array::Array(std::initializer_list\<bool\>, int) κατασκευαστής

Δημιουργεί ένα αντικείμενο [Array](../) και το γεμίζει με τιμές από την καθορισμένη λίστα εκκίνησης που περιέχει στοιχεία τύπου bool.

```cpp
System::Array<T>::Array(std::initializer_list<bool> init, int=0)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| init | std::initializer_list\<**bool**\> | Λίστα εκκίνησης που περιέχει στοιχεία για να γεμίσει ο πίνακας |

## Δείτε επίσης

* Typedef [ValueType](../valuetype/)
* Typedef [UnderlyingType](../underlyingtype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)