---
title: Read()
second_title: Aspose.Slides για C++ Αναφορά API
description: Διαβάζει έναν μόνο χαρακτήρα από τη ροή.
type: docs
weight: 40
url: /el/system.io/streamreader/read/
---
## StreamReader::Read() μέθοδος

Διαβάζει έναν μόνο χαρακτήρα από τη ροή.

```cpp
virtual int System::IO::StreamReader::Read() override
```

### Τιμή Επιστροφής

Διαβάστηκε χαρακτήρας κωδικοποιημένος με κωδικοποίηση UTF-16· εάν ο διαβασμένος χαρακτήρας αντιπροσωπεύεται από δύο codepoints στην κωδικοποίηση UTF-16, τότε επιστρέφεται μόνο το υψηλό surrogate.

## StreamReader::Read(ArrayPtr\<char_t\>, int, int) μέθοδος

Διαβάζει τον καθορισμένο αριθμό χαρακτήρων από τη ροή, τους μετατρέπει σε κωδικοποίηση UTF-16 και γράφει τους προκύπτοντες χαρακτήρες UTF-16 στον καθορισμένο πίνακα χαρακτήρων ξεκινώντας από τη καθορισμένη θέση.

```cpp
virtual int System::IO::StreamReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Ο πίνακας χαρακτήρων UTF-16 στον οποίο θα γραφτούν οι χαρακτήρες που διαβάστηκαν από τη ροή |
| index | int | Ένας δείκτης 0-βάσης στο **buffer** στο οποίο θα αρχίσει η εγγραφή |
| count | int | Ο αριθμός των χαρακτήρων που θα διαβαστούν από τη ροή |

### Τιμή Επιστροφής

Ο αριθμός των χαρακτήρων που διαβάστηκαν από τη ροή

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [StreamReader](../)
* Χώρος ονομάτων [System::IO](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)