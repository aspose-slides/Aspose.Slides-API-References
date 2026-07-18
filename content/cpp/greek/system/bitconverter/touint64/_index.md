---
title: ToUInt64()
second_title: Aspose.Slides για C++ API Αναφορά
description: Μετατρέπει οκτώ byte από τον καθορισμένο πίνακα που αρχίζει στον καθορισμένο δείκτη σε αμετάβλητη τιμή 64-bit ακέραιου.
type: docs
weight: 118
url: /el/system/bitconverter/touint64/
---
## BitConverter::ToUInt64(const System::ArrayPtr\<uint8_t\>\&, int) μέθοδος

Μετατρέπει οκτώ byte από τον καθορισμένο πίνακα που αρχίζει στον καθορισμένο δείκτη σε αμετάβλητη τιμή 64-bit ακέραιου.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) που περιέχει τα byte για μετατροπή |
| startIndex | int | Δείκτης στον πίνακα από τον οποίο αρχίζει η λήψη των byte για μετατροπή |

### Τιμή Επιστροφής

Αμετάβλητη τιμή 64-bit ακέραιου που προκύπτει από τη μετατροπή

## BitConverter::ToUInt64(const System::Details::ArrayView\<uint8_t\>\&, int) μέθοδος

Μετατρέπει οκτώ byte από τον καθορισμένο πίνακα που αρχίζει στον καθορισμένο δείκτη σε αμετάβλητη τιμή 64-bit ακέραιου.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView που περιέχει τα byte για μετατροπή |
| startIndex | int | Δείκτης στον πίνακα από τον οποίο αρχίζει η λήψη των byte για μετατροπή |

### Τιμή Επιστροφής

Αμετάβλητη τιμή 64-bit ακέραιου που προκύπτει από τη μετατροπή

## Δείτε επίσης

* Typedef [ArrayPtr](../../arrayptr/)
* Κλάση [BitConverter](../)
* Χώρος ονομάτων [System](../../)
* Library [Aspose.Slides](../../../)