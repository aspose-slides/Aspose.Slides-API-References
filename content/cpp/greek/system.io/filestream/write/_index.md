---
title: Write()
second_title: Αναφορά API του Aspose.Slides για C++
description: Γράφει το καθορισμένο υποσύνολο bytes από τον καθορισμένο πίνακα byte στη ροή.
type: docs
weight: 248
url: /el/system.io/filestream/write/
---
## FileStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) μέθοδος

Γράφει το καθορισμένο υποσύνολο byte από τον καθορισμένο πίνακα byte στη ροή.

```cpp
void System::IO::FileStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ο πίνακας που περιέχει τα byte προς εγγραφή. |
| offset | **int32_t** | Ένας δείκτης με βάση το 0 του στοιχείου στο **buffer** όπου αρχίζει το υποσύνολο προς εγγραφή. |
| count | **int32_t** | Ο αριθμός των στοιχείων στο υποσύνολο προς εγγραφή. |

## FileStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) μέθοδος

Γράφει το καθορισμένο υποσύνολο byte από τον καθορισμένο πίνακα byte στη ροή.

```cpp
void System::IO::FileStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Η προβολή πίνακα που περιέχει τα byte προς εγγραφή. |
| offset | **int32_t** | Ένας δείκτης με βάση το 0 του στοιχείου στο **buffer** όπου αρχίζει το υποσύνολο προς εγγραφή. |
| count | **int32_t** | Ο αριθμός των στοιχείων στο υποσύνολο προς εγγραφή. |

## Δείτε επίσης

* Τύπος [ArrayPtr](../../../system/arrayptr/)
* Κλάση [FileStream](../)
* Χώρος ονομάτων [System::IO](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)