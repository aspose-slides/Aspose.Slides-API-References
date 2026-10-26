---
title: Read()
second_title: Aspose.Slides για C++ Αναφορά API
description: Διαβάζει τον καθορισμένο αριθμό byte από τη ροή και τα γράφει στον καθορισμένο πίνακα byte.
type: docs
weight: 391
url: /el/system.net.security/sslstream/read/
---
## SslStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) μέθοδος

Διαβάζει τον καθορισμένο αριθμό byte από τη ροή και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
int32_t System::Net::Security::SslStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ο πίνακας byte στον οποίο θα γραφούν τα διαβασμένα byte |
| offset | **int32_t** | Μια θέση που ξεκινά από 0 στο **buffer** για να αρχίσει η εγγραφή |
| count | **int32_t** | Ο αριθμός των byte προς ανάγνωση |

### Τιμή Επιστροφής

Ο αριθμός των byte που διαβάστηκαν

## SslStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) μέθοδος

Διαβάζει τον καθορισμένο αριθμό byte από τη ροή και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
int32_t System::Net::Security::SslStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Ο πίνακας byte στον οποίο θα γραφούν τα διαβασμένα byte |
| offset | **int32_t** | Μια θέση που ξεκινά από 0 στο **buffer** για να αρχίσει η εγγραφή |
| count | **int32_t** | Ο αριθμός των byte προς ανάγνωση |

### Τιμή Επιστροφής

Ο αριθμός των byte που διαβάστηκαν

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [SslStream](../)
* Χώρος ονομάτων [System::Net::Security](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)