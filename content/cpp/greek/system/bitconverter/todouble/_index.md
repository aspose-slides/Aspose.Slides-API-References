---
title: ToDouble()
second_title: Aspose.Slides για C++ Αναφορά API
description: Μετατρέπει οκτώ bytes από τον καθορισμένο πίνακα αρχίζοντας από τον καθορισμένο δείκτη σε τιμή κινητής υποδιαστολής διπλής ακρίβειας.
type: docs
weight: 144
url: /el/system/bitconverter/todouble/
---
## BitConverter::ToDouble(const System::ArrayPtr\<uint8_t\>\&, int) μέθοδος

Μετατρέπει οκτώ bytes από τον καθορισμένο πίνακα αρχίζοντας από τον καθορισμένο δείκτη σε τιμή κινητής υποδιαστολής διπλής ακρίβειας.

```cpp
static double System::BitConverter::ToDouble(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) που περιέχει τα bytes για μετατροπή |
| startIndex | int | Δείκτης στον πίνακα όπου αρχίζει η λήψη των bytes για τη μετατροπή |

### Τιμή Επιστροφής

Τιμή κινητής υποδιαστολής διπλής ακρίβειας που προκύπτει από τη μετατροπή

## BitConverter::ToDouble(const System::Details::ArrayView\<uint8_t\>\&, int) μέθοδος

Μετατρέπει οκτώ bytes από τον καθορισμένο πίνακα αρχίζοντας από τον καθορισμένο δείκτη σε τιμή κινητής υποδιαστολής διπλής ακρίβειας.

```cpp
static double System::BitConverter::ToDouble(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView που περιέχει τα bytes για μετατροπή |
| startIndex | int | Δείκτης στον πίνακα όπου αρχίζει η λήψη των bytes για τη μετατροπή |

### Τιμή Επιστροφής

Τιμή κινητής υποδιαστολής διπλής ακρίβειας που προκύπτει από τη μετατροπή

## Δείτε επίσης

* Τύπος [ArrayPtr](../../arrayptr/)
* Κλάση [BitConverter](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)