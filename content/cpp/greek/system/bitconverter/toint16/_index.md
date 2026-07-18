---
title: ToInt16()
second_title: Aspose.Slides για C++ API Αναφορά
description: Μετατρέπει δύο byte από τον καθορισμένο πίνακα, αρχίζοντας από τον καθορισμένο δείκτη, σε τιμή ακέραιου 16-bit.
type: docs
weight: 53
url: /el/system/bitconverter/toint16/
---
## BitConverter::ToInt16(const System::ArrayPtr\<uint8_t\>\&, int) method


Μετατρέπει δύο byte από τον καθορισμένο πίνακα, αρχίζοντας από το καθορισμένο δείκτη, σε τιμή ακέραιου 16-bit.

```cpp
static int16_t System::BitConverter::ToInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) that contains bytes to convert |
| startIndex | int | Index in the array at which to start taking bytes for conversion |

### Τιμή Επιστροφής

16-bit integer value resulting from conversion

## BitConverter::ToInt16(const System::Details::ArrayView\<uint8_t\>\&, int) method


Μετατρέπει δύο byte από τον καθορισμένο πίνακα, αρχίζοντας από το καθορισμένο δείκτη, σε τιμή ακέραιου 16-bit.

```cpp
static int16_t System::BitConverter::ToInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView that contains bytes to convert |
| startIndex | int | Index in the array at which to start taking bytes for conversion |

### Τιμή Επιστροφής

16-bit integer value resulting from conversion

## Δείτε επίσης

* Typedef [ArrayPtr](../../arrayptr/)
* Κλάση [BitConverter](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)