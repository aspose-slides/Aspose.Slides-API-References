---
title: Boolean
second_title: Aspose.Slides για C++ API Τεκμηρίωση
description: Κλάση που διατηρεί static μέλη του τύπου System.Boolean .Net.
type: docs
weight: 79
url: /el/system/boolean/
---
## Κλάση Boolean

Κλάση που διατηρεί static μέλη του τύπου [System.Boolean](./) .[Net](../../system.net/).

```cpp
class Boolean
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| static **bool** [Parse](./parse/)(const [String](../string/)\&) | Μετατρέπει τη συγκεκριμένη συμβολοσειρά σε τιμή τύπου bool. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**\&) | Μετατρέπει τη συγκεκριμένη συμβολοσειρά σε τιμή τύπου bool. |

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| static [FalseString](./falsestring/) | [String](../string/) αναπαράσταση της τιμής boolean 'false'. |
| static [TrueString](./truestring/) | [String](../string/) αναπαράσταση της τιμής boolean 'true'. |

## Παρατηρήσεις

```cpp
#include <system/boolean.h>

using namespace System;

int main()
{
  // Δημιουργεί τη μεταβλητή boolean.
  bool isWeekend = false;

  // Αναλύει τη συμβολοσειρά εισόδου και εκτυπώνει το αποτέλεσμα.
  if (Boolean::TryParse(u"True", isWeekend))
  {
    std::cout << "Is weekend: " << (isWeekend ? "Yes" : "No");
  }
  else
  {
    std::cerr << "Something went wrong" << std::endl;
  }

  return 0;
}
/*
Αυτό το παράδειγμα κώδικα παράγει την ακόλουθη έξοδο:
Είναι Σαββατοκύριακο: Ναι
*/
```

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)