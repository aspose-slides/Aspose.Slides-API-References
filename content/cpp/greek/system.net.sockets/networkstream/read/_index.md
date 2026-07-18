---
title: Read()
second_title: Aspose.Slides για C++ Αναφορά API
description: Διαβάζει τον καθορισμένο αριθμό byte από τη ροή και τα γράφει στον καθορισμένο πίνακα byte.
type: docs
weight: 196
url: /el/system.net.sockets/networkstream/read/
---
## NetworkStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) μέθοδος


Διαβάζει τον καθορισμένο αριθμό byte από τη ροή και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ο πίνακας byte όπου θα γραφτούν τα διαβασμένα byte. |
| offset | **int32_t** | Η μετατόπιση σε byte στον καθορισμένο πίνακα. |
| size | **int32_t** | Ο αριθμός των byte που θα διαβαστούν. |

### Τιμή Επιστροφής

Ο αριθμός των διαβασμένων byte.

## NetworkStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) μέθοδος


Διαβάζει τον καθορισμένο αριθμό byte από τη ροή και τα γράφει στην καθορισμένη προβολή πίνακα byte.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Η προβολή πίνακα byte στην οποία θα γραφτούν τα διαβασμένα byte |
| offset | **int32_t** | Μια θέση που ξεκινά από 0 στο **buffer** για την έναρξη της εγγραφής |
| size | **int32_t** | Ο αριθμός των byte που θα διαβαστούν |

### Τιμή Επιστροφής

Ο αριθμός των byte που διαβάστηκαν

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [NetworkStream](../)
* Χώρος ονομάτων [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)