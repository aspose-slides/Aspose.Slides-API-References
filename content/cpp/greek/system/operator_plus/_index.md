---
title: operator+()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιστρέφει μια νέα παρουσία της κλάσης Decimal που αντιπροσωπεύει μια τιμή η οποία είναι το άθροισμα της καθορισμένης τιμής και της τιμής που αναπαριστά το καθορισμένο αντικείμενο Decimal.
type: docs
weight: 2159
url: /el/system/operator_plus/
---
## System::operator+(const T\&, const Decimal\&) συνάρτηση


Επιστρέφει μια νέα παρουσία της κλάσης [Decimal](../decimal/) που αντιπροσωπεύει μια τιμή που είναι το άθροισμα της καθορισμένης τιμής και της τιμής που αναπαριστά το καθορισμένο αντικείμενο [Decimal](../decimal/).

```cpp
template<typename T,typename _> Decimal System::operator+(const T &x, const Decimal &d)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | const T\& | The first summand |
| d | const [Decimal](../decimal/)\& | The constant reference to the [Decimal](../decimal/) object representing the second summand |

### Τιμή Επιστροφής

Μια νέα παρουσία της κλάσης [Decimal](../decimal/) που αντιπροσωπεύει μια τιμή που είναι το άθροισμα του **x** και της τιμής που αναπαριστά το **d**.

## System::operator+(MulticastDelegate\<T\>, MulticastDelegate\<T\>) συνάρτηση


Συνδέει όλες τις κλήσεις επιστροφής (callbacks) από τον δεξιό εκχωρητή στο τέλος της λίστας κλήσεων επιστροφής του αριστερού εκχωρητή.

```cpp
template<typename T> MulticastDelegate<T> System::operator+(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | The delegate to which callbacks are added. |
| rhv | MulticastDelegate\<T\> | The delegate whose callbacks are being added. |

### Τιμή Επιστροφής

Επιστρέφει έναν εκχωρητή που περιέχει τις κλήσεις επιστροφής της αριστερής τιμής και, στη συνέχεια, τις κλήσεις του δεξιού.

## System::operator+(const T1\&, const Nullable\<T2\>\&) συνάρτηση


Αθροίζει τιμές μη-μηδενικές και μηδενικές.

```cpp
template<typename T1,typename T2,typename> auto System::operator+(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some+other.get_Value())>
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Left operand type. |
| T2 | Right operand type. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| some | const T1\& | Left operand. |
| other | const [Nullable](../nullable/)\<T2\>\& | Right operand. |

### Τιμή Επιστροφής

Αποτέλεσμα άθροισης.

## System::operator+(T\&, const String\&) συνάρτηση


[String](../string/) σύνθεση.

```cpp
template<typename T> std::enable_if<IsStringLiteral<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | [String](../string/) τύπος literal. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | T\& | Λεκτικό για σύνθεση με τη συμβολοσειρά. |
| right | const [String](../string/)\& | [String](../string/) για σύνθεση. |

### Τιμή Επιστροφής

Συγκεντρωμένη συμβολοσειρά.

## System::operator+(T\&, const String\&) συνάρτηση


[String](../string/) σύνθεση.

```cpp
template<typename T> std::enable_if<IsStringPointer<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | [String](../string/) τύπος δείκτη. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | T\& | [String](../string/) δείκτης για σύνθεση με τη συμβολοσειρά. |
| right | const [String](../string/)\& | [String](../string/) για σύνθεση. |

### Τιμή Επιστροφής

Συγκεντρωμένη συμβολοσειρά.

## System::operator+(const char_t, const String\&) συνάρτηση


[String](../string/) σύνθεση.

```cpp
String System::operator+(const char_t left, const String &right)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | const char_t | Χαρακτήρας για σύνθεση με τη συμβολοσειρά. |
| right | const [String](../string/)\& | [String](../string/) για σύνθεση. |

### Τιμή Επιστροφής

Συγκεντρωμένη συμβολοσειρά.

## Δείτε επίσης

* Κλάση [Decimal](../decimal/)
* Κλάση [Nullable](../nullable/)
* Κλάση [String](../string/)
* Δομή [IsStringLiteral](../isstringliteral/)
* Δομή [IsStringPointer](../isstringpointer/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)