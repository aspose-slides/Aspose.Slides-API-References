---
title: Read()
second_title: Αναφορά API Aspose.Slides για C++
description: Διαβάζει τον καθορισμένο αριθμό bytes από το ρεύμα και τα γράφει στον καθορισμένο πίνακα bytes.
type: docs
weight: 183
url: /el/system.io/filestream/read/
---
## FileStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) μέθοδος


Διαβάζει τον καθορισμένο αριθμό bytes από το ρεύμα και τα γράφει στον καθορισμένο πίνακα bytes.

```cpp
int32_t System::IO::FileStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Παράμετρα

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ο πίνακας bytes στον οποίο θα γραφτούν τα διαβασμένα bytes. |
| offset | **int32_t** | Μία θέση με βάση το 0 στο **buffer** για να αρχίσει η εγγραφή. |
| count | **int32_t** | Ο αριθμός των bytes προς ανάγνωση. |

### Τιμή Επιστροφής

Ο αριθμός των bytes που διαβάστηκαν.

## FileStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) μέθοδος


Διαβάζει τον καθορισμένο αριθμό bytes από το ρεύμα και τα γράφει στην καθορισμένη προβολή πίνακα bytes.

```cpp
int32_t System::IO::FileStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Παράμετρα

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Η προβολή πίνακα bytes στην οποία θα γραφτούν τα διαβασμένα bytes. |
| offset | **int32_t** | Μία θέση με βάση το 0 στο **buffer** για να αρχίσει η εγγραφή. |
| count | **int32_t** | Ο αριθμός των bytes προς ανάγνωση. |

### Τιμή Επιστροφής

Ο αριθμός των bytes που διαβάστηκαν.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [FileStream](../)
* Χώρος ονομάτων [System::IO](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)