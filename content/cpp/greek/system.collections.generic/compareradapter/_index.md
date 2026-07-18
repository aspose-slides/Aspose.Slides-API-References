---
title: ComparerAdapter
second_title: Aspose.Slides για C++ Αναφορά API
description: Προσαρμογέας για χρήση του IComparer σε περιβάλλον STL. Χρησιμοποιεί το IComparer εάν έχει οριστεί· διαφορετικά, χρησιμοποιεί τον τελεστή < (εάν είναι διαθέσιμο) ή επιστρέφει false (εάν δεν είναι).
type: docs
weight: 638
url: /el/system.collections.generic/compareradapter/
---
## ComparerAdapter δομή


Προσαρμογέας για χρήση του [IComparer](../icomparer/) σε περιβάλλον STL. Χρησιμοποιεί το [IComparer](../icomparer/) εάν έχει οριστεί· διαφορετικά, χρησιμοποιεί τον τελεστή < (εάν είναι διαθέσιμος) ή επιστρέφει false (εάν δεν είναι).

```cpp
template<class T>class ComparerAdapter
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος που συγκρίνεται. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  [ComparerAdapter](./compareradapter/)() | Κατασκευάζει τον προσαρμογέα χωρίς διαθέσιμο συγκριτή. |
|  [ComparerAdapter](./compareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Κατασκευάζει τον προσαρμογέα. |
| std::enable_if\<detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) συνάρτηση για τύπους με διαθέσιμο τελεστή <. |
| std::enable_if<\!detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) συνάρτηση για τύπους χωρίς διαθέσιμο τελεστή <. |
| void [set_Comparator](./set_comparator/)(const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<T\>\>\&) | Ορίζει αντικείμενο συγκριτή. |

## Δείτε επίσης

* Χώρος ονομάτων [System::Collections::Generic](../)
* Βιβλιοθήκη [Aspose.Slides](../../)