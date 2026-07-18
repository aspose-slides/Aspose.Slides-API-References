---
title: Enum
second_title: Aspose.Slides για C++ Αναφορά API
description: Παρέχει μεθόδους που εκτελούν κάποιες λειτουργίες σε τιμές τύπου enum. Αυτός είναι ένας στατικός τύπος χωρίς υπηρεσίες στιγμιότυπου. Δεν πρέπει ποτέ να δημιουργείτε στιγμιότυπα του με κανέναν τρόπο.
type: docs
weight: 1561
url: /el/system/enum/
---
## Δομή Enum

Παρέχει μεθόδους που εκτελούν κάποιες λειτουργίες στις τιμές τύπου enum. Αυτός είναι ένας στατικός τύπος χωρίς υπηρεσίες στιγμιότυπου. Δεν πρέπει ποτέ να δημιουργείτε στιγμιότυπα του με κανέναν τρόπο.

```cpp
template<class E,class Guard>class Enum
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| E | Ο τύπος του enum των τιμών του οποίου διαχειρίζεται η κλάση |
| Guard | Παράμετρος τύπου υπηρεσίας που έχει σκοπό να διασφαλίσει ότι το **E** είναι επαναλήψιμος τύπος |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| static int [Compare](./compare/)(E, T) | Εκτελεί την αριθμητική σύγκριση των τιμών των καθορισμένων σταθερών της αρίθμησης. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetDescription](./getdescription/)(T) | Επιστρέφει το όνομα της σταθεράς της αρίθμησης που έχει την καθορισμένη τιμή. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetName](./getname/)(T) | Επιστρέφει το όνομα της σταθεράς της αρίθμησης που έχει την καθορισμένη τιμή. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() | Επιστρέφει έναν πίνακα που περιέχει τα ονόματα όλων των μελών της αρίθμησης **E**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() | Επιστρέφει τον υποκείμενο τύπο της αρίθμησης. |
| static [ArrayPtr](../arrayptr/)\<E\> [GetValues](./getvalues/)() | Επιστρέφει έναν πίνακα που περιέχει όλα τα μέλη της αρίθμησης **E**. |
| static **bool** [HasFlag](./hasflag/)(E, E) | Καθορίζει εάν τα καθορισμένα bit είναι ορισμένα σε μια δυαδική αναπαράσταση της καθορισμένης τιμής enum. |
| static **bool** [IsDefined](./isdefined/)(E) | Καθορίζει εάν η καθορισμένη τιμή είναι μέλος του τύπου αρίθμησης **E**. |
| static std::enable_if\<std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, **bool**\>::type [IsDefined](./isdefined/)(T) | Καθορίζει εάν η καθορισμένη τιμή είναι μέλος του τύπου αρίθμησης **T**. |
| static **bool** [IsDefined](./isdefined/)(const [String](../string/)\&) | Καθορίζει εάν η τιμή με το καθορισμένο όνομα είναι ανάμεσα στα μέλη του enum **E**. |
| static E [Parse](./parse/)(const [String](../string/)\&, **bool**) | Μετατρέπει τη καθορισμένη συμβολοσειρά σε αντίστοιχη σταθερά enum. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, E\&) | Προσπαθεί να μετατρέψει τη καθορισμένη συμβολοσειρά σε αντίστοιχη σταθερά enum. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**, E\&) | Προσπαθεί να μετατρέψει τη καθορισμένη συμβολοσειρά σε αντίστοιχη σταθερά enum. |

## Ορισμοί τύπων

| Ορισμός τύπου | Περιγραφή |
| --- | --- |
| [UnderlyingType](./underlyingtype/) | Ψευδώνυμο για τον υποκείμενο τύπο του enum. |

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)