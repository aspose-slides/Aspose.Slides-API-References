---
title: Comparison
second_title: Aspose.Slides για το C++ API
description: "Αναπαριστά έναν δείκτη στη μέθοδο που συγκρίνει δύο αντικείμενα του ίδιου τύπου. Αυτός ο τύπος πρέπει να εκχωρείται στο στοίβο και να μεταβιβάζεται σε συναρτήσεις με τιμή ή με αναφορά. Ποτέ μην χρησιμοποιείτε τη κλάση System::SmartPtr για τη διαχείριση αντικειμένων αυτού του τύπου."
type: docs
weight: 183
url: /el/system/comparison/
---
## Σύγκριση κλάση

Αναπαριστά έναν δείκτη στη μέθοδο που συγκρίνει δύο αντικείμενα του ίδιου τύπου. Αυτός ο τύπος θα πρέπει να εκχωρείται στο στοίβο και να περνιέται σε συναρτήσεις με τιμή ή με αναφορά. Ποτέ μην χρησιμοποιείτε [System::SmartPtr](../smartptr/) κλάση για τη διαχείριση αντικειμένων αυτού του τύπου.

```cpp
template<typename T>class Comparison : public System::MulticastDelegate<int(T, T)>
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των αντικειμένων που συγκρίνει η μέθοδος |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| **bool** [operator()](./operator_call/)(T, T) | Καλεί το αντικείμενο που μπορεί να κληθεί στον οποίο δείχνει το τρέχον αντικείμενο. |

## Παρατηρήσεις



```cpp
#include "system/comparison.h"
#include "system/console.h"
#include "system/exceptions.h"
#include "system/string.h"
#include <algorithm>
#include <initializer_list>
#include <vector>

using namespace System;

// Η κλάση προτύπου που αναπαριστά έναν δυναμικό πίνακα.
template <typename T>
class MyArray
{
  // Χρησιμοποιείται για την αποθήκευση των δεδομένων του πίνακα.
  std::vector<T> m_data;

public:
  // Δημιουργεί ένα νέο στιγμιότυπο του δυναμικού μας πίνακα.
  MyArray(const std::initializer_list<T>& source) : m_data(source) {};

  // Χρησιμοποιείται για την ταξινόμηση των δεδομένων του πίνακα. Αυτή η μέθοδος δέχεται ένα στιγμιότυπο του
  // πρότυπο κλάσης 'System::Comparison'.
  void Sort(Comparison<T> comparison)
  {
    if (comparison.IsNull())
    {
      throw ArgumentNullException(u"comparison");
    }
    std::sort(m_data.begin(), m_data.end(), comparison);
  }

  // Επιστρέφει τον αριθμό των στοιχείων που αποθηκεύει ο δυναμικός μας πίνακας.
  size_t get_Size()
  {
    return m_data.size();
  }

  // Χρησιμοποιείται για την ανάκτηση ενός στοιχείου στο συγκεκριμένο δείκτη.
  T& operator[](int index)
  {
    if (index < 0 || index >= m_data.size())
    {
      throw IndexOutOfRangeException(u"index");
    }
    return m_data[index];
  }
};

int main() {
  // Δημιουργήστε ένα στιγμιότυπο της κλάσης MyArray με τα καθορισμένα στοιχεία.
  MyArray<String> arr = {u"a", u"e", u"c", u"b", u"d"};

  // Ταξινόμηση κατά αύξουσα σειρά των στοιχείων του δυναμικού πίνακα.
  arr.Sort([](const String &a, const String &b) -> int
  {
    return String::Compare(a, b);
  });

  // Εκτυπώστε τα στοιχεία του δυναμικού πίνακα.
  for (auto i = 0; i < arr.get_Size(); ++i)
  {
    Console::WriteLine(arr[i]);
  }

  return 0;
}
/*
Αυτό το παράδειγμα κώδικα παράγει την ακόλουθη έξοδο:
a
b
c
d
e
*/
```

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)