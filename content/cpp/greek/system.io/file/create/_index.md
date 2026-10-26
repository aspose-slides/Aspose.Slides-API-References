---
title: Create()
second_title: Aspose.Slides για την αναφορά API του C++
description: Δημιουργεί ένα νέο αρχείο (ή αντικαθιστά το υπάρχον) και το ανοίγει για πρόσβαση ανάγνωσης και εγγραφής χρησιμοποιώντας το καθορισμένο μέγεθος buffer και τις επιλογές.
type: docs
weight: 53
url: /el/system.io/file/create/
---
## File::Create(const String\&, int32_t, FileOptions) μέθοδος

Δημιουργεί ένα νέο αρχείο (ή αντικαθιστά υπάρχον) και το ανοίγει για ανάγνωση και εγγραφή χρησιμοποιώντας το καθορισμένο μέγεθος buffer και τις επιλογές.

```cpp
static FileStreamPtr System::IO::File::Create(const String &path, int32_t bufferSize=DefaultBufferSize, FileOptions options=FileOptions::None)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Η διαδρομή του αρχείου προς δημιουργία ή αντικατάσταση |
| bufferSize | **int32_t** | Ο αριθμός των byte που αποθηκεύονται στη μνήμη ενδιάμεσα κατά την ανάγνωση και εγγραφή του αρχείου |
| options | [FileOptions](../../fileoptions/) | Καθορίζει πώς θα δημιουργηθεί ή θα αντικατασταθεί το αρχείο |

### Τιμή επιστροφής

Ένα shared pointer στο αντικείμενο [FileStream](../../filestream/) που σχετίζεται με το καθορισμένο αρχείο

## Δείτε επίσης

* Enum [FileOptions](../../fileoptions/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)