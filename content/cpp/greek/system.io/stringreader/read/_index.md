---
title: Read()
second_title: Αναφορά API Aspose.Slides για C++
description: Διαβάζει έναν μόνο χαρακτήρα από τη ροή.
type: docs
weight: 40
url: /el/system.io/stringreader/read/
---
## StringReader::Read() μέθοδος

Διαβάζει έναν μόνο χαρακτήρα από τη ροή.

```cpp
virtual int System::IO::StringReader::Read() override
```

### Τιμή Επιστροφής

Ένας διαβασμένος χαρακτήρας ή -1 εάν δεν διαβαστεί κανένας χαρακτήρας

## StringReader::Read(ArrayPtr\<char_t\>, int, int) μέθοδος

Διαβάζει τον καθορισμένο αριθμό χαρακτήρων από τη ροή στον καθορισμένο πίνακα χαρακτήρων, αρχίζοντας από τη καθορισμένη θέση.

```cpp
virtual int System::IO::StringReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Ο πίνακας χαρακτήρων στον οποίο θα γραφτούν οι χαρακτήρες που διαβάστηκαν από τη ροή |
| index | int | Ένα μηδενικής βάσης δείκτης στο **buffer** από όπου θα ξεκινήσει η εγγραφή |
| count | int | Ο αριθμός των χαρακτήρων που θα διαβαστούν από τη ροή |

### Τιμή Επιστροφής

Ο αριθμός των χαρακτήρων που διαβάστηκαν από τη ροή

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StringReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)