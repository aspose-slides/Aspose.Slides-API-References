---
title: ToSingle()
second_title: Αναφορά API του Aspose.Slides για C++
description: Μετατρέπει τέσσερα byte από τον καθορισμένο πίνακα, αρχίζοντας από τον καθορισμένο δείκτη, σε τιμή κινητής υποδιαστολής μονής ακριβείας.
type: docs
weight: 131
url: /el/system/bitconverter/tosingle/
---
## BitConverter::ToSingle(const System::ArrayPtr\<uint8_t\>\&, int) μέθοδος

Μετατρέπει τέσσερα byte από τον καθορισμένο πίνακα, αρχίζοντας από το καθορισμένο δείκτη, σε τιμή κινητής υποδιαστολής μονής ακριβείας.

```cpp
static float System::BitConverter::ToSingle(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) που περιέχει τα byte προς μετατροπή |
| startIndex | int | Δείκτης στον πίνακα από όπου θα ξεκινήσει η λήψη των byte για τη μετατροπή |

### Τιμή επιστροφής

Τιμή κινητής υποδιαστολής μονής ακριβείας που προκύπτει από τη μετατροπή

## BitConverter::ToSingle(const System::Details::ArrayView\<uint8_t\>\&, int) μέθοδος

Μετατρέπει τέσσερα byte από τον καθορισμένο πίνακα, αρχίζοντας από το καθορισμένο δείκτη, σε τιμή κινητής υποδιαστολής μονής ακριβείας.

```cpp
static float System::BitConverter::ToSingle(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView που περιέχει τα byte προς μετατροπή |
| startIndex | int | Δείκτης στον πίνακα από όπου θα ξεκινήσει η λήψη των byte για τη μετατροπή |

### Τιμή επιστροφής

Τιμή κινητής υποδιαστολής μονής ακριβείας που προκύπτει από τη μετατροπή

## Δείτε επίσης

* Typedef [ArrayPtr](../../arrayptr/)
* Κλάση [BitConverter](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)