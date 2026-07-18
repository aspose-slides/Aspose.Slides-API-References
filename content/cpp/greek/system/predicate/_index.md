---
title: Predicate
second_title: Αναφορά API Aspose.Slides για C++
description: Αντιπροσωπεύει έναν δείκτη σε ένα predicate - μια κλήσιμη οντότητα που δέχεται ένα μόνο όρισμα και επιστρέφει μια τιμή bool.
type: docs
weight: 4148
url: /el/system/predicate/
---
## Δήλωση τύπου Predicate

Αντιπροσωπεύει έναν δείκτη σε ένα predicate - μια κλήσιμη οντότητα που δέχεται ένα μόνο όρισμα και επιστρέφει μια τιμή bool.

```cpp
using System::Predicate = typedef MulticastDelegate<bool(T)>
```

## Σημειώσεις



```cpp
#include "system/array.h"
#include "system/predicate.h"
#include <iostream>

int main()
{
  // Γεμίστε τον πίνακα.
  auto arr = System::MakeArray<int>({-1, -123, 5, 3, 7});

  // Δημιουργήστε το predicate που επιστρέφει ένα στοιχείο του πίνακα που είναι μεγαλύτερο από 3.
  const auto predicate = static_cast<System::Predicate<int>>([](int a) -> bool
  {
      return a > 3;
  });

  // Βρείτε το πρώτο στοιχείο του πίνακα χρησιμοποιώντας το δημιουργημένο predicate και εκτυπώστε το.
  int firstItem = System::Array<int>::Find(arr, predicate);
  std::cout << firstItem << std::endl;

  return 0;
}
/*
Αυτό το παράδειγμα κώδικα παράγει την ακόλουθη έξοδο:
5
*/
```

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)