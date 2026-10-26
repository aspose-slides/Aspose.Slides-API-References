---
title: AsSpan()
second_title: Αναφορά API Aspose.Slides για C++
description: Δημιουργεί ένα span από έναν πίνακα.
type: docs
weight: 1
url: /el/system.memoryextensions/asspan/
---
## System::MemoryExtensions::AsSpan(const ArrayPtr\<T\>\&, int32_t, int32_t) συνάρτηση

Δημιουργεί ένα Span από έναν πίνακα.

```cpp
template<typename T> Span<T> System::MemoryExtensions::AsSpan(const ArrayPtr<T> &array, int32_t start=0, int32_t length=-1)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στον array. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | Ο πηγαίος array. |
| start | **int32_t** | Ο αρχικός δείκτης στο array. |
| length | **int32_t** | Το μήκος του span. |

### Τιμή επιστροφής

Span<T> που καλύπτει το συγκεκριμένο τμήμα του array.

## System::MemoryExtensions::AsSpan(const String\&, int32_t, int32_t) συνάρτηση

Δημιουργεί ένα ReadOnlySpan από μια συμβολοσειρά.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::AsSpan(const String &text, int32_t start=0, int32_t length=-1)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | const [String](../../system/string/)\& | Η πηγαία συμβολοσειρά. |
| start | **int32_t** | Ο αρχικός δείκτης στη συμβολοσειρά. |
| length | **int32_t** | Το μήκος του span. |

### Τιμή επιστροφής

ReadOnlySpan<char16_t> που καλύπτει το συγκεκριμένο τμήμα της συμβολοσειράς.

## Δείτε επίσης

* Typedef [ArrayPtr](../../system/arrayptr/)
* Κλάση [Span](../../system/span/)
* Κλάση [ReadOnlySpan](../../system/readonlyspan/)
* Κλάση [String](../../system/string/)
* Χώρος ονομάτων [System::MemoryExtensions](../)
* Βιβλιοθήκη [Aspose.Slides](../../)