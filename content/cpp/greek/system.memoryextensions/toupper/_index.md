---
title: ToUpper()
second_title: Αναφορά API του Aspose.Slides για C++
description: Μετατρέπει χαρακτήρες σε κεφαλαία χρησιμοποιώντας την καθορισμένη πολιτιστική ρύθμιση.
type: docs
weight: 469
url: /el/system.memoryextensions/toupper/
---
## System::MemoryExtensions::ToUpper(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) συνάρτηση

Μετατρέπει χαρακτήρες σε κεφαλαία χρησιμοποιώντας την καθορισμένη πολιτιστική ρύθμιση.

```cpp
int32_t System::MemoryExtensions::ToUpper(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Το αρχικό εύρος χαρακτήρων προς μετατροπή |
| destination | [Span](../../system/span/)\<char16_t\>\& | Το εύρος προορισμού για την αποθήκευση των μετατρεπόμενων χαρακτήρων |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | Η πολιτιστική ρύθμιση που θα χρησιμοποιηθεί για τη μετατροπή (nullptr για την τρέχουσα πολιτιστική ρύθμιση) |

### Τιμή Επιστροφής

Αριθμός χαρακτήρων που μετατράπηκαν, ή -1 εάν ο προορισμός είναι πολύ μικρός

## Δείτε επίσης

* Τύπος [SharedPtr](../../system/sharedptr/)
* Κλάση [ReadOnlySpan](../../system/readonlyspan/)
* Κλάση [Span](../../system/span/)
* Κλάση [CultureInfo](../../system.globalization/cultureinfo/)
* Χώρος ονομάτων [System::MemoryExtensions](../)
* Βιβλιοθήκη [Aspose.Slides](../../)