---
title: Func
second_title: Aspose.Slides για C++ API Αναφορά
description: "Αντιπρόσωπος συνάρτησης. Αυτός ο τύπος πρέπει να εκχωρηθεί στο stack και να περάσει στις συναρτήσεις με τιμή ή με αναφορά. Ποτέ μην χρησιμοποιείτε την κλάση System::SmartPtr για τη διαχείριση αντικειμένων αυτού του τύπου."
type: docs
weight: 859
url: /el/system/func/
---
## Func κλάση

Αντιπρόσωπος συνάρτησης. Αυτός ο τύπος πρέπει να εκχωρηθεί στο stack και να περάσει στις συναρτήσεις με τιμή ή με αναφορά. Ποτέ μην χρησιμοποιείτε την κλάση [System::SmartPtr](../smartptr/) για τη διαχείριση αντικειμένων αυτού του τύπου.

```cpp
template<typename...>class Func : public System::MulticastDelegate<::System::Detail::FuncArgsReorderer<void(), Args...>::type>
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Args | Παράμετροι κλήσης, έπειτα υποχρεωτικός τύπος επιστροφής. |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  [Func](./func/)() | Κατασκευαστής προεπιλογής που δημιουργεί null-Func. |
|  [Func](./func/)(T\&&) | Κατασκευαστής που κατασκευάζει αντικείμενο [Func](./) και αναθέτει τιμή (είτε πραγματικό callback είτε nullptr) σε αυτό. |
|  [Func](./func/)(const [Func](./)\&) | Κατασκευαστής αντιγραφής. |
|  [Func](./func/)([Func](./)\&&) | Κατασκευαστής μετακίνησης. |
| [Func](./)\& [operator=](./operator_equal/)(const [Func](./)\&) | Ανάθεση αντιγραφής. |
| [Func](./)\& [operator=](./operator_equal/)([Func](./)\&&) | Ανάθεση μετακίνησης. |
|  [~Func](./~func/)() | Καταστροφέας. |

## Παρατηρήσεις

```cpp
#include "system/func.h"
#include <iostream"

// Αυτή η συνάρτηση δέχεται μια παρουσία του αντιπροσώπου System::Func ως παράμετρο.
void Print(int x, const System::Func<int, int> &func)
{
  std::cout << func(x) << std::endl;
}

int main()
{
  // Δημιουργήστε μια παρουσία του αντιπροσώπου System::Func.
  auto func = static_cast<System::Func<int, int>>([](int x) -> int
  {
    return x * x;
  });

  // Περάστε τη δημιουργημένη παρουσία ως όρισμα συνάρτησης.
  Print(1, func);
  Print(2, func);
  Print(3, func);

  return 0;
}
/*
Αυτό το παράδειγμα κώδικα παράγει την παρακάτω έξοδο:
1
4
9
*/
```

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)