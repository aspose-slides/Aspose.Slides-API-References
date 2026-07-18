---
title: PrintToString()
second_title: Aspose.Slides για C++ API Αναφορά
description: Εκτυπώνει το αντικείμενο σε συμβολοσειρά επιλέγοντας τη σωστή συνάρτηση σειριοποίησης.
type: docs
weight: 1
url: /el/system.testpredicates.details/printtostring/
---
## System::TestPredicates::Details::PrintToString(const T\&) συνάρτηση

Εκτυπώνει το αντικείμενο σε συμβολοσειρά επιλέγοντας την κατάλληλη συνάρτηση σειριοποίησης.

```cpp
template<typename T> std::enable_if_t<!TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | [Object](../../system/object/) τύπος. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) για εκτύπωση. |

### Τιμή Επιστροφής

[String](../../system/string/) αναπαραστάσεις του περασμένου αντικειμένου.

## System::TestPredicates::Details::PrintToString(const T\&) συνάρτηση

Εκτυπώνει κοντέινερ τύπου ICollection σε συμβολοσειρά εκτυπώνοντας τα στοιχεία τους (όχι περισσότερο από 32).

```cpp
template<typename T> std::enable_if_t<TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | [Object](../../system/object/) τύπος. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) για εκτύπωση. |

### Τιμή Επιστροφής

Συνεκτικές συμβολοσειρές αναπαραστάσεων των περιεχόμενων στοιχείων.

## System::TestPredicates::Details::PrintToString(std::nullptr_t) συνάρτηση

Εκτυπώνει nullptr σε συμβολοσειρά.

```cpp
std::string System::TestPredicates::Details::PrintToString(std::nullptr_t)
```

### Τιμή Επιστροφής

\"nullptr\" συμβολοσειρά.

## System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable\<bool\>\&) συνάρτηση

Εκτυπώνει τις συλλογές [IEnumerable<bool>](../../system.collections.generic/ienumerable/) σε συμβολοσειρά εκτυπώνοντας τα στοιχεία τους (όχι περισσότερο από 32).

```cpp
std::string System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable<bool> &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | [Object](../../system/object/) τύπος. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<**bool**\>\& | [Object](../../system/object/) για εκτύπωση. |

### Τιμή Επιστροφής

Συνεκτικές συμβολοσειρές αναπαραστάσεων των περιεχόμενων στοιχείων.

## Δείτε επίσης

* Κλάση [IEnumerable](../../system.collections.generic/ienumerable/)
* Δομή [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Χώρος ονομάτων [System::TestPredicates::Details](../)
* Βιβλιοθήκη [Aspose.Slides](../../)