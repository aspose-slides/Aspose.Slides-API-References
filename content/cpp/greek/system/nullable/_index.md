---
title: Nullable
second_title: Aspose.Slides για C++ - Αναφορά API
description: Δήλωση προώθησης.
type: docs
weight: 1093
url: /el/system/nullable/
---
## Κλάση Nullable

Forward declaration.

```cpp
template<typename T>class Nullable
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο υποκείμενος τύπος τιμής που επεκτείνεται από την κλάση [Nullable](./) |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| std::enable_if\<[IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [Equals](./equals/)(const T1\&) const | Καθορίζει αν η τιμή που εκπροσωπείται από το τρέχον αντικείμενο είναι ίση με την τιμή που εκπροσωπείται από το συγκεκριμένο αντικείμενο [Nullable](./). |
| **bool** [get_HasValue](./get_hasvalue/)() const | Καθορίζει αν το τρέχον αντικείμενο εκπροσωπεί οποιαδήποτε τιμή. |
| T [get_Value](./get_value/)() const | Επιστρέφει ένα αντίγραφο της τιμής που εκπροσωπείται από το τρέχον αντικείμενο. |
| int [GetHashCode](./gethashcode/)() const | Επιστρέφει έναν κώδικα κατατεματισμού (hash) για το τρέχον αντικείμενο. |
| T [GetValueOrDefault](./getvalueordefault/)(T) | Επιστρέφει την τιμή που εκπροσωπείται από το τρέχον αντικείμενο ή την καθορισμένη τιμή εάν η τιμή που εκπροσωπείται από το τρέχον αντικείμενο είναι null. |
| T [GetValueOrDefault](./getvalueordefault/)() |  |
| **bool** [IsNull](./isnull/)() const | Καθορίζει αν το τρέχον αντικείμενο εκπροσωπεί μια τιμή null. |
| [Nullable](./nullable/)() | Δημιουργεί ένα στιγμιότυπο που εκπροσωπεί τιμή null. |
| [Nullable](./nullable/)(std::nullptr_t) | Δημιουργεί ένα στιγμιότυπο που εκπροσωπεί null. |
| [Nullable](./nullable/)(const T1\&) | Δημιουργεί ένα στιγμιότυπο της κλάσης [Nullable](./) που εκπροσωπεί την καθορισμένη τιμή μετατρεπόμενη (εάν είναι απαραίτητο) στον τύπο υποκείμενης τιμής T. |
| [Nullable](./nullable/)(const [Nullable](./)\<T1\>\&) | Δημιουργεί ένα στιγμιότυπο που εκπροσωπεί μια τιμή που εκπροσωπείται από το συγκεκριμένο αντικείμενο [Nullable](./). Το καθορισμένο nullable αντικείμενο ενδέχεται να εκπροσωπεί τιμή διαφορετικού τύπου από τον υποκείμενο τύπο του κατασκευασμένου στιγμιότυπου, οπότε η τιμή μετατρέπεται σε τύπο T. |
| **bool** [NullableBoolHelper](./nullableboolhelper/)(const T1\&, const std::function\<**bool**()>\&, **bool**) const | Βοηθητική συνάρτηση για να ελεγχθεί αν αυτό και **other** δεν είναι null και να κληθεί μια lambda εάν είναι. Χρησιμοποιείται στις υλοποιήσεις. |
| [operator const T &](./operator_const_t__and/)() const | Επιστρέφει μια σταθερή αναφορά στην τιμή που εκπροσωπείται από το τρέχον αντικείμενο. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Καθορίζει αν η τιμή που εκπροσωπείται από το τρέχον αντικείμενο δεν είναι null. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const T1\&) const | Καθορίζει αν η τιμή που εκπροσωπείται από το τρέχον αντικείμενο δεν είναι ίση με την καθορισμένη τιμή. |
| **bool** [operator!=](./operator_not_equal/)(const [Nullable](./)\<T1\>\&) const | Καθορίζει αν η τιμή που εκπροσωπείται από το τρέχον αντικείμενο δεν είναι ίση με την τιμή που εκπροσωπείται από το συγκεκριμένο αντικείμενο [Nullable](./). |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator&=](./operator_and_equal/)(**bool**) | Εφαρμόζει [operator&=()](./operator_and_equal/) στην τιμή που εκπροσωπείται από το τρέχον αντικείμενο χρησιμοποιώντας την καθορισμένη τιμή ως δεξιό όρισμα. |
| [Nullable](./)\<T\> [operator+](./operator_plus/)(std::nullptr_t) const | Επιστρέφει ένα προεπιλεγμένο στιγμιότυπο της κλάσης Nullable<T>. |
| auto [operator+](./operator_plus/)(const T1\&) const | Προσθέτει nullable και non-nullable τιμές. |
| auto [operator+](./operator_plus/)(const [Nullable](./)\<T1\>\&) const | Προσθέτει nullable τιμές. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(std::nullptr_t) | Επαναφέρει το τρέχον αντικείμενο ώστε να εκπροσωπεί τιμή null. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator+=](./operator_plus_equal/)(const T1\&) | Εφαρμόζει [operator+=()](./operator_plus_equal/) στην τιμή που εκπροσωπείται από το τρέχον αντικείμενο χρησιμοποιώντας την καθορισμένη τιμή ως δεξιό όρισμα. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(const [Nullable](./)\<T1\>\&) | Εφαρμόζει [operator+=()](./operator_plus_equal/) στην τιμή που εκπροσωπείται από το τρέχον αντικείμενο χρησιμοποιώντας την τιμή που εκπροσωπείται από το συγκεκριμένο αντικείμενο [Nullable](./) ως δεξιό όρισμα. |
| [Nullable](./)\<T\> [operator-](./operator_minus/)(T1) const | Αφαιρεί nullable και τιμές που δείχνουν στο null. |
| auto [operator-](./operator_minus/)(const T1\&) const | Αφαιρεί nullable και non-nullable τιμές. |
| auto [operator-](./operator_minus/)(const [Nullable](./)\<T1\>\&) const | Αφαιρεί nullable τιμές. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(T1) | Επιστρέφει ένα στιγμιότυπο της κλάσης [Nullable](./) που εκπροσωπεί τιμή null. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator-=](./operator_minus_equal/)(const T1\&) | Εφαρμόζει [operator-=()](./operator_minus_equal/) στην τιμή που εκπροσωπείται από το τρέχον αντικείμενο χρησιμοποιώντας την καθορισμένη τιμή ως δεξιό όρισμα. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(const [Nullable](./)\<T1\>\&) | Εφαρμόζει [operator-=()](./operator_minus_equal/) στην τιμή που εκπροσωπείται από το τρέχον αντικείμενο χρησιμοποιώντας την τιμή που εκπροσωπείται από το συγκεκριμένο αντικείμενο [Nullable](./) ως δεξιό όρισμα. |
| **bool** [operator<](./operator_less/)(std::nullptr_t) const | Πάντα επιστρέφει false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<](./operator_less/)(const T1\&) const | Καθορίζει αν η τιμή του τρέχοντος αντικειμένου είναι μικρότερη από την καθορισμένη τιμή εφαρμόζοντας [operator<()](./operator_less/) σε αυτές τις τιμές. |
| **bool** [operator<](./operator_less/)(const [Nullable](./)\<T1\>\&) const | Καθορίζει αν η τιμή του τρέχοντος αντικειμένου είναι μικρότερη από την τιμή του συγκεκριμένου αντικειμένου [Nullable](./) εφαρμόζοντας [operator<()](./operator_less/) σε αυτές τις τιμές. |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const | Πάντα επιστρέφει false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<=](./operator_less_equal/)(const T1\&) const | Καθορίζει αν η τιμή του τρέχοντος αντικειμένου είναι μικρότερη ή ίση με την καθορισμένη τιμή εφαρμόζοντας [operator<=()](./operator_less_equal/) σε αυτές τις τιμές. |
| **bool** [operator<=](./operator_less_equal/)(const [Nullable](./)\<T1\>\&) const | Καθορίζει αν η τιμή του τρέχοντος αντικειμένου είναι μικρότερη ή ίση με την τιμή του συγκεκριμένου αντικειμένου [Nullable](./) εφαρμόζοντας [operator<=()](./operator_less_equal/) σε αυτές τις τιμές. |
| [Nullable](./)\<T\> [operator=](./operator_equal/)(std::nullptr_t) | Αντιστοιχίζει null στο τρέχον αντικείμενο. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value\&&\!std::is_null_pointer\<T1\>::value, [Nullable](./)\<T\>\&\>::type [operator=](./operator_equal/)(const T1\&) | Αντικαθιστά την τρέχουσα τιμή που εκπροσωπείται από το αντικείμενο με την καθορισμένη. |
| [Nullable](./)\<T\>\& [operator=](./operator_equal/)(const [Nullable](./)\<T1\>\&) | Αντικαθιστά την τρέχουσα τιμή που εκπροσωπείται από το αντικείμενο με την καθορισμένη. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Καθορίζει αν η τιμή που εκπροσωπείται από το τρέχον αντικείμενο είναι null. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const T1\&) const | Καθορίζει αν η τιμή του τρέχοντος αντικειμένου είναι ίση με την καθορισμένη τιμή. |
| **bool** [operator==](./operator_equal_equal/)(const [Nullable](./)\<T1\>\&) const | Καθορίζει αν η τιμή του τρέχοντος αντικειμένου είναι ίση με την τιμή του συγκεκριμένου αντικειμένου [Nullable](./). |
| **bool** [operator>](./operator_greater/)(std::nullptr_t) const | Πάντα επιστρέφει false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>](./operator_greater/)(const T1\&) const | Καθορίζει αν η τιμή του τρέχοντος αντικειμένου είναι μεγαλύτερη από την καθορισμένη τιμή εφαρμόζοντας [operator>()](./operator_greater/) σε αυτές τις τιμές. |
| **bool** [operator>](./operator_greater/)(const [Nullable](./)\<T1\>\&) const | Καθορίζει αν η τιμή του τρέχοντος αντικειμένου είναι μεγαλύτερη από την τιμή του συγκεκριμένου αντικειμένου [Nullable](./) εφαρμόζοντας [operator>()](./operator_greater/) σε αυτές τις τιμές. |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const | Πάντα επιστρέφει false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>=](./operator_greater_equal/)(const T1\&) const | Καθορίζει αν η τιμή του τρέχοντος αντικειμένου είναι μεγαλύτερη ή ίση με την τιμή του συγκεκριμένου αντικειμένου εφαρμόζοντας [operator>=()](./operator_greater_equal/) σε αυτές τις τιμές. |
| **bool** [operator>=](./operator_greater_equal/)(const [Nullable](./)\<T1\>\&) const | Καθορίζει αν η τιμή του τρέχοντος αντικειμένου είναι μεγαλύτερη ή ίση με την τιμή του συγκεκριμένου αντικειμένου [Nullable](./) εφαρμόζοντας [operator>=()](./operator_greater_equal/) σε αυτές τις τιμές. |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator|=](./operator_or_equal/)(**bool**) | Εφαρμόζει [operator|=()](./operator_or_equal/) στην τιμή που εκπροσωπείται από το τρέχον αντικείμενο χρησιμοποιώντας την καθορισμένη τιμή ως δεξιό όρισμα. |
| void [reset](./reset/)() | Ορίζει την τρέχουσα τιμή ως null. |
| void [set_Value](./set_value/)(const T\&) | Ορίζει μια νέα τιμή στο nullable αντικείμενο. |
| [String](../string/) [ToString](./tostring/)() const | Μετατρέπει την τιμή που εκπροσωπείται από το τρέχον αντικείμενο σε συμβολοσειρά. |

## Ορισμοί τύπου

| Ορισμός τύπου | Περιγραφή |
| --- | --- |
| [ValueType](./valuetype/) | Ένα ψευδώνυμο για τον τύπο της τιμής που εκπροσωπείται από αυτήν την κλάση. |

## Σχόλια

Αντιπροσωπεύει μια τιμή του συγκεκριμένου τύπου που μπορεί να ανατεθεί ως null. Αυτός ο τύπος θα πρέπει να εκχωρείται στη στοίβα και να περνιέται σε συναρτήσεις ως τιμή ή ως αναφορά. Ποτέ μην χρησιμοποιείτε την κλάση [System::SmartPtr](../smartptr/) για τη διαχείριση αντικειμένων αυτού του τύπου.

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)