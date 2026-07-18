---
title: ReadAllLines()
second_title: Αναφορά API Aspose.Slides για C++
description: Διαβάζει το περιεχόμενο του συγκεκριμένου αρχείου κειμένου γραμμή προς γραμμή σε έναν πίνακα συμβολοσειρών χρησιμοποιώντας την καθορισμένη κωδικοποίηση χαρακτήρων.
type: docs
weight: 300
url: /el/system.io/file/readalllines/
---
## File::ReadAllLines(const String\&, const EncodingPtr\&) μέθοδος


Διαβάζει το περιεχόμενο του συγκεκριμένου αρχείου κειμένου γραμμή προς γραμμή σε έναν πίνακα συμβολοσειρών χρησιμοποιώντας την καθορισμένη κωδικοποίηση χαρακτήρων.

```cpp
static ArrayPtr<String> System::IO::File::ReadAllLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Η διαδρομή του αρχείου για ανάγνωση |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Η κωδικοποίηση χαρακτήρων προς χρήση |

### Τιμή Επιστροφής

Ένας πίνακας συμβολοσειρών, κάθε στοιχείο του οποίου αντιπροσωπεύει μια μεμονωμένη γραμμή από το καθορισμένο αρχείο

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)