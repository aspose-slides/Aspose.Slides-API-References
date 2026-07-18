---
title: ToUInt32()
second_title: Aspose.Slides για το C++ API Αναφορά
description: Μετατρέπει τέσσερα byte από τον καθορισμένο πίνακα που αρχίζει στον καθορισμένο δείκτη σε τιμή ακεραίου 32-bit χωρίς πρόσημο.
type: docs
weight: 105
url: /el/system/bitconverter/touint32/
---
## BitConverter::ToUInt32(const System::ArrayPtr\<uint8_t\>\&, int) μέθοδος

Μετατρέπει τέσσερα byte από τον καθορισμένο πίνακα που αρχίζει στον καθορισμένο δείκτη σε τιμή ακεραίου 32-bit χωρίς πρόσημο.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) που περιέχει τα byte για μετατροπή |
| startIndex | int | Δείκτης στον πίνακα από τον οποίο θα ξεκινήσει η λήψη byte για τη μετατροπή |

### Τιμή Επιστροφής

Τιμή ακεραίου 32-bit χωρίς πρόσημο που προκύπτει από τη μετατροπή

## BitConverter::ToUInt32(const System::Details::ArrayView\<uint8_t\>\&, int) μέθοδος

Μετατρέπει τέσσερα byte από τον καθορισμένο πίνακα που αρχίζει στον καθορισμένο δείκτη σε τιμή ακεραίου 32-bit χωρίς πρόσημο.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView που περιέχει τα byte για μετατροπή |
| startIndex | int | Δείκτης στον πίνακα από τον οποίο θα ξεκινήσει η λήψη byte για τη μετατροπή |

### Τιμή Επιστροφής

Τιμή ακεραίου 32-bit χωρίς πρόσημο που προκύπτει από τη μετατροπή

## Δείτε επίσης

* Typedef [ArrayPtr](../../arrayptr/)
* Κλάση [BitConverter](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)