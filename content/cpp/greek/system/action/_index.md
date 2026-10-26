---
title: Action
second_title: Αναφορά API Aspose.Slides για C++
description: Τύπος delegate που αναφέρεται σε μεθόδους που δεν έχουν τιμή επιστροφής.
type: docs
weight: 3563
url: /el/system/action/
---
## Ορισμός τύπου Action


Τύπος delegate που αναφέρεται σε μεθόδους που δεν έχουν τιμή επιστροφής.

```cpp
using System::Action = typedef MulticastDelegate<void(Args...)>
```

## Παρατηρήσεις



```cpp
#include <system/action.h>

using namespace System;

// Η λειτουργία που εκτυπώνει το δοσμένο κείμενο.
void PrintString(const String &string)
{
  using namespace std;
  cout << string << endl;
}

int main()
{
  // Δημιουργήστε μια παρουσία του Action.
  auto action = Action<String>(std::bind(&PrintString, std::placeholders::_1));

  // Κλήση της ενέργειας.
  action(u"Hello, world!");

  return 0;
}
/*
Αυτό το παράδειγμα κώδικα παράγει την ακόλουθη έξοδο:
Hello, world!
*/
```

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)