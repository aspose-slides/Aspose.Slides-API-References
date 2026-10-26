---
title: Overlaps()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει εάν δύο ReadOnlySpans επικαλύπτονται στη μνήμη χωρίς να υπολογίζει τη μετατόπιση.
type: docs
weight: 274
url: /el/system.memoryextensions/overlaps/
---
## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Καθορίζει αν δύο ReadOnlySpans επικαλύπτονται στη μνήμη χωρίς να υπολογίζει τη μετατόπιση.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | Ο τύπος των στοιχείων στα spans |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το πρώτο span για έλεγχο επικάλυψης |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το δεύτερο span για έλεγχο επικάλυψης |

### Τιμή επιστροφής

true εάν τα spans μοιράζονται κοινές θέσεις μνήμης, false διαφορετικά

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Καθορίζει αν ένα [Span](../../system/span/) και [ReadOnlySpan](../../system/readonlyspan/) επικαλύπτονται στη μνήμη χωρίς να υπολογίζει τη μετατόπιση.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | Ο τύπος των στοιχείων στα spans |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το [Span](../../system/span/) για έλεγχο επικάλυψης |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το [ReadOnlySpan](../../system/readonlyspan/) για έλεγχο επικάλυψης |

### Τιμή επιστροφής

true εάν τα spans μοιράζονται κοινές θέσεις μνήμης, false διαφορετικά

## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) function

Καθορίζει αν δύο ReadOnlySpans επικαλύπτονται στη μνήμη και υπολογίζει τη μετατόπιση.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```

### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | Ο τύπος των στοιχείων στα spans |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το πρώτο span για έλεγχο επικάλυψης |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το δεύτερο span για έλεγχο επικάλυψης |
| elementOffset | **int32_t**\& | Παράμετρος εξόδου που λαμβάνει τη μετατόπιση μεταξύ των spans εφόσον επικαλύπτονται |

### Τιμή επιστροφής

true εάν τα spans μοιράζονται κοινές θέσεις μνήμης, false διαφορετικά

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) function

Καθορίζει αν ένα [Span](../../system/span/) και [ReadOnlySpan](../../system/readonlyspan/) επικαλύπτονται στη μνήμη και υπολογίζει τη μετατόπιση.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```

### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | Ο τύπος των στοιχείων στα spans |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Το [Span](../../system/span/) για έλεγχο επικάλυψης |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το [ReadOnlySpan](../../system/readonlyspan/) για έλεγχο επικάλυψης |
| elementOffset | **int32_t**\& | Παράμετρος εξόδου που λαμβάνει τη μετατόπιση μεταξύ των spans εφόσον επικαλύπτονται |

### Τιμή επιστροφής

true εάν τα spans μοιράζονται κοινές θέσεις μνήμης, false διαφορετικά

## Δείτε επίσης

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)