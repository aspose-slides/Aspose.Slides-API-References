---
title: Trim()
second_title: Αναφορά API Aspose.Slides για C++
description: Καθαρίζει το καθορισμένο στοιχείο από τις δύο άκρες ενός typed span.
type: docs
weight: 365
url: /el/system.memoryextensions/trim/
---
## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, T) συνάρτηση


Καθαρώνει το καθορισμένο στοιχείο από τις δύο άκρες ενός typed span.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, T trimElement)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span προς αφαίρεση |
| trimElement | T | Το στοιχείο προς αφαίρεση |

### Τιμή Επιστροφής

A new span with the specified element trimmed from both ends

## System::MemoryExtensions::Trim(Span\<T\>\&, T) συνάρτηση


Καθαρώνει το καθορισμένο στοιχείο από τις δύο άκρες ενός mutable typed span.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, T trimElement)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Το mutable span προς αφαίρεση |
| trimElement | T | Το στοιχείο προς αφαίρεση |

### Τιμή Επιστροφής

A new span with the specified element trimmed from both ends

## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) συνάρτηση


Καθαρώνει τα καθορισμένα στοιχεία από τις δύο άκρες ενός typed span.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span προς αφαίρεση |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Τα στοιχεία προς αφαίρεση |

### Τιμή Επιστροφής

A new span with the specified elements trimmed from both ends

## System::MemoryExtensions::Trim(Span\<T\>\&, const ReadOnlySpan\<T\>\&) συνάρτηση


Καθαρώνει τα καθορισμένα στοιχεία από τις δύο άκρες ενός mutable typed span.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Το mutable span προς αφαίρεση |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Τα στοιχεία προς αφαίρεση |

### Τιμή Επιστροφής

A new span with the specified elements trimmed from both ends

## System::MemoryExtensions::Trim(const ReadOnlySpan\<char16_t\>\&) συνάρτηση


Καθαρώνει τους χαρακτήρες λευκού χώρου από τις δύο άκρες ενός character span.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::Trim(const ReadOnlySpan<char16_t> &span)
```


### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Το character span προς αφαίρεση |

### Τιμή Επιστροφής

A new span with whitespace trimmed from both ends

## System::MemoryExtensions::Trim(Span\<char16_t\>\&) συνάρτηση


Καθαρώνει τους χαρακτήρες λευκού χώρου από τις δύο άκρες ενός mutable character span.

```cpp
Span<char16_t> System::MemoryExtensions::Trim(Span<char16_t> &span)
```


### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Το mutable character span προς αφαίρεση |

### Τιμή Επιστροφής

A new span with whitespace trimmed from both ends

## Δείτε επίσης

* Κλάση [ReadOnlySpan](../../system/readonlyspan/)
* Κλάση [Span](../../system/span/)
* Χώρος ονομάτων [System::MemoryExtensions](../)
* Βιβλιοθήκη [Aspose.Slides](../../)