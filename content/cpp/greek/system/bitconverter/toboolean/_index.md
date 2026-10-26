---
title: ToBoolean()
second_title: Aspose.Slides για C++ Αναφορά API
description: Μετατρέπει ένα byte από τον καθορισμένο πίνακα που αρχίζει από τον καθορισμένο δείκτη σε boolean τιμή.
type: docs
weight: 27
url: /el/system/bitconverter/toboolean/
---
## BitConverter::ToBoolean(const System::ArrayPtr\<uint8_t\>\&, int) μέθοδος

Μετατρέπει ένα byte από τον καθορισμένο πίνακα που αρχίζει από το καθορισμένο δείκτη σε boolean τιμή.

```cpp
static bool System::BitConverter::ToBoolean(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) που περιέχει bytes για μετατροπή |
| startIndex | int | Δείκτης στον πίνακα από τον οποίο ξεκινά η λήψη bytes για μετατροπή |

### Τιμή Επιστροφής

[Boolean](../../boolean/) τιμή που προκύπτει από τη μετατροπή

## BitConverter::ToBoolean(const System::Details::ArrayView\<uint8_t\>\&, int) μέθοδος

Μετατρέπει ένα byte από τον καθορισμένο πίνακα που αρχίζει από το καθορισμένο δείκτη σε Boolean τιμή.

```cpp
static bool System::BitConverter::ToBoolean(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView που περιέχει bytes για μετατροπή |
| startIndex | int | Δείκτης στον πίνακα από τον οποίο ξεκινά η λήψη bytes για μετατροπή |

### Τιμή Επιστροφής

[Boolean](../../boolean/) τιμή που προκύπτει από τη μετατροπή

## Δείτε επίσης

* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)