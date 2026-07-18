---
title: "System::BoxedValueDetail"
second_title: Αναφορά API του Aspose.Slides για C++
description: 
type: docs
weight: 287
url: /el/system.boxedvaluedetail/
---
## Κλάσεις

| Κλάση | Περιγραφή |
| --- | --- |
| [Comparable](./comparable/) | Απλή υλοποίηση του IComparable<> |
| [NonComparable](./noncomparable/) | Ψευδοβάση τύπο για συσκευασμένους τύπους που δεν υλοποιούν το IComparable<> |
## Δομές

| Δομή | Περιγραφή |
| --- | --- |
| [ImplementsInterface](./implementsinterface/) | Πρότυπο πρόβλεψης που ελέγχει αν το συσκευασμένο αντικείμενο πρέπει να υλοποιήσει τη δοσμένη διεπαφή από μόνο του. |
| [ImplementsInterface< String, IComparable< String > >](./implementsinterface_tmpl_string__icomparable_tmpl_string__end_tmpl__end_tmpl/) | [String](../system/string/) implements [IComparable](../system/icomparable/). |
| [ImplementsInterface< T, IComparable< T > >](./implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/) | Πρότυπο πρόβλεψης που ελέγχει αν το συσκευασμένο αντικείμενο πρέπει να υλοποιήσει τη διεπαφή [IComparable](../system/icomparable/) από μόνο του. |
## Συναρτήσεις

| Συνάρτηση | Περιγραφή |
| --- | --- |
| std::enable_if\<detail::has_operator_equal\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | Καθορίζει την ισότητα της συγκεκριμένης τιμής χρησιμοποιώντας [operator==()](../system/operator_equal_equal/). |
| std::enable_if\<detail::has_only_method_equals\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | Καθορίζει την ισότητα της συγκεκριμένης τιμής χρησιμοποιώντας τη μέθοδο [System::Object::Equals()](../system/object/equals/). |
| **bool** [Equals< float >](./equals_less_float__greater/)(**float**, **float**) | Συγκρίνει δύο τιμές κινητής υποδιαστολής μονής ακρίβειας. |
| **bool** [Equals< double >](./equals_less_double__greater/)(**double**, **double**) | Συγκρίνει δύο τιμές κινητής υποδιαστολής διπλής ακρίβειας. |