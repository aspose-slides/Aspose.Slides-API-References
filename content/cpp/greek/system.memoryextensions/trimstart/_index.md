---
title: TrimStart()
second_title: Αναφορά API του Aspose.Slides για C++
description: Αφαιρεί το καθορισμένο στοιχείο από την αρχή ενός τυποποιημένου span.
type: docs
weight: 391
url: /el/system.memoryextensions/trimstart/
---
## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const T\&) συνάρτηση

Αφαίρεση του συγκεκριμένου στοιχείου από την αρχή ενός τυποποιημένου span.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const T &trimElement)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span προς αφαίρεση |
| trimElement | const T\& | Το στοιχείο προς αφαίρεση |

### Τιμή επιστροφής

Ένα νέο span με το συγκεκριμένο στοιχείο αφαιρεμένο από την αρχή

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const T\&) συνάρτηση

Αφαίρεση του συγκεκριμένου στοιχείου από την αρχή ενός μεταβλητού τυποποιημένου span.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const T &trimElement)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Το μεταβλητό span προς αφαίρεση |
| trimElement | const T\& | Το στοιχείο προς αφαίρεση |

### Τιμή επιστροφής

Ένα νέο span με το συγκεκριμένο στοιχείο αφαιρεμένο από την αρχή

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) συνάρτηση

Αφαίρεση των συγκεκριμένων στοιχείων από την αρχή ενός τυποποιημένου span.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span προς αφαίρεση |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Τα στοιχεία προς αφαίρεση |

### Τιμή επιστροφής

Ένα νέο span με τα συγκεκριμένα στοιχεία αφαιρεμένα από την αρχή

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const ReadOnlySpan\<T\>\&) συνάρτηση

Αφαίρεση των συγκεκριμένων στοιχείων από την αρχή ενός μεταβλητού τυποποιημένου span.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Το μεταβλητό span προς αφαίρεση |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Τα στοιχεία προς αφαίρεση |

### Τιμή επιστροφής

Ένα νέο span με τα συγκεκριμένα στοιχεία αφαιρεμένα από την αρχή

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&) συνάρτηση

Αφαίρεση λευκών χαρακτήρων από την αρχή ενός span χαρακτήρων.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Το span χαρακτήρων προς αφαίρεση |

### Τιμή επιστροφής

Ένα νέο span με λευκούς χαρακτήρες αφαιρεμένους από την αρχή

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&) συνάρτηση

Αφαίρεση λευκών χαρακτήρων από την αρχή ενός μεταβλητού span χαρακτήρων.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Το μεταβλητό span χαρακτήρων προς αφαίρεση |

### Τιμή επιστροφής

Ένα νέο span με λευκούς χαρακτήρες αφαιρεμένους από την αρχή

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, char16_t) συνάρτηση

Αφαίρεση του συγκεκριμένου χαρακτήρα από την αρχή ενός span χαρακτήρων.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Το span χαρακτήρων προς αφαίρεση |
| trimchar | char16_t | Ο χαρακτήρας προς αφαίρεση |

### Τιμή επιστροφής

Ένα νέο span με τον συγκεκριμένο χαρακτήρα αφαιρεμένο από την αρχή

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, char16_t) συνάρτηση

Αφαίρεση του συγκεκριμένου χαρακτήρα από την αρχή ενός μεταβλητού span χαρακτήρων.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, char16_t trimchar)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Το μεταβλητό span χαρακτήρων προς αφαίρεση |
| trimchar | char16_t | Ο χαρακτήρας προς αφαίρεση |

### Τιμή επιστροφής

Ένα νέο span με τον συγκεκριμένο χαρακτήρα αφαιρεμένο από την αρχή

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) συνάρτηση

Αφαίρεση των συγκεκριμένων χαρακτήρων από την αρχή ενός span χαρακτήρων.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Το span χαρακτήρων προς αφαίρεση |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Οι χαρακτήρες προς αφαίρεση |

### Τιμή επιστροφής

Ένα νέο span με τους συγκεκριμένους χαρακτήρες αφαιρεμένους από την αρχή

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) συνάρτηση

Αφαίρεση των συγκεκριμένων χαρακτήρων από την αρχή ενός μεταβλητού span χαρακτήρων.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Το μεταβλητό span χαρακτήρων προς αφαίρεση |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Οι χαρακτήρες προς αφαίρεση |

### Τιμή επιστροφής

Ένα νέο span με τους συγκεκριμένους χαρακτήρες αφαιρεμένους από την αρχή

## Δείτε επίσης

* Κλάση [ReadOnlySpan](../../system/readonlyspan/)
* Κλάση [Span](../../system/span/)
* Ονομαχώρος [System::MemoryExtensions](../)
* Βιβλιοθήκη [Aspose.Slides](../../)