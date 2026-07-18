---
title: OpenText()
second_title: Αναφορά API Aspose.Slides για C++
description: Ανοίγει το συγκεκριμένο υπάρχον αρχείο για ανάγνωση κειμένου χρησιμοποιώντας κωδικοποίηση UTF-8 χωρίς κοινή χρήση.
type: docs
weight: 261
url: /el/system.io/file/opentext/
---
## File::OpenText(const String\&, const EncodingPtr\&) μέθοδος

Ανοίγει το συγκεκριμένο υπάρχον αρχείο για ανάγνωση κειμένου χρησιμοποιώντας κωδικοποίηση UTF-8 χωρίς κοινή χρήση.

```cpp
static StreamReaderPtr System::IO::File::OpenText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Η διαδρομή του αρχείου προς άνοιγμα |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Η κωδικοποίηση χαρακτήρων που θα χρησιμοποιηθεί |

### Return Value

Ένας κοινόχρηστος δείκτης σε ένα αντικείμενο [StreamWriter](../../streamwriter/) που σχετίζεται με το ανοιγμένο αρχείο

## See Also

* Typedef [StreamReaderPtr](../../../system/streamreaderptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [File](../)
* Χώρος ονομάτων [System::IO](../../)
* Library [Aspose.Slides](../../../)