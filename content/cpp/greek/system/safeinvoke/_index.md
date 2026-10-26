---
title: SafeInvoke()
second_title: Aspose.Slides για C++ Αναφορά API
description: Υλοποίηση της μετάφρασης του τελεστή '?.'.
type: docs
weight: 2614
url: /el/system/safeinvoke/
---
## System::SafeInvoke(T0\&&, T1\&&) συνάρτηση

Υλοποίηση της μετάφρασης του τελεστή '?.'.

```cpp
template<typename T0,typename T1> static auto System::SafeInvoke(T0 &&expr, T1 &&func)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T0 | τύπος έκφρασης. |
| T1 | Τύπος του lambda που περιβάλλει την έκφραση 'WhenTrue'. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| expr | T0\&& | τιμή έκφρασης. |
| func | T1\&& | Έκφραση 'WhenTrue' δεσμευμένη σε functor. |

### Τιμή Επιστροφής

Αν η τιμή expr δεν είναι null, επιστρέφει το func που κλήθηκε με τη τιμή του ως πρώτο όρισμα, διαφορετικά επιστρέφει null.

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)