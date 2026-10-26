---
title: operator-()
second_title: Aspose.Slides για C++ API Αναφορά
description: Υπολογίζει τον αριθμό των ημερών μεταξύ δύο ημερών της εβδομάδας.
type: docs
weight: 2146
url: /el/system/operator_minus/
---
## System::operator-(DayOfWeek, DayOfWeek) συνάρτηση

Υπολογίζει τον αριθμό των ημερών μεταξύ δύο ημερών της εβδομάδας.

```cpp
auto System::operator-(DayOfWeek a, DayOfWeek b)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | [DayOfWeek](../dayofweek/) | Το μειωτέο |
| b | [DayOfWeek](../dayofweek/) | Το αφαιρετέο |

### Τιμή Επιστροφής

Ο αριθμός των ημερών μεταξύ των εργάσιμων ημερών **a** και **b**; η τιμή επιστροφής είναι ένας αρνητικός αριθμός εάν *μεταβαίνει* μετά ****

## System::operator-(const T\&, const Decimal\&) συνάρτηση

Επιστρέφει ένα νέο αντικείμενο της κλάσης [Decimal](../decimal/) που αντιπροσωπεύει μια τιμή που είναι το αποτέλεσμα της αφαίρεσης της τιμής που αντιπροσωπεύεται από το καθορισμένο αντικείμενο [Decimal](../decimal/) από την καθορισμένη τιμή.

```cpp
template<typename T,typename _> Decimal System::operator-(const T &x, const Decimal &d)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | const T\& | Η τιμή από την οποία θα αφαιρεθεί |
| d | const [Decimal](../decimal/)\& | Το αντικείμενο [Decimal](../decimal/) που αντιπροσωπεύει την αφαιρούμενη τιμή |

### Τιμή Επιστροφής

Ένα νέο αντικείμενο της κλάσης [Decimal](../decimal/) που αντιπροσωπεύει μια τιμή που είναι το αποτέλεσμα της αφαίρεσης της τιμής που αντιπροσωπεύεται από το **d** από το **x**.

## System::operator-(MulticastDelegate\<T\>, MulticastDelegate\<T\>) συνάρτηση

Αποσυνδέει όλες τις κλήσεις-επιστροφές (callbacks) στο δεξιό delegate από το τέλος της λίστας κλήσεων-επιστροφών του αριστερού delegate.

```cpp
template<typename T> MulticastDelegate<T> System::operator-(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | Το delegate από το οποίο θα αφαιρεθούν οι κλήσεις-επιστροφές. |
| rhv | MulticastDelegate\<T\> | Το delegate του οποίου οι κλήσεις-επιστροφές θα αφαιρεθούν. |

### Τιμή Επιστροφής

Επιστρέφει ένα delegate που περιέχει τις κλήσεις-επιστροφές της αριστερής τιμής, αλλά χωρίς αυτές της δεξιάς τιμής.

## System::operator-(const T1\&, const Nullable\<T2\>\&) συνάρτηση

Αφαιρεί μη-μηδενικές (non-nullable) και μηδενικές (nullable) τιμές.

```cpp
template<typename T1,typename T2,typename> auto System::operator-(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some - other.get_Value())>
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Τύπος αριστερού τελεστή. |
| T2 | Τύπος δεξιού τελεστή. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| some | const T1\& | Αριστερός τελεστής. |
| other | const [Nullable](../nullable/)\<T2\>\& | Δεξιός τελεστής. |

### Τιμή Επιστροφής

Αποτέλεσμα αφαίρεσης.

## Δείτε επίσης

* Enum [DayOfWeek](../dayofweek/)
* Class [Decimal](../decimal/)
* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)