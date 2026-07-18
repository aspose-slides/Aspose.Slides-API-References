---
title: ToChar()
second_title: Αναφορά API του Aspose.Slides για C++
description: Μετατρέπει δύο byte από τον καθορισμένο πίνακα που αρχίζει από τον καθορισμένο δείκτη σε τιμή char_t.
type: docs
weight: 40
url: /el/system/bitconverter/tochar/
---
## BitConverter::ToChar(const System::ArrayPtr\<uint8_t\>\&, int) μέθοδος


Μετατρέπει δύο byte από τον καθορισμένο πίνακα που αρχίζει από τον καθορισμένο δείκτη σε τιμή char_t.

```cpp
static char_t System::BitConverter::ToChar(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) που περιέχει byte προς μετατροπή |
| startIndex | int | Δείκτης στον πίνακα από τον οποίο ξεκινά η λήψη byte για τη μετατροπή |

### Τιμή Επιστροφής

char_t τιμή που προκύπτει από τη μετατροπή

## BitConverter::ToChar(const System::Details::ArrayView\<uint8_t\>\&, int) μέθοδος


Μετατρέπει δύο byte από τον καθορισμένο πίνακα που αρχίζει από τον καθορισμένο δείκτη σε τιμή char_t.

```cpp
static char_t System::BitConverter::ToChar(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView που περιέχει byte προς μετατροπή |
| startIndex | int | Δείκτης στον πίνακα από τον οποίο ξεκινά η λήψη byte για τη μετατροπή |

### Τιμή Επιστροφής

char_t τιμή που προκύπτει από τη μετατροπή

## Δείτε επίσης

* Τύπος ορισμού [ArrayPtr](../../arrayptr/)
* Κλάση [BitConverter](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)