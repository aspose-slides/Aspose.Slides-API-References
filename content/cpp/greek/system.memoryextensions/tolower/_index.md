---
title: ToLower()
second_title: Aspose.Slides για C++ API Αναφορά
description: Μετατρέπει χαρακτήρες σε πεζά χρησιμοποιώντας την καθορισμένη πολιτιστική ρύθμιση.
type: docs
weight: 443
url: /el/system.memoryextensions/tolower/
---
## System::MemoryExtensions::ToLower(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) συνάρτηση

Μετατρέπει χαρακτήρες σε πεζά χρησιμοποιώντας την καθορισμένη πολιτιστική ρύθμιση.

```cpp
int32_t System::MemoryExtensions::ToLower(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Το τμήμα χαρακτήρων source για μετατροπή |
| destination | [Span](../../system/span/)\<char16_t\>\& | Το τμήμα destination για αποθήκευση των μετατρεπόμενων χαρακτήρων |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | Η πολιτιστική ρύθμιση culture για χρήση στη μετατροπή (nullptr για την τρέχουσα πολιτιστική ρύθμιση) |

## Τιμή Επιστροφής

Αριθμός χαρακτήρων που μετατράπηκαν, ή -1 αν το destination είναι πολύ μικρό

## Δείτε επίσης

* Typedef [SharedPtr](../../system/sharedptr/)
* Κλάση [ReadOnlySpan](../../system/readonlyspan/)
* Κλάση [Span](../../system/span/)
* Κλάση [CultureInfo](../../system.globalization/cultureinfo/)
* Χώρος ονομάτων [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)