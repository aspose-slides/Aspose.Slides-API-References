---
title: FromBase64CharArray()
second_title: Aspose.Slides για C++ Αναφορά API
description: Αποκωδικοποιεί δεδομένα κωδικοποιημένα σε base-64 που αναπαρίστανται ως εύρος σε έναν πίνακα χαρακτήρων Unicode.
type: docs
weight: 53
url: /el/system/convert/frombase64chararray/
---
## Convert::FromBase64CharArray(const ArrayPtr\<char_t\>\&, int, int) μέθοδος

Αποκωδικοποιεί δεδομένα κωδικοποιημένα σε base-64 που αναπαρίστανται ως εύρος σε έναν πίνακα χαρακτήρων Unicode.

```cpp
static ArrayPtr<uint8_t> System::Convert::FromBase64CharArray(const ArrayPtr<char_t> &in_array, int offset, int length)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Ο πίνακας που περιέχει τα δεδομένα προς αποκωδικοποίηση |
| offset | int | Η θέση στον πίνακα εισόδου όπου αρχίζει το εύρος που θα αποκωδικοποιηθεί |
| length | int | Το μήκος του εύρους που θα αποκωδικοποιηθεί |

### Τιμή Επιστροφής

Πίνακας byte που περιέχει τα αποκωδικοποιημένα δεδομένα

## Δείτε επίσης

* Typedef [ArrayPtr](../../arrayptr/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)