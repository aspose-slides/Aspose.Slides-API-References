---
title: ToByteArray()
second_title: Αναφορά API Aspose.Slides για C++
description: Μετατρέπει τη συμβολοσειρά ή την υποσυμβολοσειρά σε πίνακα byte.
type: docs
weight: 508
url: /el/system/string/tobytearray/
---
## String::ToByteArray(int32_t, int32_t, bool) const μέθοδος


Μετατρέπει τη συμβολοσειρά ή την υποσυμβολοσειρά σε πίνακα bytes.

```cpp
ArrayPtr<uint8_t> System::String::ToByteArray(int32_t startIndex=0, int32_t length=INT32_MAX, bool LE=1) const
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startIndex | **int32_t** | Δείκτης εκκίνησης της υποσυμβολοσειράς. |
| length | **int32_t** | Μήκος της υποσυμβολοσειράς. |
| LE | **bool** | Αν είναι true, κωδικοποιεί τους χαρακτήρες χρησιμοποιώντας μικρή σειρά byte (little endianness); διαφορετικά, χρησιμοποιεί μεγάλη σειρά byte (big endianness). |

### Τιμή Επιστροφής

[Array](../../array/) που περιέχει bytes που αναπαριστούν τους χαρακτήρες της συμβολοσειράς.

## Δείτε επίσης

* Typedef [ArrayPtr](../../arrayptr/)
* Κλάση [String](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)