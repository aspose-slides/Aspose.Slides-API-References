---
title: TrueForAll()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει εάν όλα τα στοιχεία στον καθορισμένο πίνακα ικανοποιούν τις συνθήκες που ορίζονται από την καθορισμένη συνθήκη.
type: docs
weight: 677
url: /el/system/array/trueforall/
---
## Array::TrueForAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) μέθοδος

Καθορίζει εάν όλα τα στοιχεία στον καθορισμένο πίνακα ικανοποιούν τις συνθήκες που ορίζονται από την καθορισμένη συνθήκη.

```cpp
static bool System::Array<T>::TrueForAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) στοιχεία των οποίων να ταιριάζουν με τις συνθήκες |
| match | [System::Predicate](../../predicate/)\<T\> | Μια συνθήκη που ορίζει τις συνθήκες για το ταίριασμα των στοιχείων του πίνακα |

### Τιμή Επιστροφής

true εάν όλα τα στοιχεία του πίνακα arr ικανοποιούν τις συνθήκες που ορίζονται από τη συνθήκη match, διαφορετικά false

## Δείτε επίσης

* Τύπος ορισμού [ArrayPtr](../../arrayptr/)
* Τύπος ορισμού [Predicate](../../predicate/)
* Κλάση [Array](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)