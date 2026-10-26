---
title: Read()
second_title: Αναφορά API του Aspose.Slides για C++
description: Διαβάζει τον καθορισμένο αριθμό bytes από τη ροή και τους γράφει στον καθορισμένο πίνακα byte.
type: docs
weight: 79
url: /el/system.io/memorystream/read/
---
## MemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) μέθοδος

Διαβάζει τον καθορισμένο αριθμό bytes από τη ροή και τους γράφει στον καθορισμένο πίνακα byte.

```cpp
int32_t System::IO::MemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ο πίνακας byte στον οποίο θα γραφτούν τα διαβασμένα bytes |
| offset | **int32_t** | Μια θέση με βάση το 0 στο **buffer** από την οποία θα ξεκινήσει η εγγραφή |
| count | **int32_t** | Ο αριθμός των bytes προς ανάγνωση |

### Τιμή Επιστροφής

Ο αριθμός των διαβασμένων bytes

## MemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) μέθοδος

Διαβάζει τον καθορισμένο αριθμό bytes από τη ροή και τους γράφει στην καθορισμένη προβολή πίνακα byte.

```cpp
int32_t System::IO::MemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Η προβολή του πίνακα byte στην οποία θα γραφτούν τα διαβασμένα bytes |
| offset | **int32_t** | Μια θέση με βάση το 0 στο **buffer** από την οποία θα ξεκινήσει η εγγραφή |
| count | **int32_t** | Ο αριθμός των bytes προς ανάγνωση |

### Τιμή Επιστροφής

Ο αριθμός των διαβασμένων bytes

## Δείτε επίσης

* Τύπος [ArrayPtr](../../../system/arrayptr/)
* Κλάση [MemoryStream](../)
* Χώρος ονομάτων [System::IO](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)