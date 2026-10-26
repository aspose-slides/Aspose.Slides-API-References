---
title: ToBase64CharArray()
second_title: Aspose.Slides για C++ Αναφορά API
description: Το Base-64 κωδικοποιεί μια περιοχή στοιχείων στον καθορισμένο πίνακα byte και αποθηκεύει τα κωδικοποιημένα δεδομένα ως έναν πίνακα χαρακτήρων Unicode.
type: docs
weight: 27
url: /el/system/convert/tobase64chararray/
---
## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char16_t\>\&, int, bool) μέθοδος

Το Base-64 κωδικοποιεί μία περιοχή στοιχείων στον καθορισμένο πίνακα bytes και αποθηκεύει τα κωδικοποιημένα δεδομένα ως έναν πίνακα χαρακτήρων Unicode.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char16_t> &out_array, int offset_out, bool insert_line_breaks=false)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Ο πίνακας των bytes που περιέχει την περιοχή των στοιχείων για κωδικοποίηση |
| offset_in | int | Ένας δείκτης ενός στοιχείου στον πίνακα εισόδου όπου αρχίζει η περιοχή που θα κωδικοποιηθεί |
| length | int | Το μήκος της περιοχής των στοιχείων για κωδικοποίηση |
| out_array | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | Μια σταθερή αναφορά στον πίνακα εξόδου στον οποίο θα τοποθετηθούν τα παραγόμενα δεδομένα |
| offset_out | int | Ένας δείκτης στον πίνακα εξόδου όπου θα ξεκινήσει η τοποθέτηση των παραγόμενων δεδομένων |
| insert_line_breaks | **bool** | Καθορίζει αν οι χαρακτήρες αλλαγής γραμμής θα εισαχθούν στον πίνακα εξόδου μετά από κάθε 76 χαρακτήρες base-64 |

### Τιμή Επιστροφής

Ο αριθμός των χαρακτήρων που γράφτηκαν στον πίνακα εξόδου

## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char_t\>\&, int, Base64FormattingOptions) μέθοδος

Το Base-64 κωδικοποιεί μία περιοχή στοιχείων στον καθορισμένο πίνακα bytes και αποθηκεύει τα κωδικοποιημένα δεδομένα ως έναν πίνακα χαρακτήρων Unicode.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char_t> &out_array, int offset_out, Base64FormattingOptions options)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Ο πίνακας των bytes που περιέχει την περιοχή των στοιχείων για κωδικοποίηση |
| offset_in | int | Ένας δείκτης ενός στοιχείου στον πίνακα εισόδου όπου αρχίζει η περιοχή που θα κωδικοποιηθεί |
| length | int | Το μήκος της περιοχής των στοιχείων για κωδικοποίηση |
| out_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Μια σταθερή αναφορά στον πίνακα εξόδου στον οποίο θα τοποθετηθούν τα παραγόμενα δεδομένα |
| offset_out | int | Ένας δείκτης στον πίνακα εξόδου όπου θα ξεκινήσει η τοποθέτηση των παραγόμενων δεδομένων |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Καθορίζει τις επιλογές μορφοποίησης των base-64 κωδικοποιημένων δεδομένων |

### Τιμή Επιστροφής

Ο αριθμός των χαρακτήρων που γράφτηκαν στον πίνακα εξόδου

## Δείτε επίσης

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)