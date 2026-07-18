---
title: WriteAllLines()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Δημιουργεί ένα νέο αρχείο κειμένου ή αντικαθιστά το υπάρχον και γράφει όλες τις συμβολοσειρές από την καθορισμένη συλλογή συμβολοσειρών που μπορεί να αναπαραχθεί σε αυτό, κάθε συμβολοσειρά σε νέα γραμμή, χρησιμοποιώντας την καθορισμένη κωδικοποίηση.
type: docs
weight: 456
url: /el/system.io/file/writealllines/
---
## File::WriteAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) μέθοδος

Δημιουργεί ένα νέο αρχείο κειμένου ή αντικαθιστά το υπάρχον και γράφει όλες τις συμβολοσειρές από τη συγκεκριμένη συλλογή συμβολοσειρών που μπορεί να αναπαραχθεί, κάθε συμβολοσειρά σε νέα γραμμή, χρησιμοποιώντας την καθορισμένη κωδικοποίηση.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Το αρχείο που θα δημιουργηθεί ή θα αντικατασταθεί |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | Μία συλλογή συμβολοσειρών που μπορεί να αναπαραχθεί |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Η κωδικοποίηση χαρακτήρων που θα χρησιμοποιηθεί |

## File::WriteAllLines(const String\&, const ArrayPtr\<String\>\&, const EncodingPtr\&) μέθοδος

Δημιουργεί ένα νέο αρχείο κειμένου ή αντικαθιστά το υπάρχον και γράφει όλες τις συμβολοσειρές από τον καθορισμένο πίνακα συμβολοσειρών σε αυτό, κάθε συμβολοσειρά σε νέα γραμμή, χρησιμοποιώντας την καθορισμένη κωδικοποίηση.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const ArrayPtr<String> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Το αρχείο που θα δημιουργηθεί ή θα αντικατασταθεί |
| contents | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Ένας πίνακας συμβολοσειρών |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Η κωδικοποίηση χαρακτήρων που θα χρησιμοποιηθεί |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [IEnumerable](../../../system.collections.generic/ienumerable/)
* Κλάση [File](../)
* Χώρος ονομάτων [System::IO](../../)
* Library [Aspose.Slides](../../../)