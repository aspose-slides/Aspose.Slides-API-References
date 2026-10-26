---
title: NullableBoolHelper()
second_title: Aspose.Slides για C++ API Αναφορά
description: Συνάρτηση βοηθός για να ελέγξει αν το this και το other είναι και τα δύο μη null και να καλέσει μια λάμδα εάν ισχύει. Χρησιμοποιείται στο implementation.s.
type: docs
weight: 105
url: /el/system/nullable/nullableboolhelper/
---
## Nullable::NullableBoolHelper(const T1\&, const std::function\<bool()>\&, bool) const μέθοδος

Συνάρτηση βοηθός για να ελέγξει αν αυτό και **other** δεν είναι null και να καλέσει μια λάμδα εάν ισχύει. Χρησιμοποιείται στο implementation.s.

```cpp
template<typename T1> bool System::Nullable<T>::NullableBoolHelper(const T1 &other, const std::function<bool()> &f, bool default_if_both_are_null=false) const
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Άλλος nullable τύπος. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | const T1\& | Άλλη nullable τιμή για σύγκριση. |
| f | const std::function\<**bool**()>\& | Λάμδα για κλήση εάν τόσο το **this** όσο και το **other** δεν είναι null. |
| default_if_both_are_null | **bool** | Τιμή επιστροφής εάν και οι δύο τιμές είναι null. |

### Τιμή επιστροφής

false αν είτε το **this** είτε το **other** είναι null· **default_if_both_are_null** αν και τα δύο είναι null· αποτέλεσμα της κλήσης **f** αν και τα δύο δεν είναι null.

## Δείτε επίσης

* Κλάση [Nullable](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)