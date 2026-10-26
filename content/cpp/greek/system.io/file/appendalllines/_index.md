---
title: AppendAllLines()
second_title: Aspose.Slides για C++ Αναφορά API
description: Προσθέτει συμβολοσειρές από τη συγκεκριμένη συλλογή συμβολοσειρών στο καθορισμένο αρχείο χρησιμοποιώντας την καθορισμένη κωδικοποίηση, γράφοντας κάθε συμβολοσειρά σε νέα γραμμή. Εάν το καθορισμένο αρχείο δεν υπάρχει, δημιουργείται. Το αρχείο κλείνει μετά τη γραφή όλων των συμβολοσειρών.
type: docs
weight: 1
url: /el/system.io/file/appendalllines/
---
## File::AppendAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) μέθοδος

Προσθέτει συμβολοσειρές από τη συγκεκριμένη συλλογή συμβολοσειρών στο συγκεκριμένο αρχείο χρησιμοποιώντας την καθορισμένη κωδικοποίηση γράφοντας κάθε συμβολοσειρά σε νέα γραμμή. Εάν το καθορισμένο αρχείο δεν υπάρχει, δημιουργείται. Το αρχείο κλείνει μετά τη γραφή όλων των συμβολοσειρών.

```cpp
static void System::IO::File::AppendAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Η διαδρομή του αρχείου στο οποίο θα προσαρτηθούν οι συμβολοσειρές |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | Οι συμβολοσειρές που θα γραφούν στο αρχείο |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Η κωδικοποίηση χαρακτήρων που θα χρησιμοποιηθεί |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [IEnumerable](../../../system.collections.generic/ienumerable/)
* Κλάση [File](../)
* Χώρος ονομάτων [System::IO](../../)
* Library [Aspose.Slides](../../../)