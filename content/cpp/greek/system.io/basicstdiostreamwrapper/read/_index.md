---
title: Read()
second_title: Αναφορά API του Aspose.Slides για C++
description: Εάν η λειτουργία περιτύλιξης είναι δυαδική, διαβάζει τον καθορισμένο αριθμό byte από το ρεύμα, διαφορετικά διαβάζει τον καθορισμένο αριθμό χαρακτήρων και τους μετατρέπει σε τύπο uint8_t. Γράφει το αποτέλεσμα της ανάγνωσης στον καθορισμένο πίνακα byte.
type: docs
weight: 66
url: /el/system.io/basicstdiostreamwrapper/read/
---
## BasicSTDIOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) μέθοδος

Αν η λειτουργία περιτύλιξης είναι δυαδική, διαβάζει τον καθορισμένο αριθμό byte από το ρεύμα, διαφορετικά διαβάζει τον καθορισμένο αριθμό χαρακτήρων και τους μετατρέπει σε τύπο **uint8_t**. Γράφει το αποτέλεσμα της ανάγνωσης στον καθορισμένο πίνακα byte.

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ο πίνακας byte στον οποίο θα γράψει τα αναγνωσμένα byte |
| offset | **int32_t** | Μια θέση αρχής 0-βάση στο **buffer** από όπου θα ξεκινήσει η εγγραφή |
| count | **int32_t** | Ο αριθμός των byte που θα διαβαστούν |

### Τιμή Επιστροφής

Αριθμός byte ή χαρακτήρων που διαβάστηκαν

## BasicSTDIOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) μέθοδος

Διαβάζει τον καθορισμένο αριθμό byte από το ρεύμα και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Η προβολή του πίνακα byte στην οποία θα γράψει τα αναγνωσμένα byte |
| offset | **int32_t** | Μια θέση αρχής 0-βάση στο **buffer** από όπου θα ξεκινήσει η εγγραφή |
| count | **int32_t** | Ο αριθμός των byte που θα διαβαστούν |

### Τιμή Επιστροφής

Ο αριθμός των byte που διαβάστηκαν

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [BasicSTDIOStreamWrapper](../)
* Χώρος ονομάτων [System::IO](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)