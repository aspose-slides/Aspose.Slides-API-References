---
title: Read()
second_title: Αναφορά API Aspose.Slides για C++
description: Διαβάζει τον καθορισμένο αριθμό byte από την υποκείμενη ροή και τα γράφει στον καθορισμένο πίνακα byte.
type: docs
weight: 53
url: /el/system.io/bufferedstream/read/
---
## BufferedStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Διαβάζει τον καθορισμένο αριθμό byte από την υποκείμενη ροή και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ο πίνακας byte στον οποίο γράφονται τα αναγνωσμένα byte |
| offset | **int32_t** | Μία θέση 0-βάση στο **buffer** για την έναρξη εγγραφής |
| count | **int32_t** | Ο αριθμός των byte προς ανάγνωση |

### Επιστρεφόμενη Τιμή

Αριθμός των byte που διαβάστηκαν

## BufferedStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Διαβάζει τον καθορισμένο αριθμό byte από την υποκείμενη ροή και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Ο πίνακας byte στον οποίο γράφονται τα αναγνωσμένα byte |
| offset | **int32_t** | Μία θέση 0-βάση στο **buffer** για την έναρξη εγγραφής |
| count | **int32_t** | Ο αριθμός των byte προς ανάγνωση |

### Επιστρεφόμενη Τιμή

Αριθμός των byte που διαβάστηκαν

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [BufferedStream](../)
* Χώρος ονομάτων [System::IO](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)