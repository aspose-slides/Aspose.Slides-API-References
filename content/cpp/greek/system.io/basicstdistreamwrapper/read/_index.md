---
title: Read()
second_title: Αναφορά API Aspose.Slides για C++
description: Εάν η λειτουργία περιτύλιξης είναι δυαδική, διαβάζει τον καθορισμένο αριθμό bytes από τη ροή, διαφορετικά διαβάζει τον καθορισμένο αριθμό χαρακτήρων και τους μετατρέπει σε τύπο uint8_t. Γράφει το αποτέλεσμα της ανάγνωσης στον καθορισμένο πίνακα byte.
type: docs
weight: 66
url: /el/system.io/basicstdistreamwrapper/read/
---
## BasicSTDIStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Αν η λειτουργία περιτύλιξης είναι δυαδική, διαβάζει τον καθορισμένο αριθμό bytes από τη ροή, διαφορετικά διαβάζει τον καθορισμένο αριθμό χαρακτήρων και τους μετατρέπει στον τύπο **uint8_t**. Γράφει το αποτέλεσμα της ανάγνωσης στον καθορισμένο πίνακα byte.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ο πίνακας byte στον οποίο θα γραφτούν τα διαβασμένα bytes |
| offset | **int32_t** | Μία θέση με βάση το 0 στο **buffer** από την οποία θα αρχίσει η εγγραφή |
| count | **int32_t** | Ο αριθμός των bytes που θα διαβαστούν |

### Τιμή Επιστροφής

Αριθμός bytes ή χαρακτήρων που διαβάστηκαν

## BasicSTDIStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Διαβάζει τον καθορισμένο αριθμό bytes από τη ροή και τους γράφει στον καθορισμένο πίνακα byte.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Η προβολή πίνακα byte στην οποία θα γραφτούν τα διαβασμένα bytes |
| offset | **int32_t** | Μία θέση με βάση το 0 στο **buffer** από την οποία θα αρχίσει η εγγραφή |
| count | **int32_t** | Ο αριθμός των bytes που θα διαβαστούν |

### Τιμή Επιστροφής

Αριθμός bytes που διαβάστηκαν

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BasicSTDIStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)