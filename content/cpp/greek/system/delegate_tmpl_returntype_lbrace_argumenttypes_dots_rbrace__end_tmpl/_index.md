---
title: Delegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides για το API του C++
description: "Αντιπροσωπεύει έναν δείκτη σε μια λειτουργία, μέθοδο ή αντικείμενο συνάρτησης. Αυτός ο τύπος θα πρέπει να εκχωρείται στη στοίβα και να περνιέται σε συναρτήσεις με τιμή ή με αναφορά. Ποτέ μην χρησιμοποιείτε την κλάση System::SmartPtr για να διαχειρίζεστε αντικείμενα αυτού του τύπου."
type: docs
weight: 287
url: /el/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## Delegate< ReturnType(ArgumentTypes...)> κλάση


Αντιπροσωπεύει ένα δείκτη προς μια λειτουργία, μέθοδο ή ένα αντικείμενο συνάρτησης. Αυτός ο τύπος πρέπει να εκχωρείται στη στοίβα και να περνιέται σε συναρτήσεις με τιμή ή με αναφορά. Ποτέ μην χρησιμοποιείτε την κλάση [System::SmartPtr](../smartptr/) για να διαχειρίζεστε αντικείμενα αυτού του τύπου.

```cpp
template<class ReturnType,class...>class Delegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| ReturnType | Ο τύπος επιστροφής μιας λειτουργίας, μεθόδου ή δείκτη αντικειμένου συνάρτησης που αντιπροσωπεύεται από την κλάση |
| ArgumentTypes | Η λίστα ορισμάτων μιας λειτουργίας, μεθόδου ή δείκτη αντικειμένου συνάρτησης που αντιπροσωπεύεται από την κλάση |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  [Delegate](./delegate/)() | Προεπιλεγμένος κατασκευαστής. Δημιουργεί το αντικείμενο delegate που δεν δείχνει σε τίποτα. |
|  [Delegate](./delegate/)(const Delegate\&) |  |
|  [Delegate](./delegate/)(Delegate\&&) | Μετακινούμενος κατασκευαστής αντιγραφής. Παίρνει την κυριότητα μιας οντότητας στην οποία δείχνει ο καθορισμένος delegate. |
|  [Delegate](./delegate/)(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) | Κατασκευαστής. Δημιουργεί ένα αντικείμενο delegate από τον καθορισμένο δείκτη σε ελεύθερη λειτουργία ή στατική μέθοδο. |
|  [Delegate](./delegate/)(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) | Κατασκευαστής. Δημιουργεί ένα delegate από τον καθορισμένο δείκτη στο αντικείμενο συνάρτησης που δημιουργείται από το std::bind(). |
|  [Delegate](./delegate/)(int, T\&) | Κατασκευαστής. Δημιουργεί ένα delegate από το καθορισμένο αντικείμενο συνάρτησης. |
|  [Delegate](./delegate/)(long, T\&&) | Μετακινούμενος κατασκευαστής. Δημιουργεί ένα delegate από το καθορισμένο αντικείμενο συνάρτησης. |
|  [Delegate](./delegate/)(MemberType ClassType::*, ClassType *) | Κατασκευαστής. Δημιουργεί ένα delegate που δείχνει στη συγκεκριμένη μη-στατική μέθοδο του καθορισμένου αντικειμένου. |
|  [Delegate](./delegate/)(MemberType MemberClass::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Κατασκευαστής. Δημιουργεί ένα delegate που δείχνει στη συγκεκριμένη μη-στατική μέθοδο του καθορισμένου αντικειμένου. |
|  [Delegate](./delegate/)(std::function\<R(Args...)>) | Δημιουργεί ένα αντικείμενο delegate που δείχνει σε ένα αντικείμενο συνάρτησης std::function. |
| **bool** [Empty](./empty/)() const | Καθορίζει εάν το τρέχον αντικείμενο delegate είναι κενό, π.χ. δεν δείχνει σε καμία οντότητα. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | Καλεί μια λειτουργία, μέθοδο ή αντικείμενο συνάρτησης στο οποίο δείχνει το τρέχον αντικείμενο delegate. |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)(const [Delegate](./delegate/)\&) |  |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)([Delegate](./delegate/)\&&) | Μετακινούμενος τελεστής ανάθεσης. Παίρνει την κυριότητα μιας οντότητας στην οποία δείχνει ο καθορισμένος delegate. |
| **bool** [operator==](./operator_equal_equal/)(const [Delegate](./delegate/)\&) const | Συγκρίνει δύο αντικείμενα delegate για να ελέγξει εάν δείχνουν στην ίδια οντότητα. |
## Παρατηρήσεις



```cpp
#include "system/delegate.h"
#include <iostream>

// Δηλώστε το delegate.
using Message = System::Delegate<void()>;

void PrintMessage()
{
  std::cout << "Hello, world!" << std::endl;
}

int main()
{
  // Αναθέστε στη μεταβλητή τη διεύθυνση της συνάρτησης PrintMessage.
  Message mes = Message(&PrintMessage);

  // Καλείτε τη συνάρτηση.
  mes();

  return 0;
}
/*
Αυτό το παράδειγμα κώδικα παράγει την ακόλουθη έξοδο:
Γειά σου, κόσμε!
*/
```

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)