---
title: Read()
second_title: Aspose.Slides για C++ API Αναφορά
description: Διαβάζει τον καθορισμένο αριθμό bytes από τη ροή και τα γράφει στον καθορισμένο πίνακα byte.
type: docs
weight: 27
url: /el/system.io/stream/read/
---
## Stream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) μέθοδος

Διαβάζει τον καθορισμένο αριθμό bytes από τη ροή και τα γράφει στον καθορισμένο πίνακα bytes.

```cpp
virtual int32_t System::IO::Stream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | The byte array to write the read bytes to |
| offset | **int32_t** | A 0-based position in **buffer** to start writing at |
| count | **int32_t** | The number of bytes to read |

### Τιμή Επιστροφής

Ο αριθμός των bytes που διαβάστηκαν

## Stream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) μέθοδος

Διαβάζει τον καθορισμένο αριθμό bytes από τη ροή και τα γράφει στον καθορισμένο πίνακα bytes.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | The byte array view to write the read bytes to |
| offset | **int32_t** | A 0-based position in **buffer** to start writing at |
| count | **int32_t** | The number of bytes to read |

### Τιμή Επιστροφής

Ο αριθμός των bytes που διαβάστηκαν

## Stream::Read(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) μέθοδος

Διαβάζει τον καθορισμένο αριθμό bytes από τη ροή και τα γράφει στον καθορισμένο πίνακα bytes.

```cpp
template<std::size_t> int32_t System::IO::Stream::Read(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| N | Το μέγεθος του πίνακα στη στοίβα |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | The byte stack array to write the read bytes to |
| offset | **int32_t** | A 0-based position in **buffer** to start writing at |
| count | **int32_t** | The number of bytes to read |

### Τιμή Επιστροφής

Ο αριθμός των bytes που διαβάστηκαν

## Stream::Read(const System::Span\<uint8_t\>\&) μέθοδος

Διαβάζει τον καθορισμένο αριθμό bytes από τη ροή και τα γράφει στο καθορισμένο byte span.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Span<uint8_t> &buffer)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const [System::Span](../../../system/span/)\<**uint8_t**\>\& | The byte span to write the read bytes to |

### Τιμή Επιστροφής

Ο αριθμός των bytes που διαβάστηκαν

## Δείτε επίσης

* Τυπική δήλωση [ArrayPtr](../../../system/arrayptr/)
* Κλάση [Stream](../)
* Κλάση [Span](../../../system/span/)
* Χώρος ονομάτων [System::IO](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)