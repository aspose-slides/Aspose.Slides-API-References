---
title: ReadLines()
second_title: Αναφορά API του Aspose.Slides για C++
description: Διαβάζει το περιεχόμενο του καθορισμένου αρχείου κειμένου γραμμή προς γραμμή χρησιμοποιώντας την καθορισμένη κωδικοποίηση χαρακτήρων και επιστρέφει μια συλλογή συμβολοσειρών όπου η καθεμία αντιπροσωπεύει μία μόνο γραμμή του περιεχομένου του αρχείου.
type: docs
weight: 326
url: /el/system.io/file/readlines/
---
## File::ReadLines(const String\&, const EncodingPtr\&) μέθοδος


Διαβάζει το περιεχόμενο του καθορισμένου αρχείου κειμένου γραμμή προς γραμμή χρησιμοποιώντας την καθορισμένη κωδικοποίηση χαρακτήρων και επιστρέφει μια συλλογή συμβολοσειρών όπου η καθεμία αντιπροσωπεύει μία μόνο γραμμή του περιεχομένου του αρχείου.

```cpp
static SharedPtr<Collections::Generic::IEnumerable<String>> System::IO::File::ReadLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Η διαδρομή του αρχείου προς ανάγνωση |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Η κωδικοποίηση χαρακτήρων που θα χρησιμοποιηθεί |

### Τιμή επιστροφής

Μία συλλογή συμβολοσειρών που αντιπροσωπεύει το περιεχόμενο του καθορισμένου αρχείου

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Κλάση [IEnumerable](../../../system.collections.generic/ienumerable/)
* Κλάση [String](../../../system/string/)
* Κλάση [File](../)
* Χώρος ονομάτων [System::IO](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)