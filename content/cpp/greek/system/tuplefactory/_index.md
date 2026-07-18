---
title: TupleFactory
second_title: Aspose.Slides για C++ API Αναφορά
description: Παρέχει στατικές μεθόδους για τη δημιουργία αντικειμένων tuple.
type: docs
weight: 1340
url: /el/system/tuplefactory/
---
## TupleFactory κλάση


Παρέχει στατικές μεθόδους για τη δημιουργία αντικειμένων tuple.

```cpp
class TupleFactory
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<Args...\>\> [Create](./create/)(Args...) | Δημιουργεί ένα νέο αντικείμενο tuple. |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<T1, T2, T3, T4, T5, T6, T7, [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<TRest\>\>\>\> [Create](./create/)(T1, T2, T3, T4, T5, T6, T7, TRest) | Δημιουργεί ένα νέο 8-tuple. Το 8ο στοιχείο αποθηκεύεται μέσα στο [Tuple](../tuple/). |
## Παρατηρήσεις



```cpp
#include "system/smart_ptr.h"
#include "system/tuple.h"
#include <iostream>

int main()
{
  const auto tuple = System::TupleFactory::Create(256, 16, 64);

  std::cout <<
    "Item 1: " << tuple->get_Item<0>() << std::endl <<
    "Item 2: " << tuple->get_Item<1>() << std::endl <<
    "Item 3: " << tuple->get_Item<2>() << std::endl;

  return 0;
}
/*
Αυτό το παράδειγμα κώδικα παράγει την παρακάτω έξοδο:
Αντικείμενο 1: 256
Αντικείμενο 2: 16
Αντικείμενο 3: 64
*/
```

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)