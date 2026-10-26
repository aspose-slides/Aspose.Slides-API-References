---
title: TrimEnd()
second_title: Aspose.Slides για C++ API Αναφορά
description: Κόβει το καθορισμένο στοιχείο από το τέλος ενός typed span.
type: docs
weight: 378
url: /el/system.memoryextensions/trimend/
---
## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const T\&) λειτουργία

Κόβει το καθορισμένο στοιχείο από το τέλος ενός typed span.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const T &trimElement)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span προς κοπή |
| trimElement | const T\& | Το στοιχείο προς κοπή |

### Τιμή επιστροφής

Ένα νέο span με το καθορισμένο στοιχείο που έχει κοπεί από το τέλος

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const T\&) λειτουργία

Κόβει το καθορισμένο στοιχείο από το τέλος ενός μεταβλητού typed span.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const T &trimElement)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Το μεταβλητό span προς κοπή |
| trimElement | const T\& | Το στοιχείο προς κοπή |

### Τιμή επιστροφής

Ένα νέο span με το καθορισμένο στοιχείο που έχει κοπεί από το τέλος

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) λειτουργία

Κόβει τα καθορισμένα στοιχεία από το τέλος ενός typed span.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Το span προς κοπή |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Τα στοιχεία προς κοπή |

### Τιμή επιστροφής

Ένα νέο span με τα καθορισμένα στοιχεία που έχουν κοπεί από το τέλος

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const ReadOnlySpan\<T\>\&) λειτουργία

Κόβει τα καθορισμένα στοιχεία από το τέλος ενός μεταβλητού typed span.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων στο span |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Το μεταβλητό span προς κοπή |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Τα στοιχεία προς κοπή |

### Τιμή επιστροφής

Ένα νέο span με τα καθορισμένα στοιχεία που έχουν κοπεί από το τέλος

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&) λειτουργία

Κόβει χαρακτήρες λευκού διαστήματος από το τέλος ενός character span.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Το character span προς κοπή |

### Τιμή επιστροφής

Ένα νέο span με λευκούς χαρακτήρες που έχουν κοπεί από το τέλος

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&) λειτουργία

Κόβει χαρακτήρες λευκού διαστήματος από το τέλος ενός μεταβλητού character span.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Το μεταβλητό character span προς κοπή |

### Τιμή επιστροφής

Ένα νέο span με λευκούς χαρακτήρες που έχουν κοπεί από το τέλος

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, char16_t) λειτουργία

Κόβει τον καθορισμένο χαρακτήρα από το τέλος ενός character span.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Το character span προς κοπή |
| trimchar | char16_t | Ο χαρακτήρας προς κοπή |

### Τιμή επιστροφής

Ένα νέο span με τον καθορισμένο χαρακτήρα που έχει κοπεί από το τέλος

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, char16_t) λειτουργία

Κόβει τον καθορισμένο χαρακτήρα από το τέλος ενός μεταβλητού character span.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, char16_t trimchar)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Το μεταβλητό character span προς κοπή |
| trimchar | char16_t | Ο χαρακτήρας προς κοπή |

### Τιμή επιστροφής

Ένα νέο span με τον καθορισμένο χαρακτήρα που έχει κοπεί από το τέλος

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) λειτουργία

Κόβει τους καθορισμένους χαρακτήρες από το τέλος ενός character span.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimChars)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Το character span προς κοπή |
| trimChars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Οι χαρακτήρες προς κοπή |

### Τιμή επιστροφής

Ένα νέο span με τους καθορισμένους χαρακτήρες που έχουν κοπεί από το τέλος

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) λειτουργία

Κόβει τους καθορισμένους χαρακτήρες από το τέλος ενός μεταβλητού character span.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Το μεταβλητό character span προς κοπή |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Οι χαρακτήρες προς κοπή |

### Τιμή επιστροφής

Ένα νέο span με τους καθορισμένους χαρακτήρες που έχουν κοπεί από το τέλος

## Δείτε επίσης

* Τάξη [ReadOnlySpan](../../system/readonlyspan/)
* Τάξη [Span](../../system/span/)
* Χώρος ονομάτων [System::MemoryExtensions](../)
* Βιβλιοθήκη [Aspose.Slides](../../)