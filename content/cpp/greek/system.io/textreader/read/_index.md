---
title: Read()
second_title: Αναφορά API του Aspose.Slides για C++
description: Διαβάζει έναν μόνο χαρακτήρα από τη ροή.
type: docs
weight: 40
url: /el/system.io/textreader/read/
---
## TextReader::Read() method

Διαβάζει ένα μόνο χαρακτήρα από τη ροή.

```cpp
virtual int System::IO::TextReader::Read()
```

### Return Value

Διαβάζει τον χαρακτήρα κωδικοποιημένο με κωδικοποίηση UTF-16· εάν ο διαβασμένος χαρακτήρας αναπαρίσταται από δύο κωδικομεγέθη στην κωδικοποίηση UTF-16, τότε επιστρέφεται μόνο το υψηλό surrogate.

## TextReader::Read(ArrayPtr\<char_t\>, int, int) method

Διαβάζει τον καθορισμένο αριθμό χαρακτήρων από τη ροή και τους γράφει στον καθορισμένο πίνακα χαρακτήρων, αρχίζοντας από τη συγκεκριμένη θέση.

```cpp
virtual int System::IO::TextReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Ο πίνακας χαρακτήρων UTF-16 στον οποίο θα γραφτούν οι χαρακτήρες που διαβάζονται από τη ροή |
| index | int | Ένας δείκτης βάσης 0 στο **buffer** από τον οποίο θα ξεκινήσει η εγγραφή |
| count | int | Ο αριθμός των χαρακτήρων που θα διαβαστούν από τη ροή |

### Return Value

Ο αριθμός των χαρακτήρων που διαβάστηκαν από τη ροή

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [TextReader](../)
* Χώρος ονομάτων [System::IO](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)