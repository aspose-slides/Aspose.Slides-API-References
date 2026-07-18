---
title: Read()
second_title: Αναφορά API του Aspose.Slides για C++
description: Αν η λειτουργία περιτύλιξης είναι δυαδική, διαβάζει τον καθορισμένο αριθμό bytes από τη ροή, διαφορετικά διαβάζει τον καθορισμένο αριθμό χαρακτήρων και τους μετατρέπει σε τύπο uint8_t. Γράφει το αποτέλεσμα της ανάγνωσης στον καθορισμένο πίνακα byte. Δεν υποστηρίζεται!
type: docs
weight: 66
url: /el/system.io/basicstdostreamwrapper/read/
---
## BasicSTDOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) μέθοδος


Αν η λειτουργία περιτυλίγματος είναι δυαδική, διαβάζει τον καθορισμένο αριθμό bytes από τη ροή, διαφορετικά διαβάζει τον καθορισμένο αριθμό χαρακτήρων και τους μετατρέπει σε τύπο **uint8_t**. Γράφει το αποτέλεσμα της ανάγνωσης στον καθορισμένο πίνακα byte. Δεν υποστηρίζεται!

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ο πίνακας byte για να γράψετε τα αναγνωσμένα bytes |
| offset | **int32_t** | Θέση που ξεκινά από 0 στο **buffer** για να αρχίσει η εγγραφή |
| count | **int32_t** | Ο αριθμός των bytes προς ανάγνωση |

### Τιμή επιστροφής

Αριθμός bytes ή χαρακτήρων που διαβάστηκαν

## BasicSTDOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) μέθοδος


Διαβάζει τον καθορισμένο αριθμό bytes από τη ροή και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Η προβολή πίνακα byte για να γράψετε τα αναγνωσμένα bytes |
| offset | **int32_t** | Θέση που ξεκινά από 0 στο **buffer** για να αρχίσει η εγγραφή |
| count | **int32_t** | Ο αριθμός των bytes προς ανάγνωση |

### Τιμή επιστροφής

Ο αριθμός των bytes που διαβάστηκαν

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [BasicSTDOStreamWrapper](../)
* Χώρος ονομάτων [System::IO](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)