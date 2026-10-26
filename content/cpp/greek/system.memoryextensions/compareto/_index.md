---
title: CompareTo()
second_title: Αναφορά API του Aspose.Slides για C++
description: Συγκρίνει δύο περιοχές χαρακτήρων με συγκεκριμένους κανόνες σύγκρισης συμβολοσειρών.
type: docs
weight: 404
url: /el/system.memoryextensions/compareto/
---
## System::MemoryExtensions::CompareTo(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) συνάρτηση

Συγκρίνει δύο περιοχές χαρακτήρων με συγκεκριμένους κανόνες σύγκρισης συμβολοσειρών.

```cpp
int32_t System::MemoryExtensions::CompareTo(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &other, StringComparison comparisonType)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Η πρώτη περιοχή χαρακτήρων |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Η δεύτερη περιοχή χαρακτήρων |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Ο τύπος σύγκρισης συμβολοσειράς που θα εκτελεστεί |

### Τιμή Επιστροφής

Αρνητική τιμή εάν span < other, μηδέν εάν είναι ίσα, θετική εάν span > other

## Δείτε επίσης

* Απαρίθμηση [StringComparison](../../system/stringcomparison/)
* Κλάση [ReadOnlySpan](../../system/readonlyspan/)
* Χώρος ονομάτων [System::MemoryExtensions](../)
* Βιβλιοθήκη [Aspose.Slides](../../)