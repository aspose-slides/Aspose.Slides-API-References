---
title: Write()
second_title: Aspose.Slides για C++ API Reference
description: Γράφει το καθορισμένο υποσύνολο των byte από τον καθορισμένο πίνακα byte στη ροή.
type: docs
weight: 53
url: /el/system.io/stream/write/
---
## Stream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) μέθοδος

Γράφει το καθορισμένο υποσύνολο των byte από τον καθορισμένο πίνακα byte στη ροή.

```cpp
virtual void System::IO::Stream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ο πίνακας που περιέχει τα byte προς εγγραφή |
| offset | **int32_t** | Ένας δείκτης που ξεκινά από 0 του στοιχείου στο **buffer** στο οποίο αρχίζει το υποσύνολο προς εγγραφή |
| count | **int32_t** | Ο αριθμός των στοιχείων στο υποσύνολο προς εγγραφή |

## Stream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) μέθοδος

Γράφει το καθορισμένο υποσύνολο των byte από τον καθορισμένο πίνακα byte στη ροή.

```cpp
virtual void System::IO::Stream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Η προβολή πίνακα που περιέχει τα byte προς εγγραφή |
| offset | **int32_t** | Ένας δείκτης που ξεκινά από 0 του στοιχείου στο **buffer** στο οποίο αρχίζει το υποσύνολο προς εγγραφή |
| count | **int32_t** | Ο αριθμός των στοιχείων στο υποσύνολο προς εγγραφή |

## Stream::Write(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) μέθοδος

Γράφει το καθορισμένο υποσύνολο των byte από τον καθορισμένο πίνακα byte στη ροή.

```cpp
template<std::size_t> void System::IO::Stream::Write(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| N | Το μέγεθος του στοίβα πίνακα |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | Ο στοίβα πίνακας που περιέχει τα byte προς εγγραφή |
| offset | **int32_t** | Ένας δείκτης που ξεκινά από 0 του στοιχείου στο **buffer** στο οποίο αρχίζει το υποσύνολο προς εγγραφή |
| count | **int32_t** | Ο αριθμός των στοιχείων στο υποσύνολο προς εγγραφή |

## Stream::Write(const System::ReadOnlySpan\<uint8_t\>\&) μέθοδος

Γράφει το καθορισμένο υποσύνολο των byte από το καθορισμένο byte span στη ροή.

```cpp
virtual void System::IO::Stream::Write(const System::ReadOnlySpan<uint8_t> &buffer)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const [System::ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | Το byte span από το οποίο διαβάζονται τα εγγραφόμενα byte |

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [Stream](../)
* Κλάση [ReadOnlySpan](../../../system/readonlyspan/)
* Χώρος ονομάτων [System::IO](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)