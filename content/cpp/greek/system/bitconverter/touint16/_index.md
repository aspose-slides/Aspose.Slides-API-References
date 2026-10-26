---
title: ToUInt16()
second_title: Aspose.Slides για C++ API Αναφορά
description: Μετατρέπει δύο bytes από τον συγκεκριμένο πίνακα, αρχίζοντας από τον συγκεκριμένο δείκτη, σε τιμή ακεραίου χωρίς πρόσημο 16-bit.
type: docs
weight: 92
url: /el/system/bitconverter/touint16/
---
## BitConverter::ToUInt16(const System::ArrayPtr\<uint8_t\>\&, int) μέθοδος

Μετρέπει δύο bytes από τον καθορισμένο πίνακα αρχής από τον καθορισμένο δείκτη σε τιμή ακεραίου χωρίς πρόσημο 16-bit.

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) που περιέχει τα bytes για μετατροπή |
| startIndex | int | Δείκτης στον πίνακα από τον οποίο ξεκινά η λήψη bytes για μετατροπή |

### Return Value

Τιμή ακέραιου χωρίς πρόσημο 16-bit που προκύπτει από τη μετατροπή

## BitConverter::ToUInt16(const System::Details::ArrayView\<uint8_t\>\&, int) μέθοδος

Μετρέπει δύο bytes από τον καθορισμένο πίνακα αρχής από τον καθορισμένο δείκτη σε τιμή ακεραίου χωρίς πρόσημο 16-bit.

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView που περιέχει τα bytes για μετατροπή |
| startIndex | int | Δείκτης στον πίνακα από τον οποίο ξεκινά η λήψη bytes για μετατροπή |

### Return Value

Τιμή ακέραιου χωρίς πρόσημο 16-bit που προκύπτει από τη μετατροπή

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)