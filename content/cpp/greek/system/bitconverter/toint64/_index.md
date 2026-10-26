---
title: ToInt64()
second_title: Αναφορά API του Aspose.Slides για C++
description: Μετατρέπει οκτώ bytes από τον καθορισμένο πίνακα ξεκινώντας από το καθορισμένο ευρετήριο σε τιμή ακέραιου 64-bit.
type: docs
weight: 79
url: /el/system/bitconverter/toint64/
---
## BitConverter::ToInt64(const System::ArrayPtr\<uint8_t\>\&, int) μέθοδος


Μετατρέπει οκτώ bytes από τον καθορισμένο πίνακα ξεκινώντας από το καθορισμένο ευρετήριο σε τιμή ακέραιου 64-bit.

```cpp
static int64_t System::BitConverter::ToInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) που περιέχει bytes για μετατροπή |
| startIndex | int | Δείκτης στον πίνακα από τον οποίο αρχίζει η λήψη των bytes για μετατροπή |

### Τιμή Επιστροφής

Τιμή ακέραιου 64-bit που προκύπτει από τη μετατροπή

## BitConverter::ToInt64(const System::Details::ArrayView\<uint8_t\>\&, int) μέθοδος


Μετατρέπει οκτώ bytes από τον καθορισμένο πίνακα ξεκινώντας από το καθορισμένο ευρετήριο σε τιμή ακέραιου 64-bit.

```cpp
static int64_t System::BitConverter::ToInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView που περιέχει bytes για μετατροπή |
| startIndex | int | Δείκτης στον πίνακα από τον οποίο αρχίζει η λήψη των bytes για μετατροπή |

### Τιμή Επιστροφής

Τιμή ακέραιου 64-bit που προκύπτει από τη μετατροπή

## Δείτε επίσης

* Typedef [ArrayPtr](../../arrayptr/)
* Κλάση [BitConverter](../)
* Χώρος Ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)