---
title: Read()
second_title: Aspose.Slides για C++ API Αναφορά
description: Διαβάζει τον καθορισμένο αριθμό byte από τη ροή και τα γράφει στον καθορισμένο πίνακα byte.
type: docs
weight: 144
url: /el/system.io/unmanagedmemorystream/read/
---
## UnmanagedMemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) μέθοδος

Διαβάζει τον καθορισμένο αριθμό byte από τη ροή και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ο πίνακας byte στον οποίο θα γραφούν τα αναγνωσμένα byte |
| offset | **int32_t** | Μια θέση με βάση το 0 στο **buffer** για να αρχίσει η εγγραφή |
| count | **int32_t** | Ο αριθμός των byte προς ανάγνωση |

### Τιμή Επιστροφής

Ο αριθμός των byte που διαβάστηκαν

## UnmanagedMemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) μέθοδος

Διαβάζει τον καθορισμένο αριθμό byte από τη ροή και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Η προβολή του πίνακα byte στην οποία θα γραφούν τα αναγνωσμένα byte |
| offset | **int32_t** | Μια θέση με βάση το 0 στο **buffer** για να αρχίσει η εγγραφή |
| count | **int32_t** | Ο αριθμός των byte προς ανάγνωση |

### Τιμή Επιστροφής

Ο αριθμός των byte που διαβάστηκαν

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [UnmanagedMemoryStream](../)
* Χώρος ονομάτων [System::IO](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)