---
title: ToInt32()
second_title: Aspose.Slides for C++ API Αναφορά
description: Μετατρέπει τέσσερα byte από τον καθορισμένο πίνακα που αρχίζει στον καθορισμένο δείκτη σε τιμή ακέραιου 32-bit.
type: docs
weight: 66
url: /el/system/bitconverter/toint32/
---
## BitConverter::ToInt32(const System::ArrayPtr\<uint8_t\>\&, int) μέθοδος

Μετατρέπει τέσσερα byte από τον καθορισμένο πίνακα που αρχίζει στον καθορισμένο δείκτη σε τιμή ακέραιου 32-bit.

```cpp
static int System::BitConverter::ToInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) που περιέχει τα byte για μετατροπή |
| startIndex | int | Δείκτης στον πίνακα όπου αρχίζει η λήψη των byte για μετατροπή |

### Τιμή Επιστροφής

Τιμή ακέραιου 32-bit που προκύπτει από τη μετατροπή

## BitConverter::ToInt32(const System::Details::ArrayView\<uint8_t\>\&, int) μέθοδος

Μετατρέπει τέσσερα byte από τον καθορισμένο πίνακα που αρχίζει στον καθορισμένο δείκτη σε τιμή ακέραιου 32-bit.

```cpp
static int System::BitConverter::ToInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView που περιέχει τα byte για μετατροπή |
| startIndex | int | Δείκτης στον πίνακα όπου αρχίζει η λήψη των byte για μετατροπή |

### Τιμή Επιστροφής

Τιμή ακέραιου 32-bit που προκύπτει από τη μετατροπή

## Δείτε επίσης

* Τύπος ορισμού [ArrayPtr](../../arrayptr/)
* Τάξη [BitConverter](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)