---
title: Write()
second_title: Αναφορά API Aspose.Slides για C++
description: Γράφει το καθορισμένο υποσύνολο των bytes από τον καθορισμένο πίνακα byte στη ροή.
type: docs
weight: 92
url: /el/system.io/memorystream/write/
---
## MemoryStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

Γράφει το καθορισμένο υποσύνολο των bytes από τον καθορισμένο πίνακα byte στη ροή.

```cpp
void System::IO::MemoryStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ο πίνακας που περιέχει τα bytes προς εγγραφή |
| offset | **int32_t** | Ένας δείκτης με βάση το 0 του στοιχείου στο **buffer** όπου αρχίζει η υποπεριοχή προς εγγραφή |
| count | **int32_t** | Ο αριθμός των στοιχείων στην υποπεριοχή προς εγγραφή |

## MemoryStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

Γράφει το καθορισμένο υποσύνολο των bytes από τον καθορισμένο πίνακα byte στη ροή.

```cpp
void System::IO::MemoryStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Η προβολή του πίνακα που περιέχει τα bytes προς εγγραφή |
| offset | **int32_t** | Ένας δείκτης με βάση το 0 του στοιχείου στο **buffer** όπου αρχίζει η υποπεριοχή προς εγγραφή |
| count | **int32_t** | Ο αριθμός των στοιχείων στην υποπεριοχή προς εγγραφή |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [MemoryStream](../)
* Χώρος ονομάτων [System::IO](../../)
* Library [Aspose.Slides](../../../)