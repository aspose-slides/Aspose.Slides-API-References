---
title: Read()
second_title: Αναφορά API του Aspose.Slides για C++
description: Διαβάζει έναν μόνο χαρακτήρα από τη ροή εισόδου.
type: docs
weight: 66
url: /el/system.io/binaryreader/read/
---
## BinaryReader::Read() μέθοδος

Διαβάζει ένα μόνο χαρακτήρα από τη ροή εισόδου.

```cpp
virtual int System::IO::BinaryReader::Read()
```

### Τιμή επιστροφής

Ο χαρακτήρας που διαβάστηκε κωδικοποιείται με κωδικοποίηση UTF-16· αν ο χαρακτήρας που διαβάστηκε αντιπροσωπεύεται από δύο κωδικούς σημείου στην κωδικοποίηση UTF-16, τότε επιστρέφεται μόνο το υψηλό surrogate.

## BinaryReader::Read(ArrayPtr\<uint8_t\>, int, int) μέθοδος

Διαβάζει τον καθορισμένο αριθμό bytes από τη ροή εισόδου και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<uint8_t> buffer, int index, int count)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ο πίνακας byte στον οποίο θα γραφούν τα διαβασμένα bytes |
| index | int | Μία θέση με βάση το 0 στο **buffer** από την οποία θα ξεκινήσει η εγγραφή |
| count | int | Ο αριθμός των bytes που θα διαβαστούν |

### Τιμή επιστροφής

Ο αριθμός των bytes που διαβάστηκαν

## BinaryReader::Read(ArrayPtr\<char_t\>, int, int) μέθοδος

Διαβάζει τον καθορισμένο αριθμό χαρακτήρων από τη ροή εισόδου, τους μετατρέπει σε κωδικοποίηση UTF-16 και γράφει τους προκύπτοντες χαρακτήρες UTF-16 στον καθορισμένο πίνακα χαρακτήρων αρχίζοντας από τη καθορισμένη θέση.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Ο πίνακας χαρακτήρων UTF-16 στον οποίο θα γραφούν οι χαρακτήρες που διαβάστηκαν από τη ροή εισόδου |
| index | int | Μέσο δείκτη με βάση το 0 στο **buffer** από το οποίο θα ξεκινήσει η εγγραφή |
| count | int | Ο αριθμός των χαρακτήρων που θα διαβαστούν από τη ροή |

### Τιμή επιστροφής

Ο αριθμός των χαρακτήρων που διαβάστηκαν από τη ροή εισόδου

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [BinaryReader](../)
* Χώρος ονομάτων [System::IO](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)